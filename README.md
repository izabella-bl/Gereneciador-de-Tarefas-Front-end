# Gerenciador de Tarefas

O Gerenciador de Tarefas é uma aplicação front-end desenvolvida para permitir que os usuários criem, visualizem, atualizem e excluam suas atividades diárias.

## Objetivos

- Permitir que os usuários criem uma conta e façam login.
- Permitir que os usuários criem, visualizem, atualizem e excluam suas atividades diárias.
- Facilitar a interação visual do usuário com o back-end para operações CRUD.

## Tecnologias Utilizadas

- Angular v17.3.5
- ngx-webstorage
- ngx-bootstrap v12.0.0
- Bootstrap v16.0.0
- Node.js v18.13.0

## Instalação

1. Certifique-se de ter o Node.js instalado em sua máquina. Você pode baixá-lo em [nodejs.org](https://nodejs.org/).

2. Clone o repositório do projeto para sua máquina local:

   ```
   git clone https://github.com/izabella-bl/Gereneciador-de-Tarefas-Front-end/tree/develop
   ```

3. Navegue até o diretório do projeto:

   ```
   cd gerenciador-de-tarefas
   ```

4. Instale as dependências do projeto utilizando o npm:

   ```
   npm install
   ```
### Node.js v18.13.0

O Node.js é um ambiente de tempo de execução JavaScript construído no motor JavaScript V8 do Chrome.

1. Baixe o instalador do Node.js para o seu sistema operacional em [nodejs.org](https://nodejs.org/).

2. Siga as instruções do instalador para instalar o Node.js em sua máquina.

### Angular v17.3.5

O Angular é um framework de desenvolvimento front-end para a construção de aplicativos web. Para instalar o Angular, você precisa primeiro ter o Node.js e o npm (gerenciador de pacotes do Node.js) instalados em sua máquina.

1. Abra o terminal ou prompt de comando.

2. Para instalar o Angular CLI (Interface de Linha de Comando do Angular), execute o seguinte comando:

   ```
   npm install -g @angular/cli@17.3.5
   ```

   Isso instalará o Angular CLI globalmente em sua máquina.

### ngx-webstorage

O ngx-webstorage é uma biblioteca Angular que fornece um serviço para armazenamento web, permitindo armazenar dados no localStorage e sessionStorage do navegador de forma fácil e consistente.

1. Com o Angular CLI instalado, navegue até o diretório do seu projeto Angular no terminal.

2. Execute o seguinte comando para instalar o ngx-webstorage:

   ```
   npm install ngx-webstorage@latest --save
   ```

   Isso instalará o ngx-webstorage e suas dependências no seu projeto Angular.

### ngx-bootstrap v12.0.0

O ngx-bootstrap é uma biblioteca Angular que fornece componentes Bootstrap 4 reescritos em Angular.

1. No diretório do seu projeto Angular, execute o seguinte comando para instalar o ngx-bootstrap:

   ```
   npm install ngx-bootstrap@12.0.0 bootstrap@4.0.0 --save
   ```

   Isso instalará o ngx-bootstrap e o Bootstrap 4 no seu projeto Angular.

### Bootstrap v16.0.0

O Bootstrap é um framework de código aberto para desenvolvimento front-end com HTML, CSS e JavaScript.

1. Você pode incluir o Bootstrap diretamente em seu projeto através de um CDN ou baixando os arquivos de distribuição e adicionando-os manualmente ao seu projeto.

   - **CDN**: Adicione o seguinte link ao seu arquivo HTML:

     ```html
     <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@16.0.0/dist/css/bootstrap.min.css">
     ```

   - **Download Manual**: Você pode baixar os arquivos de distribuição do Bootstrap em [getbootstrap.com](https://getbootstrap.com/docs/5.1/getting-started/download/).


Após seguir esses passos, você terá todas as tecnologias instaladas e estará pronto para desenvolver sua aplicação de gerenciamento de tarefas! Se precisar de mais alguma coisa, estou à disposição para ajudar!

## Executando a Aplicação

Após a instalação das dependências, você pode executar a aplicação localmente utilizando o Angular CLI. Certifique-se de estar no diretório do projeto.

1. Inicie a aplicação:

   ```
   ng serve
   ```

2. Abra o seu navegador e acesse `http://localhost:4200/` para visualizar a aplicação.

## Contribuição

Sinta-se à vontade para contribuir com este projeto! Se você encontrar problemas ou tiver sugestões de melhorias, por favor, abra uma issue ou envie uma pull request.
