# Frontend Mentor - Solução do cartão de resumo de pedido

Esta é uma solução para o [desafio do cartão de resumo de pedido no Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Os desafios do Frontend Mentor ajudam você a melhorar suas habilidades de codificação construindo projetos realistas.

## Índice

- [Visão geral](#visão-geral)
  - [O desafio](#o-desafio)
  - [Captura de tela](#captura-de-tela)
  - [Links](#links)
- [Meu processo](#meu-processo)
  - [Construído com](#construído-com)
  - [O que eu aprendi](#o-que-eu-aprendi)
  - [Desenvolvimento contínuo](#desenvolvimento-contínuo)
  - [Recursos úteis](#recursos-úteis)
- [Autor](#autor)
- [Agradecimentos](#agradecimentos)

## Visão geral

### O desafio

Os usuários devem ser capazes de:

- Ver os estados de foco para elementos interativos

### Captura de tela

![Screenshot-Order-Summary](https://imgur.com/iHjRiIY.png)

### Links

- URL da solução: [Adicione a URL da solução aqui](https://your-solution-url.com)

## Meu processo

### Construído com

- Marcação HTML5 semântica;
- Propriedades personalizadas do CSS;
- Conceito de Flexbox.

### O que eu aprendi

- Aprendi a utlização prática das medidas ```rem```, sendo completamente responsivas trazendo conforto tanto para quem desenvolve quanto para o usuário final;
- Compreendi mais um pouco sobre o uso de ```display:flex```, ```align-items: center;```, ```justify-content: center;``` e ```flex-direction: column;``` tornando futuro estudos mais confortável sobre este conceito, como neste trecho:
```css
  main section {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    padding: 0 2rem;
    height: 100%;
    width: 100%;
}
```
- O uso expansivo das estilizações utlizando ```class=""``` dentro do ```HTML``` e ```CSS```, um trecho que evidência muito bem o que quero expressar é este:

```html
    <section>
      <h1>Order Summary</h1>
      <span class="description">You can now listen to millions of songs, audiobooks, and podcasts on any
        device anywhere you like!
      </span>

      <div class="informations">
        <div class="music-price">
          <img src="images/icon-music.svg" alt="Musica Icon">
          <div class="price">
            <strong>Annual Plan</strong>
            <span>$59.99/year</span>
          </div>
        </div>
        <a href="#">Change</a>
      </div>

      <button>Proceed to Payment</button>
      <a href="#" id="cancel-order">Cancel Order</a>
      <div class="attribution">
        Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>.
        Coded by <a href="https://github.com/BrianMunizSilveira">Brian Muniz Silveira</a>.
      </div>
    </section>
```

### Desenvolvimento Contínuo

Use esta seção para delinear áreas nas quais você deseja continuar focando em futuros projetos. Estes podem ser conceitos com os quais você ainda não está completamente confortável ou técnicas que achou úteis e que deseja refinar e aperfeiçoar.

### Recursos Úteis

- [Vídeo explicativo da Giovanna Moeller](https://www.example.com) - Sua didática foi fundamental para a realização deste desafio.
- [Imgur.com](https://imgur.com/) - Este recurso é de grande ajuda para upar imagens para usar em diversos locais de forma simples e eficiente, tanto é que estou usando bem aqui neste repositório: [Captura de tela](#captura-de-tela)

## Autor

- Website - [Brian Muniz Silveira](https://www.your-site.com)
- Frontend Mentor - [@BrianMunizSilveira](https://www.frontendmentor.io/profile/BrianMunizSilveira)
- Instagram - [@mxlfylxrd](https://www.instagram.com/mxlfylxrd/)

## Agradecimentos

Quero agradecer a explicações e o tempo dedicado da [Giovanna Moeller](https://github.com/giovannamoeller) por ter dado a oportunidade de além de realizar o desafio, ter uma ótima didática durante o seu vídeo no Youtube: [Desafio Front-end Mentor #1 - Card de Resumo do Pedido - HTML/CSS](https://www.youtube.com/watch?v=ap_KHxw4Q_E). Meus sinceros agradecimentos.