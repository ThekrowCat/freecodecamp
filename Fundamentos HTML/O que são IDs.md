O que são IDs e classes e quando você deve usá-los?
O atributo id adiciona um identificador único a um elemento HTML.

Aqui está um exemplo de um elemento h1 com um id de title.

Abaixo do elemento h1, adicione um elemento h2 com um id definido como "subtitle". Você pode escrever qualquer texto que desejar para o h2 e verá as alterações na janela de visualização. Para interagir com o exemplo, será necessário habilitar o editor interativo.

<h1 id="title">Movie Review Page</h1>

Você pode referenciar o nome id de title dentro do seu JavaScript ou CSS. Aqui está um exemplo de CSS referenciando o id de title para alterar a color do texto para red.

NOTA: Alguns CSS foram fornecidos para você neste exemplo interativo. Não se preocupe em tentar entender o código CSS porque você aprenderá mais sobre isso em lições futuras. Mas se quiser ver a cor do texto mudar para azul, habilite o editor interativo, clique na aba styles.css e altere o color: red; para color: blue;.

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta
       name="viewport"
       content="width=device-width, initial-scale=1.0" />
    <title>Review page Example</title>
    <link rel="stylesheet" href="./styles.css" />
  </head>
  <body>
    <h1 id="title">Movie Review Page</h1>
  </body>
</html>
#title {
  color: red;
}
O símbolo de cerquilha (#) na frente de title indica ao computador que você quer direcionar um id com esse valor. Nomes de id não devem ser usados mais de uma vez e devem ser sempre únicos. Outra coisa a notar sobre valores de id é que eles não podem conter espaços. Aqui está um exemplo de aplicação das palavras main e heading a um valor de atributo id:

<h1 id="main heading">Main heading</h1>
Os navegadores verão esse espaço como parte do id o que levará a problemas indesejados quando se tratar de estilização e script. Os valores do atributo id devem conter apenas letras, dígitos, underscores e traços.

Ao contrário do atributo id, o valor do atributo class não precisa ser único e pode conter espaços.

Aqui está um exemplo de aplicação de uma classe chamada box a um elemento div.

<div class="box"></div>
Se você quiser adicionar múltiplos nomes de classe a um elemento, pode fazer isso separando os nomes por um espaço. Aqui está um exemplo atualizado aplicando múltiplas classes a um elemento div.

<div class="box red-box"></div>
Aqui está outro exemplo de aplicação de múltiplas classes a múltiplos elementos div.

NOTA: Alguns CSS foram fornecidos para você neste exemplo interativo. Não se preocupe em tentar entender o código CSS porque você aprenderá mais sobre isso em lições futuras. Mas se você quiser mudar a cor das primeiras e terceiras caixas, habilite o editor interativo e clique na aba styles.css e mude o background-color: red; para background-color: black;.

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta
       name="viewport"
       content="width=device-width, initial-scale=1.0" />
    <title>Colored boxes example</title>
    <link rel="stylesheet" href="./styles.css" />
  </head>
  <body>
    <div class="box red-box"></div>
    <div class="box blue-box"></div>
    <div class="box red-box"></div>
    <div class="box blue-box"></div>
  </body>
</html>
.box {
  width: 100px;
  height: 100px;
}

.red-box {
background-color: red;
}

.blue-box {
background-color: blue;
}
Então, para recapitular, quando você deve usar um id versus uma class? Classes são melhores quando você quer aplicar um conjunto de estilos a muitos elementos. Se você quiser direcionar um elemento específico, é melhor usar id porque esses valores precisam ser únicos.
