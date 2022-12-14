# criar-3-componentes-sendo-2-componentes-filhos-do-componente-principal-utilizando-reactjs
#### Como criar 3 componentes sendo 2 componentes filhos do componente principal utilizando ReactJS

Para criar três componentes, sendo dois componentes filhos do componente principal usando ReactJS, você pode seguir os seguintes passos:

Inicie criando um novo projeto ReactJS usando o comando npx create-react-app no seu terminal:

```
npx create-react-app meu-projeto-react
```

Isso criará um novo projeto ReactJS com o nome "meu-projeto-react" e todas as dependências e arquivos necessários para começar a desenvolver.

Em seguida, abra o arquivo src/App.js e adicione o seguinte código para criar o componente principal e os dois componentes filhos:

```
import React from "react";

function App() {
  return (
    <div>
      <h1>Componente principal</h1>
      <Filho1 />
      <Filho2 />
    </div>
  );
}

function Filho1() {
  return <h2>Componente filho 1</h2>;
}

function Filho2() {
  return <h2>Componente filho 2</h2>;
}

export default App;
```

Isso criará o componente principal App e dois componentes filhos chamados Filho1 e Filho2. O componente principal renderiza os dois componentes filhos dentro dele.

Para verificar se tudo está funcionando corretamente, você pode iniciar o servidor de desenvolvimento usando o comando npm start no seu terminal e acessar o endereço http://localhost:3000 em seu navegador. Você deverá ver o componente principal e os dois componentes filhos sendo renderizados na tela.
Isso é apenas um exemplo básico de como criar três componentes, sendo dois componentes filhos do componente principal usando ReactJS. Você pode personalizar o código de acordo com as suas necessidades e adicionar mais funcionalidades conforme desejar.
