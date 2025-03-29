# QuizzHub - Descubra se você é um Herói ou Vilão! 🦸

Bem-vindo ao **QuizzHub!** 🚀

Este é um projeto desenvolvido em Angular inspirado no BuzzFeed. O objetivo é responder a uma série de perguntas e, no final, descobrir se você seria um herói ou vilão no mundo dos superpoderes! 🦹

## 🚀 Funcionalidades

✅ Quiz interativo com perguntas e opções de resposta.

✅ Sistema de pontuação para classificar o usuário como Herói ou Vilão.

✅ Interface responsiva e intuitiva.

✅ Desenvolvido com Angular 14.


## 🛠️ Tecnologias Utilizadas

🔹 Angular 14 → Framework para construção do frontend.

🔹 TypeScript → Linguagem utilizada para o desenvolvimento do projeto.

🔹 RxJS → Gerenciamento de estados assíncronos.

🔹 HTML e CSS → Para a estruturação e estilização do quiz.

🔹 Zone.js → Controle de mudanças no Angular.

## 📦 Dependências Principais
```
"dependencies": {
  "@angular/animations": "^14.1.0",
  "@angular/common": "^14.1.0",
  "@angular/compiler": "^14.1.0",
  "@angular/core": "^14.1.0",
  "@angular/forms": "^14.1.0",
  "@angular/platform-browser": "^14.1.0",
  "@angular/platform-browser-dynamic": "^14.1.0",
  "@angular/router": "^14.1.0",
  "rxjs": "~7.5.0",
  "tslib": "^2.3.0",
  "zone.js": "~0.11.4"
},
"devDependencies": {
  "@angular-devkit/build-angular": "^14.1.2",
  "@angular/cli": "~14.1.2",
  "@angular/compiler-cli": "^14.1.0",
  "@types/jasmine": "~4.0.0",
  "jasmine-core": "~4.2.0",
  "karma": "~6.4.0",
  "karma-chrome-launcher": "~3.1.0",
  "karma-coverage": "~2.2.0",
  "karma-jasmine": "~5.1.0",
  "karma-jasmine-html-reporter": "~2.0.0",
  "typescript": "~4.7.2"
}
```

## ▶️ Como Executar o Projeto

### 📌 Pré-requisitos

Antes de iniciar, certifique-se de ter instalado:

• Node.js (versão 14 ou superior)
• Angular CLI

## 🖥️ Passos para rodar o projeto

**1️⃣ Clone o repositório**
```
git clone https://github.com/seu-usuario/quizzhub.git
```
**2️⃣ Acesse o diretório do projeto**
```
cd quizzhub
```
**3️⃣ Instale as dependências**
```
npm install
```
**4️⃣ Execute o projeto**
```
ng serve
```
**5️⃣ Acesse no navegador**
```
http://localhost:4200
```

## 🧐 Como Funciona o Quiz?

O jogo consiste em responder 5 perguntas, onde cada resposta tem um peso de A (vilão) ou B (herói). No final, o sistema analisa as respostas e determina seu perfil com base na maioria das respostas escolhidas.

**Exemplo de Pergunta:**

"Qual super poder você escolheria?"

🔹 Raios-Lasers (A)🔹 Voar (B)🔹 Explodir coisas (A)🔹 Curar feridas (B)🔹 Soltar fogo pelas mãos (A)

**📢 Resultado:**

Se a maioria das suas respostas foi A, você é um Vilão! 😈
Se a maioria das suas respostas foi B, você é um Herói! 🦸


### 🤝 Contribuição

Contribuições são bem-vindas! Se você encontrar bugs, tiver sugestões ou melhorias, fique à vontade para abrir uma issue ou enviar um pull request. 
