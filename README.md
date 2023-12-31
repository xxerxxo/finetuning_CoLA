
1st Jan 2024

1. Install Homebrew (new laptop)
   - /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   - (echo; echo 'eval "$(/opt/homebrew/bin/brew shellenv)"') >> /Users/hyunkyung/.zprofile
     - Homebrew 환경 설정을 사용자의 .zprofile 파일에 추가(zsh 쉘을 사용할 때마다 자동으로 실행되는 스크립트)
   - eval "$(/opt/homebrew/bin/brew shellenv)"
     - 현재 열려 있는 터미널 세션에 대해 Homebrew 환경 설정을 적용
2. Install wget
   - brew install wget
3. Load data CoLA
   - wget https://nyu-mll.github.io/CoLA/cola_public_1.1.zip
   - unzip cola_public_1.1.zip