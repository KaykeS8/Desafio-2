# Desafio-2 da Codelândia

<img src="img/shop.png" alt="Exemplo de aplicação">

## 1º Crie variaveis em seu css isso vai facilitar sua vida. Para usar variáveis CSS é simples:

p{
 color: var(--title);
}

<p>
    Dessa forma nossa tag 'p' terá a cor #313131.
    Por que usar variáveis? Se for uma aplicação grande, será chato ficar procurando todos os títulos da página para mudar de cor.
    Com a variável é só mudar o valor dela e assim será aplicada em toda aplicação!
</p>

<p>
    Qualquer dúvida leia esse post que fiz sobre como declarar variáveis no CSS
    Post sobre variáveis no CSS => <a href="https://www.instagram.com/p/CO6F8r4gXVw/">https://www.instagram.com/p/CO6F8r4gXVw/</a>
</p>

<p>
    Caso você não entenda sobre cores, também fiz um post sobre
    Post sobre cores => <a href="https://www.instagram.com/p/CMqGBTmj2KW/">https://www.instagram.com/p/CMqGBTmj2KW/</a>
</p>

<p>Além disso, no arquivo tem um CSS de reset no navegador.</p>

-------------------------------------------------------------------------------------------------------------------------------------------------------------

## 2º A estrutura toda do desafio pode ser feita usando Flexbox, assim fica melhor na hora de fazer a responsividade ou utilize grid.

<p>Essas propriedades FlexBox ou Grid já são o suficiente:</p>

<code>
    #nomeDiv{
     display: flex;
     align-items: center;
     justify-content: space-between;
     flex-wrap: wrap; //Ele vai fazer com que o nosso flexbox quebre;
    }
    
    #nomeDiv {
     display: grid;
     grid-template-columns: repeat(4, 1fr);
     grid-template-rows: repeat(2, 250px);
    }
</code>

<p>Post sobre justify-content => <a href="https://www.instagram.com/p/CMQNUOjA_nM/" target="_blank">https://www.instagram.com/p/CMQNUOjA_nM/</a></p>
<p>Post sobre align-items => <a href="https://www.instagram.com/p/CMVUmSHAWZx/">https://www.instagram.com/p/CMVUmSHAWZx/</a></p>

-------------------------------------------------------------------------------------------------------------------------------------------------------------

## 3º A imagem (wallpaper.jpeg) você pode colocar um:

<img src="img/fundo.jpeg" alt="Imagem do exemplo">

<code>
    
    #div img {
      filter: brightness(50%);
    }
    
    #div img {
      backdrop-filter: brightness(50%);
    }
</code>

<p>
    para assim a imagem ficar mais escura, ou se preferir pode mudar em algum editor de imagem.
</p>

-------------------------------------------------------------------------------------------------------------------------------------------------------------


-------------------------------------------------------------------------------------------------------------------------------------------------------------
<p>
    Post sobre centralizar no CSS => <a href="https://www.instagram.com/p/COgbhA-DvGN/">https://www.instagram.com/p/COgbhA-DvGN/</a>
</p>

-------------------------------------------------------------------------------------------------------------------------------------------------------------


