
<h1 align="center">
    <img alt="NextLevelWeek" title="#NextLevelWeek" src="./.github/banner.png" />
</h1>

<h4 align="center"> 
	🚧  DevRadar :satellite: Concluído 🚀 🚧
</h4>

<p align="center">
 <a href="#-sobre-o-projeto">Sobre</a> •
 <a href="#-funcionalidades">Funcionalidades</a> •
 <a href="#-layout">Layout</a> • 
 <a href="#-como-executar-o-projeto">Como executar</a> • 
 <a href="#-tecnologias">Tecnologias</a> • 
 <a href="#-autor">Autor</a>
</p>


## 💻 Sobre o projeto

:satellite: DevRadar - O DevRadar é um projeto que visa conectar desenvolvedores próximos a você que trabalham com as mesmas tecnologias.


Projeto desenvolvido durante a **Semana Omnistack 10** oferecida pela [Rocketseat](https://rocketseat.com.br/).
A Semana Omnistack é uma experiência online com muito conteúdo prático, desafios e hacks onde o conteúdo fica disponível durante uma semana.

---

## ⚙️ Funcionalidades

- [x] Desenvolvedores podem se cadastrar na aplicação enviando:
  - [x] usuário do github
  - [x] tecnologias com que trabalha
  - [x] localização (latitude e longitude) 

- [x] No aplicativo móvel, os usuários podem:
  - [x] navegar pelo mapa e procurar desenvolvedores por tecnologia
  - [x] acessar a página de perfil do github de usuários cadastrados no app

---

## 🎨 Layout

### Mobile

<p align="center">
  <img alt="NextLevelWeek" title="#NextLevelWeek" src="./.github/mobile.png" width="1000px">
</p>

### Web

<p align="center" style="display: flex; align-items: flex-start; justify-content: center;">
  <img alt="NextLevelWeek" title="#NextLevelWeek" src="./.github/web.png" width="1000px">
</p>

---

## 🚀 Como executar o projeto

Este projeto é divido em três partes:
1. Backend (pasta backend) 
2. Frontend (pasta frontend)
3. Mobile (pasta mobile)

💡Tanto o Frontend quanto o Mobile precisam que o Backend esteja sendo executado para funcionar.

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/). 
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

#### 🎲 Rodando o Backend (servidor)

```bash

# Clone este repositório
$ git clone https://github.com/naMoraezDev/AirCnC-Full-Stack-App.git

# Acesse a pasta do projeto no terminal/cmd
$ cd AirCnC-Full-Stack-App-main

# Vá para a pasta server
$ cd backend

# Instale as dependências
$ npm install 
ou 
$ yarn install

# Execute a aplicação em modo de desenvolvimento
$ npm run dev:server
ou
$ yarn dev

# O servidor inciará na porta:3333 - acesse http://localhost:3333 

```

#### 🧭 Rodando a aplicação web (Frontend)

```bash

# Clone este repositório
$ git clone https://github.com/naMoraezDev/AirCnC-Full-Stack-App.git

# Acesse a pasta do projeto no seu terminal/cmd
$ cd AirCnC-Full-Stack-App-main

# Vá para a pasta da aplicação Front End
$ cd frontend

# Instale as dependências
$ npm install
ou
$ yarn install

# Execute a aplicação em modo de desenvolvimento
$ npm run start
ou
$ yarn start

# A aplicação será aberta na porta:3000 - acesse http://localhost:3000

```

#### :space_invader: Rodando a aplicação mobile (mobile)

```bash

# Clone este repositório
$ git clone https://github.com/naMoraezDev/AirCnC-Full-Stack-App.git

# Acesse a pasta do projeto no seu terminal/cmd
$ cd AirCnC-Full-Stack-App-main

# Vá para a pasta da aplicação Front End
$ cd mobile

# Instale as dependências
$ npm install
ou
$ yarn install

# Execute a aplicação em modo de desenvolvimento
$ npm run start
ou
$ yarn start

```

---

## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

#### **Front-End**  ([React](https://reactjs.org/))

-   **[React Dom](https://github.com/facebook/react/tree/master/packages/react-dom)**
-   **[React Scripts](https://github.com/facebook/create-react-app/tree/master/packages/react-scripts)**
-   **[Axios](https://github.com/axios/axios)**
-   **[testing-library/jest-dom](https://github.com/testing-library/jest-dom)**
-   **[testing-library/react](https://github.com/testing-library/react-testing-library)**
-   **[testing-library/user-event](https://github.com/testing-library/user-event)**

#### **Back-End**  ([NodeJS](https://nodejs.org/en/))

-   **[Axios](https://github.com/axios/axios)**
-   **[Express](https://expressjs.com/)**
-   **[CORS](https://expressjs.com/en/resources/middleware/cors.html)**
-   **[Mongoose](https://mongoosejs.com/docs/)**
-   **[Socket.io](https://github.com/socketio/socket.io)**

#### **Mobile**  ([React Native](http://www.reactnative.com/))

-   **[Axios](https://github.com/axios/axios)**
-   **[Expo](https://expo.io/)**
-   **[React Dom](https://github.com/facebook/react/tree/master/packages/react-dom)**
-   **[React Native Gesture Handler](https://github.com/software-mansion/react-native-gesture-handler)**
-   **[React Native Reanimated](https://github.com/software-mansion/react-native-reanimated)**
-   **[React Navigation](https://reactnavigation.org/)**
-   **[React Navigation Stack](https://github.com/react-navigation/stack)**
-   **[React Native Web](https://github.com/necolas/react-native-web)**
-   **[Socket.io Client](https://github.com/socketio/socket.io-client)**
-   **[Expo Location](https://docs.expo.io/versions/latest/sdk/location/)**
-   **[React Native Maps](https://github.com/react-native-maps/react-native-maps)**
-   **[React Native Safe Area Context](https://github.com/th3rdwave/react-native-safe-area-context)**
-   **[React Native Screens](https://github.com/software-mansion/react-native-screens)**
-   **[React Native Webview](https://github.com/react-native-webview/react-native-webview)**

---

## 💪 Como contribuir para o projeto

1. Faça um **fork** do projeto.
2. Crie uma nova branch com as suas alterações: `git checkout -b my-feature`
3. Salve as alterações e crie uma mensagem de commit contando o que você fez: `git commit -m "feature: My new feature"`
4. Envie as suas alterações: `git push origin my-feature`

---

## 🦸 Autor

Feito com ❤️ Gabriel Moraes :wave: [Entre em contato!](https://www.linkedin.com/in/gabriel-moraes-5572b2145/)
