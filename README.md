# Curso JavaScript com TDD na Prática

## Boas Práticas

### [Introdução](http://willianjusten.teachable.com/courses/103968/lectures/1573102)

* É importante utilizar um **guia de estilos** em um projeto.
* Recomenda-se utilizar **hooks do Git** para a verificação de qualidade de código.
* Recomenda-se utilizar o Babel para fazer o **transpiling** do ES6.
* Recomenda-se utilizar o Webpack como **ferramenta de bundling**.
* É importante conhecer a teoria de testes, TDD e integração contínua.
* É importante entender como **configurar** e **utilizar** o NPM e o como funcionam os **NPM scripts**.

### [Configurando o NPM e Criando o package.json](http://willianjusten.teachable.com/courses/103968/lectures/1577434)

* Para iniciar o diretório no Git utiliza-se o comando `git init`.
* O arquivo `package.json` é é responsável por conter as **dependências** e **versões das bibliotecas** utilizadas no projeto.
* Recomenda-se utilizar o NPM para o **gerenciamento de dependências**.
* Recomenda-se possuir uma conta no NPM para permitir a **publicação de projetos**.
* O site do NPM é `www.npmjs.com`.
* Utiliza-se os comandos `npm set init-author-name`, `npm set init-author-email`, `npm set init-author-url` e `npm set init-author-license` para definir o **nome**, **e-mail**, **url** e **licença** padrões ao criar projetos com o NPM.
* Utiliza-se o comando `npm adduser` para **realizar o login** no NPM e informar usuário, senha e e-mail.
* Utiliza-se o comando `npm init` para **iniciar um projeto** utilizando o NPM para gerenciamento de dependências.
* Ao iniciar um projeto deve-se informar nome do projeto, versão, descrição, entrypoint entre outros.
* No final do projeto, um esboço do arquivo `package.json` é exibido.

### [Criando o gitignore de forma simples](http://willianjusten.teachable.com/courses/103968/lectures/1577435)

* O arquivo `.gitignore` permite **ignorar arquivos e diretórios** que não necessitam serem versionados no Git.
* Sugere-se utilizar a ferramenta de linha de comando **gitignore** para gerar arquivos `.gitignore` de diferentes plataformas.
* Utiliza-se o comando `npm install gitignore -g` para instalar a ferramenta **gitignore** de forma global no ambiente.
* Utiliza-se o comando `gitignore -types` para **listar as opções disponíveis** de plataformas para a geração de arquivos `.gitignore`.
* Utiliza-se o comando `gitignore Node` para gerar um arquivo `.gitignore` para projetos JavaScript.
* O arquivo `.gitignore` deve ser versionado no Git.

### [Criando arquivos para documentação](http://willianjusten.teachable.com/courses/103968/lectures/1578395)

* A **documentação** é parte fundamental em um projeto de software.
* O **arquivo README** é o arquivo principal do GitHub que contém uma *apresentação inicial*, *como utilizar a biblioteca*, *boas práticas* entre outros.
* O repositório [awesome-readme](https://github.com/matiassingers/awesome-readme) possui *artigos* e *exemplos* de como fazer uma **boa documentação**.
* Pode-se utilizar o **template** do arquivo README para o seu projeto que pode ser encontrado em https://gist.github.com/PurpleBooth/109311bb0361f32d87a2.
* Um **arquivo README** é composto por *título*, *badges* (tamanho, se os testes estão passando e a versão do NPM), *descrição*, *estrutura de diretórios*, *trechos de códigos*, *gifs animados*, *porque utilizar a ferramenta*, *como contribuir* e a *licença*.
* Recomenda-se utilizar os arquivos `README.md`, `CONTRIBUTING.md` e `LICENSE.md` em um projeto e nomeá-los com letras maiúsculas.
* O arquivo `CONTRIBUTING.md` deve conter instruções de **como contribuir** com o projeto.
* O arquivo `LICENSE.md` deve conter a **licença** utilizada pelo projeto e pode ser obtida em `opensource.org`.