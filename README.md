
# 🚀 Introdução ao Desafio


Neste desafio, você colocará à prova seus conhecimentos sobre funções e testes unitários. O objetivo é implementar diversas funções no arquivo `src/index.js` e garantir que todas elas sejam devidamente testadas através de testes unitários no arquivo `__tests__/index.test.js`.


Este é o momento de reforçar seus aprendizados sobre criação de funções e assegurar que seu código esteja devidamente coberto por testes, uma prática essencial para qualquer desenvolvedor.



## Instruções

### 1. Fork do Repositório
   - Um "fork" é uma cópia de um repositório que fica no seu perfil GitHub. Você faz um fork para ter uma versão própria do projeto na qual você pode trabalhar. Isso permite que você modifique e experimente o código sem afetar o repositório original.

     
#### Como forkar?

[Link como fazer Fork](https://github.com/campinho-digital/Como-fazer-um-Fork)

### 2. Após o Fork

- Clonar o Repositório Forkado
  
Abra o terminal ou o Git Bash em seu computador.


### Clone o repositório forkado para o seu computador com o seguinte comando:

~~~javascript
git clone seu_repositorio
~~~


### Navegue até a pasta do repositório clonado:

~~~javascript
cd seu_repositorio
~~~

#### ⚠️ Atenção 

Quando você clona um repositório, o Git cria uma nova pasta no seu sistema contendo todos os arquivos e a estrutura do projeto. Para trabalhar com esse projeto (editar arquivos, rodar scripts, instalar dependências, etc.), você precisa estar dentro dessa pasta. Se não navegar para essa pasta, você estará em uma localização diferente no seu sistema e os comandos que tentar rodar (como npm install ou git) não funcionarão corretamente, pois eles precisam ser executados no diretório correto.


### 3. Instalar Dependências
Se o projeto utiliza npm, você deve instalar as dependências:

~~~javascript
npm install

~~~

#### ⚠️ Atenção 
Se o projeto utiliza o Node.js e tem um arquivo package.json, você precisa rodar npm install para instalar todas as bibliotecas e dependências que o projeto necessita para funcionar. Sem isso, o projeto pode não rodar corretamente.

### 4. Abrir o Arquivo index.js
Abra seu editor de código preferido (por exemplo, Visual Studio Code).
No editor, abra o arquivo `index.js` que está no repositório.

- Cada participante deverá responder individualmente às questões propostas no arquivo `index.js`
- Lembre-se de sempre comentar o código respondido para explicar o que está sendo feito.
- Para cada questão, remova o comentário do console.log() relacionado àquela questão. Isso ajudará a testar e debugar o código.


### 5. Rodando o projeto
Use o comando `npm start` no terminal para executar o projeto e testar as respostas que você implementou no arquivo index.js.

~~~javascript
npm start
~~~

O código será executado, e você poderá ver a saída do `console.log` no terminal.

### 6. Testando seu código com o  `Jest`

   - Escreva suas funções no arquivo src/index.js.
  ##### Todas as funções devem ser corretamente exportadas usando module.exports. Este é o arquivo onde você implementará as funcionalidades solicitadas.

   - O arquivo de testes já está pronto!
#### O arquivo de testes `__tests__/index.test.js` já está configurado e preparado para rodar os testes das funções que você escrever. Você não precisa criar novos arquivos de teste, apenas certifique-se de que todas as funções que você implementar no `index.js` estão cobertas pelos testes.

- Certifique-se de testar todas as funções que você escreveu!
Cada função que você criar no `src/index.js` deve ser testada no arquivo de teste correspondente. Se você adicionar uma nova função, certifique-se de que existe um teste para ela no arquivo de testes `__tests__/index.test.js`

Rode os testes com o Jest.
Para verificar se suas funções estão corretas, execute o seguinte comando no terminal:

~~~javascript
npm test
~~~

Ao finalizar os testes você deverá ver a seguinte mensagem informando que todos os seus testes passaram:

<img width="435" alt="Captura de Tela 2024-09-17 às 10 39 23" src="https://github.com/user-attachments/assets/5b725553-d228-455e-ba8c-c2c7f719a58e">

### 7. Versionamento com Git
Depois de responder às questões e adicionar comentários ao código, você precisa versionar essas alterações usando o Git.

### 8. Enviar o Repositório para o Moodle

Você deve enviar o link do repositório com as questões respondidas para o Moodle, para que o instrutor possa revisar o seu trabalho. O link do GitHub facilita o acesso ao código e também permite que o instrutor veja todo o histórico de commits (versões anteriores do código), o que é útil para acompanhar seu progresso.


### Links úteis


[Funções](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide/Functions)

[Funções no JS](https://www.javascriptprogressivo.net/2018/12/Funcao-Parametro-Argumento-Retorno.html)

[Testes de Unidade](https://aws.amazon.com/pt/what-is/unit-testing/)

[Anatomia de um teste em JavaScript](https://gabrieluizramos.com.br/anatomia-de-um-teste-em-javascript)

[Jest Doc](https://jestjs.io/pt-BR/docs/setup-teardown#repetindo-a-configura%C3%A7%C3%A3o-para-v%C3%A1rios-testes)

[Import e export no JS](https://www.alura.com.br/artigos/como-funciona-o-import-e-export-do-javascript?srsltid=AfmBOoo-2uSgAbPe7kN4e8KPMtQFEa49Az5_2_I-WRVOL-2qHmgtA4KF)






