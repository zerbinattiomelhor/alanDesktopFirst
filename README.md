# alanDesktopFirst 
<p>Neste projeto, criamos um layout de perfil utilizando HTML e CSS com foco em um design simples e responsivo. A implementação começou com a estrutura básica do HTML, onde definimos uma área de perfil que contém uma imagem circular, o nome da pessoa e uma breve descrição. Além disso, foram adicionados três cartões abaixo do perfil, cada um contendo uma imagem e uma breve descrição.

Para o estilo da página, utilizamos CSS, onde o primeiro passo foi garantir que todos os elementos fossem resetados, removendo margens e preenchimentos padrões. O fundo da página foi configurado para preto (`#000`), enquanto a cor do texto foi definida como branco (`#fff`), para criar um contraste visual nítido. 

A seção do perfil foi centralizada utilizando `text-align: center`, e a imagem de perfil foi ajustada para ficar em formato redondo com a propriedade `border-radius: 50%`. Para garantir que a imagem ficasse centralizada dentro do círculo e mantivesse suas proporções, utilizamos `display: flex`, juntamente com `justify-content: center` e `align-items: center`, e a propriedade `object-fit: cover` foi aplicada à imagem, fazendo com que ela preenchesse o círculo sem distorções.

Os cartões foram organizados em um layout flexível, permitindo que eles se ajustassem à largura da tela. Cada cartão foi estilizado com um fundo cinza escuro para manter a coerência com o fundo preto da página, e a cor do texto dentro dos cartões também foi mantida em branco. 

Além disso, garantimos a responsividade do layout com uma regra CSS de `@media`, onde a largura e o tamanho dos elementos são ajustados para telas menores, como dispositivos móveis. O layout flexível para os cartões foi modificado para um formato em coluna em dispositivos menores, garantindo uma boa visualização e usabilidade.

Com essas implementações, o resultado foi um layout moderno, simples e funcional, adaptável a diferentes resoluções de tela e com um contraste visual adequado para facilitar a leitura e navegação.</p>
