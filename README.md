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

### [Padrões de Código - Styleguides](http://willianjusten.teachable.com/courses/103968/lectures/1578417)

* Uma das coisas mais importantes nas boas práticas é a utilização de um **style guide**.
* Um **style guide** é um documento que contém os **padrões de código** que serão utilizados em um projeto.
* Um **código padronizado** facilita a *leitura* e *manutenção* do código de um grande projeto entre os membros da equipe.
* Um dos style guides **mais conhecidos** e utilizados em JavaScript é o do Airbnb e pode ser acessado em https://github.com/airbnb/javascript.
* Recomenda-se fazer uma **leitura completa** do style guide.
* Outro style guide bastante conhecido é o **Standard JS** e pode ser acessado em https://standardjs.com/.
* Mais um style guide bastante conhecido é o **Idiomatic JavaScript** criado pelo Rick Waldron e pode ser acessado em https://github.com/rwaldron/idiomatic.js.
* A ferramenta de análise de código **mais utilizada** antigamente era o **JSHint**.
* Existiam também **outras ferramentas** como **JSLint** e **JSCS**.
* O **JSCS** utilizava o conceito de presets e exibia o erro de maneira amigável.
* O **JSCS** funcionava como um linter e um formatador de código.
* O ESLint é a ferramenta de análise de código **mais utilizada** hoje em dia.
* O ESLint fará a **verificação do código** de acordo com as **regras definidas**.
* O ESLint pode ser configurado para rodar no **editor de texto** ou na **linha de comando**, por exemplo.

### [Instalando e Usando o Eslint](http://willianjusten.teachable.com/courses/103968/lectures/1578420)

* Recomenda-se instalar o ESLint no **diretório do projeto** e não globalmente.
* Utiliza-se o comando `npm install eslint --save-dev` para **instalar o ESLint** no diretório do projeto.
* Utiliza-se o comando `./node_modules/.bin/eslint --init` para **inicializar as configurações** do ESLint para o prjeto.
* O **executável** do ESLint encontra-se do diretório `node_modules/.bin` do projeto.
* Após executar o **comando de configuração** serão realizadas perguntas sobre *utilizar algum style guide existente* ou *definir as suas próprias regras* e o **formato do arquivo de configuração**.
* Após isso, serão instalados alguns **pacotes complementares** como `eslint-plugin-import` e `eslint-config-airbnb-base` e o **arquivo de configuração** `.eslintrc.js` será criado.
* Para **realizar a verificação** utiliza-se o comando `./node_modules/.bin/eslint *.js`.
* Será listada *linha*, *tipo*, *mensagem* e *regra* para cada **inconsistência** encontrada.
* Algumas **regras** são `no-undef`, `no-unused-vars`, `semi`, `no-redeclare`, `quotes` e `eol-last`.
* É possível **integrar** o ESLint com o **editor de texto** predileto como o Sublime Text.
* Para o Sublime Text pode-se utilizar os pacotes `SublimeLinter` e `SublimeLinter-contrib-eslint`.

### [Configurando o editorconfig](http://willianjusten.teachable.com/courses/103968/lectures/1578421)

* O **EditorConfig** permite definir **regras de configuração** para o editor de texto.
* Deve-se criar um arquivo `.editorconfig` na raiz do diretório do projeto com as **configurações necessárias**.
* Neste arquivo pode-se definir as **regras** e as **extensões dos arquivos** que as regras serão aplicadas.
* Algumas **regras** são `ident_style`, `ident_size`, `end_of_line`, `charset` e `trim_trailing_whitespace`.
* Deve-se **instalar o plugin** do EditorConfig no seu editor de texto predileto.

### [Criando um NPM Script](http://willianjusten.teachable.com/courses/103968/lectures/1578860)

* O **NPM Script** é um script que pode ser **rodado** através do NPM.
* Normalmente cria-se NPM scripts para tarefas como *transpiling de JavaScript* ou *pré-processamento de estilos*, por exemplo.
