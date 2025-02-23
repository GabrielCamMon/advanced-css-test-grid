# Starter Project

Este é um projeto inicial (starter) para facilitar a configuração e desenvolvimento com Sass, PostCSS e autoprefixing.

## Scripts

Este projeto inclui alguns scripts no `package.json` para automatizar tarefas de desenvolvimento. Eles podem ser executados com o comando `npm run <script>` ou `yarn <script>`.

### Scripts disponíveis:

- **watch:sass**  
  Observa alterações no arquivo Sass (`sass/main.scss`) e compila o CSS automaticamente para o arquivo `css/style.css`.
  
  Comando:  
  ```bash
  npm run watch:sass
  ```
- **compile:sass**   
  Compila o arquivo Sass (sass/main.scss) em um arquivo CSS (css/style.comp.css).
  
  Comando:
  ```bash
  npm run compile:sass
  ```
  
- **concat:css**
  
  Concatena os arquivos css/icon-font.css e css/style.comp.css em um único arquivo css/style.concat.css.
  Comando:
  
  ```bash
  npm run concat:css
  ```
  
  
- **prefix:css**
  Adiciona prefixos de compatibilidade para navegadores ao arquivo CSS css/style.concat.css usando o autoprefixer e gera o arquivo css/style.prefix.css.
  Comando:

   ```bash
   npm run prefix:css
   ```
## Dependências de Desenvolvimento
  O projeto usa as seguintes dependências para automação e otimização de CSS:

  - autoprefixer: Adiciona prefixos de compatibilidade automaticamente no CSS.
  - concat: Concatena arquivos CSS em um único arquivo.
  - postcss-cli: Ferramenta de linha de comando para executar PostCSS.
  - sass: Compilador Sass para converter arquivos .scss em .css.

## Instalação
  1. Clone este repositório.
  2. Navegue até a pasta do projeto.
  3. Execute o comando abaixo para instalar as dependências:

     ```bash
      npm install
     ```
     
      Ou, se estiver usando o Yarn:
      
          
           yarn install


     
    
