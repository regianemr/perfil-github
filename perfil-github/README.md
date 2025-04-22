# 🔍 Buscador de Usuários GitHub

Este é um projeto desenvolvido em **React** utilizando **Yarn** como gerenciador de pacotes. Ele permite buscar perfis públicos de usuários do GitHub e exibir informações como nome, foto de perfil e bio, com base em um layout proposto no Figma.

## 📸 Demonstração do Projeto

### Tela Inicial
>![Tela inicial]('./src/assets/perfil-github1.png')

### Busca por usuário
>![Demonstração do projeto](https://github.com/regianemr/perfil-github/blob/main/perfil-github/src/assets/perfil-github1.png)

### Busca por usuário não existente seguida de mensagem de erro
>![Demonstração do projeto]('./src/assets/perfil-github3.png')

>![Demonstração do projeto]('./src/assets/perfil-github4.png')


## 🚀 Funcionalidades

- Campo de busca para nome de usuário do GitHub
- Consumo da API pública do GitHub
- Exibição de nome, avatar e bio
- Mensagem de erro caso o usuário não seja encontrado
- Interface responsiva e customizada

## 🛠️ Tecnologias utilizadas

- [React](https://reactjs.org/)
- [Axios](https://axios-http.com/)
- [Yarn](https://yarnpkg.com/)
- CSS Modules

## 📦 Como rodar o projeto

### Pré-requisitos

- Node.js instalado
- Yarn instalado

### Passos:

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/nome-do-repo.git

# Acesse a pasta do projeto
cd nome-do-repo

# Instale as dependências
yarn install

# Inicie o projeto
yarn dev

```

## ❌ Tratamento de Erros

Se o nome de usuário digitado não for encontrado, uma mensagem amigável será exibida ao usuário informando o erro.

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).