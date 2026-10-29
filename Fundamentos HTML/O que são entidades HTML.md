Uma entidade HTML, ou referência de caractere, é um conjunto de caracteres usados para representar um caractere reservado em HTML.

Vamos supor que você queira exibir o texto This is an <img/> element na tela. Se você usar o código que está atualmente no editor, ele não exibirá o resultado desejado. Mesmo que você adicione os atributos src e alt ao exemplo, ele mostrará uma imagem no meio do parágrafo. Não é o resultado desejado. Para interagir com o exemplo, você precisará ativar o editor interativo.

<p>This is an <img /> element</p>
Quando o analisador HTML vê o símbolo de menor que (<) seguido pelo nome de uma tag HTML, ele interpreta isso como um elemento HTML. Por isso você não está vendo o resultado desejado de This is an <img/> element na tela.

Para corrigir esse problema, você pode usar entidades HTML. Aqui está um exemplo atualizado usando as entidades HTML corretas para os símbolos less-than (<) e greater-than (>). Agora você deve ver This is an <img/> element na tela.

Ative o editor interativo e tente adicionar um &lt;p&gt;learning is fun&lt;/p&gt; abaixo do elemento parágrafo. Você deve ver <p>learning is fun</p> na tela.

<p>This is an &lt;img /&gt; element</p>

Esses tipos de referências de caracteres são conhecidos como referências de caracteres nomeadas. Referências nomeadas começam com um sinal de e comercial (&) e terminam com um ponto e vírgula (;). Ao usar uma referência de caractere nomeada, o parser HTML não confundirá isso com um elemento HTML real.

Outro tipo de referência de caractere seria a referência numérica decimal. Esta referência de caractere começa com um sinal de e comercial e o símbolo de cerquilha (#), seguido por um ou mais dígitos decimais, seguido por um ponto e vírgula.

Aqui está um exemplo de uso da referência numérica decimal para o símbolo de menor que.

Ative o editor interativo e altere o código para ver símbolos diferentes. Você pode usar &#169; para o símbolo de copyright e &#174; para o símbolo de marca registrada.

&#60;
O último tipo de referência de caractere seria a referência numérica hexadecimal. Esta referência de caractere começa com um sinal de e comercial, símbolo de cerquilha e a letra x. Em seguida, é seguido por um ou mais dígitos hexadecimais ASCII e termina com um ponto e vírgula.

Aqui está um exemplo de uso da referência numérica hexadecimal para o símbolo de menor que.

Ative o editor interativo e altere o código para ver símbolos diferentes. Você pode usar &#x20AC; para o símbolo do euro e &#x03A9; para o símbolo da letra grega maiúscula Ômega.

&#x3C;
