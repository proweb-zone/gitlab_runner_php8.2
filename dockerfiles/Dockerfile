FROM gitlab/gitlab-runner:latest

RUN apt-get update
RUN apt install software-properties-common -y
RUN add-apt-repository ppa:ondrej/php -y
RUN apt-get install php8.2 php8.2-common php8.2-cli -y
RUN apt-get install php8.2-xml -y
RUN apt-get install php-codesniffer -y

