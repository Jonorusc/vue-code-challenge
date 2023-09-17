# O desafio
A proposta geral do sistema é disponibilizar uma área onde deve ser possível gerenciar e consultar 
empresas a partir de um mapa geral

![](video.gif)


# Instruções de Instalação 

Este guia fornecerá as etapas necessárias para configurar e executar o aplicativo em seu ambiente de desenvolvimento local.

## Pré-requisitos

Certifique-se de ter as seguintes ferramentas instaladas em seu sistema:

- [Node.js](https://nodejs.org) - Utilizamos o Node.js para executar o código JavaScript do aplicativo.
- [npm](https://www.npmjs.com/) - Gerenciador de pacotes JavaScript (geralmente é instalado junto com o Node.js).
- [yarn](https://classic.yarnpkg.com/lang/en/docs/install/) - Gerenciador de pacotes JavaScript.

## Passos de Instalação

1. **Clone o repositório:**

```sh
git clone https://github.com/Jonorusc/convicti-test.git
cd convicti-test
cd client
```

3. **Instale as dependências:**

  ```sh 
  yarn 
  ## OR
  yarn install
  ```

3. **Configure as variáveis de ambiente:**

Renomeie o arquivo .env.example para .env e configure as variáveis de ambiente necessárias, como chaves de API, configurações de banco de dados, etc.

4. **Inicie o aplicativo:**

  ```sh 
  yarn dev
  ```
Apos o loading a página abrirá automáticamente em seu navegador padrão
