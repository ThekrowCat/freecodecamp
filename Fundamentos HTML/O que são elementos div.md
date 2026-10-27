O que são elementos div e quando você deve usá-los?
O elemento div é usado como um container para agrupar outros elementos.

Aqui está um exemplo de um elemento div. Adicione outro elemento de parágrafo dentro do elemento div e veja as mudanças na janela de visualização. Para ver as visualizações, você precisará habilitar o editor interativo.

<div>
  <p>Example paragraph element.</p>
</div>
Você usará principalmente o elemento div quando quiser agrupar elementos HTML que compartilharão um conjunto de estilos CSS. Você aprenderá mais sobre CSS em lições e oficinas futuras.

Embora o elemento div seja comumente usado em bases de código do mundo real, você deve ter cuidado para não usá-lo em excesso. Há momentos em que outro elemento seria mais apropriado.

Por exemplo, se você quiser dividir seu conteúdo em seções, então o elemento section seria mais apropriado do que um elemento div.

Adicione outro elemento section abaixo do primeiro. Então, dentro do elemento section, adicione elementos h2 e p. Você pode usar qualquer texto que desejar e verá as mudanças na janela de visualização. Para interagir com o exemplo, será necessário habilitar o editor interativo.

<section>
  <h2>Mammals</h2>
  <p>
    Mammals are warm-blooded animals with fur or hair. Most give birth to live
    young.
  </p>
  <ul>
    <li>Lion</li>
    <li>Elephant</li>
    <li>Dolphin</li>
  </ul>
</section>
O elemento section tem significado semântico em relação ao elemento div, que não é semântico. Semântica é o significado de palavras ou frases em uma linguagem. No HTML, que é uma linguagem, os elementos também têm seu próprio significado semântico. Isso significa que, se você usar um elemento section, o navegador captará seu significado semântico e saberá tratá-lo como uma seção, em desktops, celulares, onde for.
