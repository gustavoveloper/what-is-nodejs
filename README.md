# NodeJS - Uma impressionante _JavaScript engine_
Aqui, encontram-se registrados estudos sobre JavaScript para desenvolvimento _backend_.
Prezado leitor, sinta-se livre para consumir e contribuir com este conteúdo.


## Um muito breve aviso
Não ache estranha a falta de prática ou de "mão no código": este não é o tipo de foco deste material.


## Meu perfil no Github
Segue meu _username_: [gustavoveloper](https://github.com/gustavoveloper).


## Iniciando...

### O que é JavaScript?
JavaScript é uma linguagem de programação, assim como Python e Java, por exemplo. Sendo uma tecnologia de alto nível, é uma das bases que fundamentam a totalidade da _World Wide Web_, junto com outras ferramentas como Linux, HTML, CSS, PHP, SQL, JSON, etc.

O desenvolvedor Brendan Eich é comumente creditado como o autor da linguagem, cujo nome foi derivado da palavra "Java", que era uma das tecnologias mais comentadas na época em que o JavaScript foi criado. Essa nomenclatura, a propósito, foi uma "jogada de _marketing_".

### CommonJS e ECMAScript
A linguagem JS pode ser implementada de duas maneiras distintas: _CommonJS_ ou _ECMAScript_. Esses dois nomes se referem a diferentes padrões de sintaxe que podem ser utilizados para escrita de código em JavaScript. Mas de onde vieram?

Com o sucesso do JavaScript como linguagem de _scripting_, diversos _browsers_ passaram a implementar seus próprios motores de execução JS (ou de linguagens baseadas/inspiradas em JS), sendo comum um deles utilizar um padrão de sintaxe distinto dos utilizados por outros.

Dada essa confusa variedade de possíveis sintaxes que acabou surgindo para o JavaScript, uma necessidade de serem estabelecidos padrões se mostrou evidente, e a organização ECMA (_European Computer Manufacturers Association_) definiu uma especificação de padrão de sintaxe chamada de _ECMAScript_ para a linguagem, que foi adotada, inclusive, por outras tecnologias (ex.: Dart, JSON).

Para definir o CommonJS, basta dizer que o mesmo consiste da implementação natural do JavaScript que não segue a sintaxe ECMAScript.

### O que é NodeJS?
Antes de explicar o que é NodeJS: **NodeJS não é um _framework_ ou uma biblioteca**. Ele nada mais é que uma _JavaScript engine_, isto é, um motor de execução JavaScript, assim como o V8 usado pela Google, por exemplo. Esse último, a propósito, serviu como base para a construção do primeiro, como é explicado a seguir.