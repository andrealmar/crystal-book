# Linguagem de Programação Crystal

Esta é a documentação referente à linguagem de programação Crystal.

Crystal é uma linguagem de programação que tem os seguintes objetivos:

* Ter uma sintaxe similar à da linguagem Ruby (mas compatibilidade com a mesma não é um objetivo).
* Ser estaticamente tipada, mas sem precisar especificar o tipo das variáveis ou o tipo dos argumentos nos métodos.
* Poder chamar código C através de bindings.
* Ter avaliação e geração de código em tempo de compilação, afim de evitar código boilerplate.
* Compilação para código nativo eficiente.

## Contribuindo para este manual de referência da Linguagem

Você gosta de ajudar? Se achar um bug ou alguma seção neste manual que precisa de correção, você é muito bem-vindo a contribuir com a documentação. Você pode submeter um pull request para este repositório:
https://github.com/crystal-lang/crystal-book

Muito Obrigado!

### Realizando Build e Servindo Localmente

```
$ git clone https://github.com/crystal-lang/crystal-book.git
$ cd crystal-book
$ npm install -g gitbook-cli@2.3.0
$ npm install
$ gitbook serve
Live reload server started on port: 35729
Press CTRL+C to quit ...

info: 8 plugins are installed
info: loading plugin "ga"... OK
...
Starting server ...
Serving book on http://localhost:4000

```

O Html vai estar na pasta `_book` (alguns links não irão funcionar se você abri-los localmente).

Está disponível também um ambiente Docker se preferir:

```
$ docker-compose up
...
gitbook_1  | Starting server ...
gitbook_1  | Serving book on http://localhost:4000
gitbook_1  | Restart after change in file node_modules/.bin
...
```

### Adicionando uma página

Para adicionar uma página, crie um arquivo markdown aonde você preferir. Exemplo: `overview/hello_world.md`. Então, adicione um link no arquivo `SUMMARY.md` que funciona como um menu de navegação para a documentação.
