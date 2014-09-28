OS-X-Setup-for-Development
==========================

MAC OS X (Mavericks ou superior) Setup for Development

baseado neste projeto do GITHUB [https://github.com/nicolashery/mac-dev-setup](https://github.com/nicolashery/mac-dev-setup)

### Premissas

1. Sistema Maverics ou superior
2. Java 8
3. Tomcat 8
4. Maven 3
5. PlantUML e gRaphviz
6. MySQL
7. git 2 ou superior


    top -o cpu -i 30 -s 7 -n 10 
    ruby --version 
    ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" 
    git config --global user.email "you@example.com"
    git config --global user.name "Your Name"
    git config --global user.email "joao.parana@gmail.com"
    git config --global user.name "Joao Ferreira"
    ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" 
    brew doctor 
    brew update 
    brew outdated
    # download JDK 8 from Oracle java site and install 
    echo 'export PATH="/usr/local/bin:$PATH"' >> ~/.bash_profile
    cat ~/.bash_profile 
    source  ~/.bash_profile 
    echo $PATH
    java -version
    brew install git
    brew install tomcat 
    brew install maven
    brew install ant 
    # Download Eclipse Luna for JEE Developers and install it
    brew install mysql 
    brew install graphviz
    git --version
    brew list --versions 
    # instaling Consolas font
    brew install cabextract 
    mkdir consolas
    cd consolas/
    curl -O http://download.microsoft.com/download/f/5/a/f5a3df76-d856-4a61-a6bd-722f52a5be26/PowerPointViewer.exe 
    cabextract PowerPointViewer.exe 
    cabextract ppviewer.cab 
    open CONSOLA*.TTF 
    # And click Install Font. 
    cd ..
    mkdir profile 
    cd profile/
    curl -O https://raw.githubusercontent.com/nicolashery/mac-dev-setup/master/.bash_profile 
    curl -O https://raw.githubusercontent.com/nicolashery/mac-dev-setup/master/.bash_prompt
    curl -O https://raw.githubusercontent.com/nicolashery/mac-dev-setup/master/.aliases 
    cd ..
    mkdir gitconfig 
    cd gitconfig
    curl -O https://raw.githubusercontent.com/nicolashery/mac-dev-setup/master/.gitconfig 
    # let's enable Git password caching
