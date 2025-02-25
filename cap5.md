# 5. Técnicas e Padrões de Layout com Flexbox

## 5.1 Criando um layout de coluna responsivo

Para criar um layout de coluna responsivo, é necessário criar um div pai e seus filhos. Onde deve-se utilizar display flex, exemplo de código abaixo:

HTML:
```
    <div class="container">
        <div class="filho1">iner</div>
        <div class="filho1"></div>
        <div class="filho1"></div>
        <div class="filho1"></div>
    </div>
```

CSS:
```
    .container{
        display: flex;
        flex-direction: collumn;
        flex-wrap: wrap;
    }
```

## 5.2 Criando um layout de linha responsivo

Para criar um layout de linha responsivo, é necessário criar um div pai e seus filhos. Onde deve-se utilizar display flex, exemplo de código abaixo:

HTML:
```
    <div class="container">
        <div class="filho1"></div>
        <div class="filho1"></div>
        <div class="filho1"></div>
        <div class="filho1"></div>
    </div>
```

CSS:
```
    .container{
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
    }
```

## 5.3 Centralizando elementos com Flexbox

Para centralizar uma div usando flexbox pode-se seguir o seguinte exemplo de código:

HTML:
```
    <div class="container">
        <div class="box">Centro</div>
    </div>
```

CSS:
```
    .container{
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
    }

    .box{
        background-color: blue;
        padding: 12px;
    }
```

## 5.4 Criando um menu de navegação flexível

Para criar uma nav flexível pode \-se seguir o seguinte exemplo de código:

HTML:
```
    <nav>
        <ul>
            <li>Home</li>
            <li>Produtos</li>
            <li>Serviços</li>
        </ul>
    </nav>
```

CSS:
```
    .ul{
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        justify-content: flex-end;
        gap: 15px;
        list-style: none;
        padding: 0;
        margin: 0;
    }
```

## 5.5 Criando um grid de cards com Flexbox

Para criar grid de cards com flexbox pode-se seguir o seguinte exemplo de código:

HTML:
```
    <div class="container">
        <div class="card">Card 1</div>
        <div class="card">Card 2</div>
        <div class="card">Card 3</div>
        <div class="card">Card 4</div>
    </div>

```

CSS:
```
    .container{
        display: flex;
        flex-wrap: wrap;
        gap: 15px;
        justify-content: center;
    }

    .card {
        width: 200px;
        height: 150px;
        background: gray;
        color: white;
        display: flex;
        justify-content: center;
        align-items: center;
        font-size: 20px;
    }

```
