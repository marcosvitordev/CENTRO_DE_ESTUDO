# Manual de Sobrevivencia

O Manual de sobrevivência tem como objetivo juntar informações do Centro de Estudo Sena.

O projeto utiliza o [Docsify](https://github.com/docsifyjs/docsify) para construir o site. As páginas são escritas em [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/) e renderizadas pelo Docsify no lado do cliente.

## Editar

Todas as páginas estão disponíveis na pasta `/paginas`. Para editar uma página, basta alterar o conteúdo do seu respectivo arquivo `.md`.

## Adicionar uma nova pagina
Para adicionar uma nova pagina: 
- criar um novo arquivo `.md` na pasta `/paginas`.
- Adicione a seguinte linha ao arquivo `_sidebar.md`:
   * [`<ion-icon name="nome do icon"></ion-icon> Nome da Pagina](paginas/nome_do_Arquivo.md "Titulo da pagina")`
   - `nome do icone`: Nome do ícone que acompanhará o link na barra lateral. Você pode consultar os ícones disponíveis no [ion-Icons](https://ionic.io/ionicons).
   `titulo da pagina`: Título da página na barra lateral.  
   `nome_do_Arquivo`: Nome do arquivo da página correspondente.  

### Editando a página inicial

Para editar o conteúdo da página inicial, basta alterar o conteúdo do arquivo `_coverpage.md`.

## Executando localmente

Para executar localmente, você precisará da versão LTS do [Node.js](https://nodejs.org) mais recente.

Primeiro, instale a interface de linha de comando do Docsify executando o seguinte comando no terminal:

        npm install -g docsify-cli

Depois, no diretório raiz do projeto, execute:

        docsify serve

No navegador da sua preferência, acesse `https://localhost:3000` para visualizar o site.
