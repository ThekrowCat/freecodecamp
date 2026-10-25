UTF-8, ou UCS Transformation Format 8, é uma codificação de caracteres padronizada amplamente usada na web. Codificação de caracteres é o método que os computadores usam para armazenar caracteres como dados. Essencialmente, todo texto em uma página web é uma sequência de caracteres armazenados como um ou mais bytes. Em computação, um byte é uma unidade de dados composta por 8 bits, ou dígitos binários. UTF-8 suporta todos os caracteres do conjunto de caracteres Unicode, incluindo caracteres e símbolos de todos os sistemas de escrita, idiomas e símbolos técnicos. Aqui está um exemplo de uso do elemento meta com o atributo charset para definir a codificação de caracteres como UTF-8:

<meta charset="UTF-8" />
Ao definir a codificação de caracteres para UTF-8, isso garantirá que o caractere acentuado "e" (é) seja exibido corretamente na página. Aqui está um exemplo de código estendido usando a codificação de caracteres UTF-8:

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Examples of the UTF-8 encoding</title>
  </head>
  <body>
    <p>Café</p>
  </body>
</html>
Para cada novo projeto que você criar, você deve incluir este elemento meta com o atributo charset definido como UTF-8.
