# Dev Tools Installation
Script / Commands to install basic dev tools 


## Dev Tools

- Git

- Curl

- NodeJS

- Yarn

- ohmyzsh

- Terminator


## Project Specific Tools

- OpenJDK-8

- Default JRE

- SBT

- Intellij IDEA ( Community edition )


## Softwares

- Python

- Docker


```

$ sudo apt update && sudo apt upgrade && sudo apt install curl && sudo apt-get install -y nodejs && sudo apt-get install gcc g++ make && curl -sL https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add - && echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list && sudo apt-get update && sudo apt-get install yarn && sudo apt install git && sudo apt install default-jre && sudo apt install openjdk-8-jdk && echo "deb https://dl.bintray.com/sbt/debian /" | sudo tee -a /etc/apt/sources.list.d/sbt.list && sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 2EE0EA64E40A89B84B2DF73499E82A75642AC823 && sudo apt update && sudo apt-get install sbt && sudo snap install intellij-idea-community --classic --edge && sudo apt-get install terminator && sudo apt install python3 && sudo apt install apt-transport-https ca-certificates curl software-properties-common && curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add - && sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable" && sudo apt update && apt-cache policy docker-ce && sudo apt install docker-ce && sudo systemctl status docker
```


Anyone can improve this
