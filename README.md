# App-food

Este é um projeto de um aplicativo de delivery desenvolvido com **React Native** e estilizado utilizando **TailwindCSS**. A aplicação inclui funcionalidades básicas como navegação, exibição de produtos e interações com uma API local.

## Como executar o projeto
### 1. Rodar o Frontend
1. Navegue até a pasta do projeto no terminal.
2. Instale as dependências:
   
    ```
   npm install
    ```
4. Inicie o frontend 
    ```
    npm start
    ```

### 2. Rodar a API local
1. Certifique-se de estar na pasta principal do projeto.
2. Inicie a API utilizando o comando:
   
    ```
    npx json-server db.json
    ```

### 3. Configurar os IPs nas URLs de chamada de API
As URLs de chamada de API estão configuradas nos seguintes arquivos localizados em **src/components**:
- restaurants/index.tsx
- restaurantsList/index.tsx
- trending/index.tsx

1. Localize as URLs de chamada de API nos arquivos mencionados.
2. Substitua o IP antigo pelo endereço IP da sua máquina.
