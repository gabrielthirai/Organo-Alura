# Aula da alura - Front-end - React

## Como iniciar um projeto React?

Usando o npx você pode iniciar um projeto react.

```
npx create-react-app organo
```

npm é para coisas locais, npx é de forma remota

## Dentro do projeto

Para facilitar o desenvolvimento do projeto e para facilitar a manutenção, criaremos compenentes de cada coisa que queremos no site, dessa forma fica mais facil de organizar e reparar futuramente.

## Criando o Banner

Criamos o Banner.js e dentro dele abrimos uma function para poder começar, e exportamos para futuramente importar, dentro da function colocamos o return e os parenteses significa que é um return de multiplas linhas.

Dentro do App.js, temos que importar o Banner.js

```
<Banner/>
```

Juntamente com o import

```
import Banner from './componentes/Banner/Banner';
```

Para podermos customizar e deixar mais bonito, vamos utilizar o css, criaremos o banner.css, e a gente consegue codificar ele da forma que ele é.

Dentro de Banner.js colocaremos o import do css

```
import './Banner.css'
```

Em js a palavra class ja é reservada do próprio js, então para podermos criar uma classe aqui, utilizaremos o className.

```
    <header className='banner'>
        <img src="/imagens/banner.png" alt="Banner principal da pagina do organo"/>
    </header>
```