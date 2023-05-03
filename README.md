<img src="https://github.com/Lucas-Araujo15/dt-money/blob/main/cover.png">

# DT Money
Esse projeto busca desenvolver uma aplicação de controle de finanças pessoais, permitindo que o usuário visualize seu saldo e despesas.

## Funcionalidades
- Cadastrar nova transação como entrada ou saída
- Visualizar transações cadastradas
- Buscar uma transação específica
- Visualizar saldo do usuário

## Principais tecnologias
- React.js
- Vite.js
- TypeScript
- styled-components
- Radix UI
- JSON Server

## Como executar o projeto?

### Pré-requisitos
Para executar este projeto, é necessário ter instalado em seu computador:

- [Node.js](https://nodejs.org/) (versão 12 ou superior)

Você pode verificar se o Node.js está instalado digitando o seguinte comando em seu terminal:

```
node -v
```

### Instalação
1. Faça um clone do repositório para a sua máquina local:

```
git clone https://github.com/Lucas-Araujo15/dt-money
```

2. Instale as dependências do projeto com o gerenciador de pacotes npm:

```
cd dt-money
npm install
```

### Executando
Após instalar as dependências, execute o seguinte comando para rodar a aplicação em modo de desenvolvimento:

```
npm run dev
```

Isso iniciará a aplicação em um servidor local em http://localhost:5173.

Para iniciar a simulação do servidor, execute o seguinte comando:

```
npm run dev:server
```

Este comando irá disponibilizar uma API REST fake que permitirá o teste de todas as funcionalidades.