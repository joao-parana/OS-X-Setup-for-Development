OS-X-Setup-for-Development
==========================

MAC OS X (Mavericks ou superior) Setup for Development

Baseado neste projeto do GITHUB [https://github.com/nicolashery/mac-dev-setup](https://github.com/nicolashery/mac-dev-setup)

Ver também este outro Fork : [https://github.com/jfrazelle/mac-dev-setup](https://github.com/jfrazelle/mac-dev-setup)

### Premissas

#### Sistema Maverics ou superior
#### Java 8
#### Tomcat 8
#### Maven 3
#### PlantUML e Graphviz
#### MySQL
#### git 2 ou superior
#### Sublime 3


    top -o cpu -i 30 -s 7 -n 10 
    ruby --version 
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
    git config --global user.email "you@example.com"
    git config --global user.name "Your Name"
    git config --global user.email "joao.parana@gmail.com"
    git config --global user.name "Joao Ferreira"
    # They will get added to your .gitconfig file.
    # To push code to your GitHub repositories, we're going to use the recommended HTTPS 
    # method (versus SSH). So you don't have to type your username and password everytime, let's
    # enable Git password caching as described here:
    git config --global credential.helper osxkeychain
    # Note: On a Mac, it is important to remember to add .DS_Store (a hidden OS X 
    # system file that's put in folders) to your .gitignore file


Para instalar o pacote de suporte a linguagem Swift da Apple use este link: [https://sublime.wbond.net/packages/Swift](https://sublime.wbond.net/packages/Swift) 

Após ter baixado os arquivos `.bash_profile`, `.bash_prompt` e `.aliases`  copie para o diretório HOME

Também adicione ao final do arquivo `~/.aliases` as linhas abaixo

    alias gitrm='git rm -r --cached Exemplo001.xcodeproj/project.xcworkspace/xcuserdata'
    alias gph='git push -u origin master '
    alias gpl='git pull origin master '
    alias gpf='git add -A . ; git commit -m "Adicionando Funcionalidades" ; git push -u origin master '
    alias gpe='git add -A . ; git commit -m "Corrigindo erros" ; git push -u origin master '
    alias git-override-and-update='git fetch --all ; git reset --hard origin/master' 
    


