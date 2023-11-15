ARG VERSION=14
FROM node:$VERSION-alpine
RUN apk update
RUN apk upgrade
RUN apk add openjdk17
RUN apk add tmux
RUN apk add git
EXPOSE 3000
ENV abcd=wtf
RUN apk add python3
RUN apk add py3-pip
RUN apk add make automake gcc g++ subversion python3-dev
RUN apk add py3-pandas
RUN apk add py3-scikit-learn
RUN apk add py3-scikit-build
RUN pip3 install --upgrade pip
RUN apk add zsh
RUN apk add vim
RUN apk add neovim
RUN apk add curl
RUN apk add lynx
RUN sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
#RUN apt install tmux
#USER node
WORKDIR /morestuff
COPY . .
