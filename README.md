##Instalações Necessárias

###Node.js

sudo apt-get install software-properties-common

curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -

sudo apt-get install nodejs

node --version

npm --version

###Angular/cli (versão mais recente)

npm install -g @ angular / cli

ng --version

###Ionic (versão mais recente)

npm install -g @ionic/cli

##Para iniciar a aplicação

ionic start myApp tabs

cd myApp

ionic serve