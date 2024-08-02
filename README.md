# aula-1-JS
-Definição JavaScript 

É uma linguagem de programação amplamente usada no desenvolvimento web para criar páginas interativas e dinâmicas. Sua principal função é adicionar comportamento e interatividade às páginas web, permitindo atualizações de conteúdo e respostas a ações do usuário sem precisar recarregar a página. 

  

-História e Evolução do JavaScript 

1995: Criado por Brendan Eich como LiveScript, renomeado para JavaScript; 

1997: Padronizado como ECMAScript 1.; 

1999: ECMAScript 3.0 trouxe melhorias significativas. 

2005: Popularização do Ajax, impulsionando o uso de JavaScript para aplicações web dinâmicas. 

2009: ECMAScript 5.0 introduziu novos recursos como JSON. 

2015: Lançamento do ECMAScript 6.0 (ES6) com grandes melhorias, incluindo classes e arrow functions. 

2016-2023: Lançamento de versões anuais do ECMAScript com novas funcionalidades e aprimoramentos contínuos. 

  

-Variáveis 

Em JavaScript, variáveis são usadas para armazenar dados que podem ser manipulados no código. São declaradas usando três principais palavras-chave: 

Tipos de Variáveis em JavaScript 

JavaScript permite declarar variáveis usando três palavras-chave principais: 

-var: 

Declaração: var nome = valor; 

Características: var é a forma mais antiga de declarar variáveis e possui escopo de função, o que significa que a variável é visível em toda a função onde foi declarada. Se declarada fora de uma função, a variável é global. var também permite que você redeclare a variável na mesma função ou no mesmo bloco, o que pode levar a comportamentos inesperados. 

-let: 

Declaração: let nome = valor; 

Características: Introduzido no ECMAScript 6 (ES6), let tem escopo de bloco, ou seja, é visível apenas dentro do bloco onde foi declarada. Isso evita problemas de variáveis vazadas e permite uma maior flexibilidade e controle sobre o escopo. let não permite a redeclaração da variável no mesmo bloco. 

-const: 

Declaração: const nome = valor; 

Características: Também introduzido no ES6, const é usado para declarar constantes, ou seja, valores que não podem ser alterados após a atribuição inicial. Assim como let, const tem escopo de bloco. A tentativa de redeclarar ou reatribuir um valor a uma variável const resulta em um erro. 

Regras para Nomes de Variáveis 

-Nomes válidos devem começar com uma letra (a-z, A-Z), um underscore (_), ou um cifrão ($). 

-Nomes de variáveis não podem começar com um número. 

-Nomes são sensíveis a maiúsculas e minúsculas (por exemplo, nome e Nome são diferentes). 

-Evite usar palavras reservadas da linguagem como nomes de variáveis. 

-Tipos de Dados em JavaScript 

Número: Representa valores numéricos. Ex: let idade = 30; 

String: Sequências de caracteres. Ex: let nome = 'João'; 

Booleano: Valores true ou false. Ex: let estaChovendo = true; 

Undefined: Variável sem valor atribuído. Ex: let valor; 

Null: Ausência intencional de valor. Ex: let pessoa = null; 

Symbol: Valor único e imutável. Ex: const id = Symbol('id'); 

BigInt: Números inteiros grandes. Ex: let numeroGrande = 1234567890123456789012345678901234567890n; 

Objeto: Coleção de propriedades e valores. Ex: let pessoa = { nome: 'Maria', idade: 28 }; 

Array: Lista ordenada de valores. Ex: let frutas = ['maçã', 'banana']; 

-Funções em JavaScript 

Funções são blocos de código reutilizáveis que realizam tarefas específicas. Podem ser criadas de três formas principais: 

Declaração de Função: Exemplo: function saudacao(nome) { return Olá, ${nome}!; } 

Expressão de Função: Exemplo: const saudacao = function(nome) { return Olá, ${nome}!; }; 

Função Arrow: Exemplo: const saudacao = (nome) => Olá, ${nome}!; 

-JavaScript manipula HTML e CSS para atualizar o conteúdo e o estilo da página dinamicamente. 

-DOM é uma representação em árvore do documento, permitindo que JavaScript acesse e modifique a estrutura e o conteúdo da página.
  
-Navegadores: 

Google Chrome, Mozilla Firefox, Microsoft Edge, Safari — oferecem ferramentas de desenvolvedor para testar e depurar JavaScript diretamente no navegador. 

Editores de Código: 

Visual Studio Code (VS Code), Sublime Text, Atom — editores populares com suporte para JavaScript e recursos como autocomplete e depuração. 

IDEs: 

WebStorm — IDE focado em JavaScript com suporte avançado para depuração e desenvolvimento. 

Eclipse — IDE de código aberto que pode ser configurado para JavaScript via plugins. 

Ferramentas Online: 

JSFiddle, CodePen, JSBin — ambientes online para testar e compartilhar código HTML, CSS e JavaScript. 


Ambientes de Desenvolvimento Local: 

Node.js — permite executar JavaScript no servidor, fora do navegador. 

NPM (Node Package Manager) — gerencia pacotes e dependências para projetos JavaScript. 

  
Sistemas de Controle de Versão: 

Git — para versionamento e colaboração em projetos JavaScript, frequentemente usado com GitHub ou GitLab. 


-Recursos úteis para aprender JavaScript: 

  
Sites e Documentação: 

MDN Web Docs: MDN Web Docs — Documentação abrangente e tutoriais. 

W3Schools: W3Schools JavaScript Tutorial — Tutoriais interativos. 

JavaScript.info: JavaScript.info — Guia completo sobre JavaScript. 

Eloquent JavaScript: Eloquent JavaScript — Livro gratuito e interativo. 


Tutoriais e Cursos Online: 

freeCodeCamp: freeCodeCamp — Cursos gratuitos e desafios práticos. 

Codecademy: Codecademy JavaScript Course — Curso interativo. 

Coursera: Coursera JavaScript Courses — Cursos de universidades. 

Udemy: Udemy JavaScript Courses — Vários cursos, de iniciantes a avançados. 

Pluralsight: Pluralsight JavaScript Path — Cursos detalhados. 

  

Comunidades e Fóruns: 

Stack Overflow: Stack Overflow JavaScript — Perguntas e respostas. 

Reddit (r/javascript): r/javascript — Discussões e compartilhamento de recursos. 
