Qual é o papel do elemento script no HTML e como ele pode ser usado para vincular arquivos JavaScript externos?
O elemento script é usado para incorporar código executável. A maioria dos desenvolvedores usará isso para executar código JavaScript. JavaScript é usado para adicionar interatividade às suas páginas web. Exemplos comuns de uso de JavaScript incluem jogos interativos, sliders de imagem e formulários dinâmicos que validam a entrada do usuário em tempo real.

Aqui está um exemplo de uso do elemento script em um documento HTML. Remova o // que está na frente do alert("Welcome to freeCodeCamp"); e você deverá ver um alerta aparecer. Para ver as prévias, você precisará ativar o editor interativo.

<body>
  <script>
    // alert("Welcome to freeCodeCamp");
  </script>
</body>
Embora você possa tecnicamente escrever todo o seu código JavaScript dentro das tags script, é considerado uma boa prática vincular a um arquivo JavaScript externo. Aqui está um exemplo de uso do elemento script para vincular a um arquivo JavaScript externo:

<script src="path-to-javascript-file.js"></script>

O atributo src é usado aqui para especificar a localização desse arquivo JavaScript externo. src significa "source". A razão pela qual não é recomendado colocar todo o seu JavaScript dentro do documento HTML é por causa da separação de responsabilidades. Separação de responsabilidades é um princípio de design onde você separa seus programas em seções distintas e faz com que cada seção trate de uma responsabilidade diferente. Neste caso, queremos separar nosso código JavaScript do nosso código HTML.
