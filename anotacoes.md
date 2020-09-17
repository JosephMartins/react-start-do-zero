## Babel

O babel serve para transpilar codigo JSX para Funçoes de React, Tambem
transforma javascript novo -const em javascript antigo  -Var

Para criar um elemento HTML com React o Babel utiliza a seguinte sintaxe

JSX: 

function App(){
  return <div class="classe">Ola</div>
}

Babel transpiling: 

function App(){
  return React.createElement(
  "div", 
  {
    class: "classe"
  },
  "Ola"
  );
}

## Parametros do React.createElement()
# Parametro 1
  O elemento HTML exp: Div, H1, h2, form
# Parametro 2
  O atributos do elemento exp: Class, Id
# Parametro 3
  O conteudo dos elementos