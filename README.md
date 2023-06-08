<p align="center">
 <img alt="Repository language count" src="https://img.shields.io/github/languages/count/didifive/queue-service-app">
    <a href="https://www.linkedin.com/in/luis-carlos-zancanela/">
        <img alt="Made by Didi" src="https://img.shields.io/badge/made%20by-Didi-green">
    </a> 
    <a href="https://github.com/didifive/queue-service-app/commits/master">
        <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/didifive/queue-service-app?color=blue">
    </a>
    <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen?color=blue">
</p>

<p align="center">
 <a href="https://angular.io/">
   <img alt="Angular" src="https://img.shields.io/static/v1?color=red&label=Dev&message=Angular&style=for-the-badge&logo=Angular">
 </a>
</p>

# 🚶🚶🚶 Queue Service APP - Filas

## 💾 Controle de senhas para atendimento

Este projeto foi desenvolvido para controle de senhas para atendimento com filas personalizadas, podendo cadastrar filas
com Tipos de Prioridades Dinâmicos, permitindo ir além do padrão "Prioritário e Normal", ficando a critério da necessidade.
Com as senhas salvas em banco é possível também construir relatórios de como foi o atendimento.

## 📼 Escopo

O sistema, considerando back e front-end deve atender os seguintes requisitos:

- Ter cadastro de empresa;
- Para os usuários, ter os perfis de Administrador, Atendente e Usuário;
- Ter cadastro de filas com nome e sigla, exemplo: nome "Caixa" e sigla "CX";
- As filas devem permitir prioridades personalizadas (Normal, Prioritário, Idoso 80+ etc);
- As senhas devem seguir sequencia numérica com o prefixo sendo a sigla da fila, exemplo: "CX001";
- Senhas devem possuir um sufixo conforme abreviação do Tipo de Atendimento, exemplo: "CX001N", onde o "N" é abreviatura
  para Tipo de Atendimento Normal;
- As senhas devem possuir data e hora de geração e de finalização, se foi atendida, deve possuir quem foi o atendente;
- O Administrador tem acesso total ao sistema, podendo inclusive alterar ou desativar outros usuários;
- O Atendente apenas chama e finaliza as senhas marcando como atendida ou não atendida;
- O Atendente pode ver apenas senhas das filas em que foi autorizado;
- O Usuário pode fazer a configuração do sistema, como criar filas, zerar número da fila, vincular (ou desvincular)
  atendente de uma fila e editar dados da empresa que o Usuário faz parte;
- Deve possuir um terminal para emissão de senhas, este deve ser logado por um alguém com perfil de Usuário para
  disponibilizar as filas para emissão de senhas da empresa em que está vinculado;
- Gerar saída para emissão de senha em equipamento de impressão térmica.

## 📱 Queue Service API - Front-End

Este projeto aborda somente o APP em Front-End.  

Foi criado para fins de estudos, prática e testes. Aproveite para fazer melhorias ou personalização.  
Apesar de este projeto ser público e não ter finalidade comercial, ainda assim foi pensado para resolver problema real,
portanto é possível utilizar esta base para um projeto comercial.  
Licença: [MIT License](https://mit-license.org/).  

### ⭐ Destaques:

- ~~Em construção~~

#### 👉 _TO DO:_

- ~~Em construção~~

### 📗 Configuração do Projeto

~~Em construção~~

#### 💻 Executar com terminal

~~Em construção~~

```bash
em-construcao
```

#### 💻 Executar com IDE

~~Em construção~~

## 🔧 Tecnologias

- Angular 16.0.5
- Node.js v18.13.0
- npm 9.2.0
- Typescript 5.0.4
- Material UI 16.0.3
- ~~Em construção~~

🔨 IDE Utilizada: [VSCode] v.1.78.2

---

## 🎨 Visuais

Logotipo:  
![Filas Logo](docs/logotipo.png?raw=true "Filas Logo")  


## 📜 Back-end em Java para este projeto

O back-end para este projeto está disponível no repositório [didifive/queue-service-api]. Visite o repositório para informações sobre o desenvolvimento do back-end e de como instalá-lo para executar em conjunto com este projeto front-end

---

📋 Qualquer dúvida, sugestão ou crítica é só entrar em contato ou abrir uma Issue (https://github.com/didifive).  
💚 Feito com muita dedicação e aprendizado. #EnjoyThis

---

📎 Links Interessantes:

* [Angular]
* [Node.js]
* [npm]
* [VSCode]
* [Typescript]
* [Material UI]

[Angular]: https://angular.io/
[Node.js]: https://nodejs.org/en
[npm]: https://www.npmjs.com/
[VSCode]: https://code.visualstudio.com/
[Typescript]: https://www.typescriptlang.org/
[Material UI]: https://material.angular.io/
[didifive/queue-service-api]: https://github.com/didifive/queue-service-api
[didifive/queue-service-app]: https://github.com/didifive/queue-service-app