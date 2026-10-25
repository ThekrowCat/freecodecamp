Qual é o papel do elemento Link no HTML e como ele pode ser usado para vincular a folhas de estilo externas?
Vamos aprender sobre o elemento link e como usá-lo para vincular a folhas de estilo externas.

O elemento link é usado para vincular a recursos externos como folhas de estilo e ícones do site. Aqui está a sintaxe básica para usar o elemento link para um arquivo CSS externo:

<link rel="stylesheet" href="./styles.css" />
O atributo rel é usado para especificar a relação entre o recurso vinculado e o documento HTML. Nessa situação, precisamos especificar que esse recurso vinculado é um stylesheet.

É considerado uma boa prática separar seu HTML e CSS em arquivos diferentes. Desenvolvedores usarão o elemento link para seu arquivo CSS externo em vez de escrever tudo no documento HTML.

O atributo href é usado para especificar a localização da URL para o recurso externo.

O . seguido de uma barra no exemplo indica para o computador procurar na pasta atual, ou diretório, pelo arquivo styles.css.

O elemento link deve ser colocado dentro do elemento head como mostrado no exemplo a seguir:

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Examples of the link element</title>
  <link rel="stylesheet" href="./styles.css" />
</head>
Frequentemente você verá múltiplos elementos link dentro de um código profissional que fazem link para diferentes folhas de estilo, fontes e ícones. Aqui está um exemplo de uso do elemento link para fazer link para uma fonte externa do Google chamada Playwrite Cuba:

<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link
  href="https://fonts.googleapis.com/css2?family=Playwrite+CU:wght@100..400&display=swap"
  rel="stylesheet"
/>
Google Fonts são um conjunto de fontes personalizadas gratuitas e de código aberto que você pode usar em qualquer projeto. Você pode escolher quais fontes deseja usar e o Google fornecerá o código HTML e CSS necessário. Neste exemplo, o valor preconnect para o atributo rel informa ao navegador para criar uma conexão antecipada com o valor especificado no atributo href. Isso é feito para acelerar os tempos de carregamento desses recursos externos.

Outro caso de uso comum para o elemento link é vincular a ícones. Aqui está um exemplo de como vincular a um favicon:

<link rel="icon" href="favicon.ico" />
Um favicon, que é a abreviação de favorite icon, é um pequeno ícone normalmente exibido na aba do navegador ao lado do título do site. Muitos sites usam um favicon para exibir o ícone da sua marca.
