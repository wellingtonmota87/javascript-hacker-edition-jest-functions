## Instruções

1. Fork do Repositório
   - Um "fork" é uma cópia de um repositório que fica no seu perfil GitHub. Você faz um fork para ter uma versão própria do projeto na qual você pode trabalhar. Isso permite que você modifique e experimente o código sem afetar o repositório original.

     
#### Como forkar?

Faça o fork desse repo: [https://github.com/campinho-digital/Como-fazer-um-Fork](https://github.com/campinho-digital/Como-fazer-um-Fork)  


2. Após o Fork

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


3. Instalar Dependências
Se o projeto utiliza npm, você deve instalar as dependências:

~~~javascript
npm install

~~~

#### ⚠️ Atenção 
Se o projeto utiliza o Node.js e tem um arquivo package.json, você precisa rodar npm install para instalar todas as bibliotecas e dependências que o projeto necessita para funcionar. Sem isso, o projeto pode não rodar corretamente.

4. Abrir o Arquivo index.js
Abra seu editor de código preferido (por exemplo, Visual Studio Code).
No editor, abra o arquivo `index.js` que está no repositório.

- Cada participante deverá responder individualmente às questões propostas no arquivo `index.js`
- Lembre-se de sempre comentar o código respondido para explicar o que está sendo feito.
- Para cada questão, remova o comentário do console.log() relacionado àquela questão. Isso ajudará a testar e debugar o código.


5. Testar o Projeto
Use o comando `npm start` no terminal para executar o projeto e testar as respostas que você implementou no arquivo index.js.

~~~javascript
npm start
~~~

O código será executado, e você poderá ver a saída do `console.log` no terminal.

6. Testando seu código com o  `Jest`
   
- Crie um arquivo de teste para o index.js (normalmente na pasta __tests__ ou diretamente no diretório principal)
  

Execute o Jest com o seguinte comando::
~~~javascript
npm test
~~~

O código será executado, e você poderá ver a saída do `console.log` no terminal.

7. Versionamento com Git
Depois de responder às questões e adicionar comentários ao código, você precisa versionar essas alterações usando o Git.

8. Enviar o Repositório para o Moodle

Você deve enviar o link do repositório com as questões respondidas para o Moodle, para que o instrutor possa revisar o seu trabalho. O link do GitHub facilita o acesso ao código e também permite que o instrutor veja todo o histórico de commits (versões anteriores do código), o que é útil para acompanhar seu progresso.


### Links úteis
