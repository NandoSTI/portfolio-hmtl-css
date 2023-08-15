# Portfólio HTML - CSS

#### O projeto Portfólio HTML - CSS é uma quest do meu percurso no desafio "Meu Primeiro Site", uma etapa muito importante no Curso de Desenvolvimento Web Fullstack proporcionado pela DEV QUEST - DEV em DOBRO. Este desafio me propôs criar um portfólio inteiramente baseado nos princípios essenciais dessas tecnologias que fundamentam o desenvolvimento web. Agradeço por conferir o meu código e estou aberto a qualquer feedback ou sugestão de melhoria. Espero que aproveitem a visualização do meu portfólio tanto quanto eu aproveitei criá-lo!

## Índice

- [Captura de tela](#captura-de-tela)
- [Links](#links)
- [Construído com](#construído-com)
- [O que aprendi](#o-que-aprendi)
- [Desenvolvimento contínuo](#desenvolvimento-contínuo)
- [Recursos úteis](#recursos-úteis)
- [Fernando Mendes](#autor)

### Captura de tela

#### Tela Desktop

<img src="./src/image/mps-desktop.gif" alt="Tela desktop exibindo funcionalidades">

#### Tela Ipad

<img src="./src/image/mps-ipad.gif" alt="Tela tablet exibindo funcionalidades">

#### Tela Mobile

<img src="./src/image/mps-mobile.gif" alt="Exibindo responsividade no mobile">

### Links

- Site URL: https://nandosti.github.io/portfolio-hmtl-css/

### Construído com

<div style="display: inline_block"><br>
  <img align="center" alt="HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">       
</div>

## O que aprendi

Nesse desafio, aprendi a criar um layout atraente e responsivo utilizando HTML e CSS. Além disso, aprimorei meus conhecimentos em animações e transições, explorando conceitos como keyframes e cubic-bezier para adicionar movimento suave aos elementos da página.

Também compreendi como utilizar o recurso de ancoragem em HTML para direcionar o usuário para diferentes seções da página, tornando a experiência de navegação mais fluida. A técnica de ajustar o tamanho das fontes em relação à viewport (unidade "vw") se mostrou valiosa para criar um design adaptável a diferentes dispositivos.

Aprendi a estruturar o código de forma organizada, utilizando classes e IDs para aplicar estilos de maneira eficiente. Além disso, a experimentação com sombras e efeitos de iluminação trouxe profundidade e destaque aos elementos visuais.

Também explorei a utilização de pseudo-elementos (::before e ::after) para criar padrões visuais como estrelas em movimento, agregando um toque a mais no meu design. As animações CSS foram um componente essencial, e pude aplicar diferentes animações em resposta a ações do usuário, como clicar em seções específicas do site.

No geral, esse projeto me proporcionou um entendimento mais sólido das capacidades do HTML e CSS, bem como habilidades práticas na criação de layouts atraentes e interativos.


## Trechos de códigos

```
  .stars2::after{
    content: " ";
    position: absolute;
    top: 150px;
    width: 1px;
    height: 1px;
    border-radius: 50%;
    box-shadow: 15px 15px white,
      125px 35px white,
      50px 80px white,
      10px 120px white,
      275px 90px white,
      230px 10px white,
      120px 130px white,
      300px 130px white,
      220px 115px white;
  }
@keyframes move-stars {
    from {
        transform: translateY(0px);
    }
    to {
        transform: translateY(-150px);
    }
}


.tracking-in-expand {
	-webkit-animation: tracking-in-expand 1s ease-in-out both;
	animation: tracking-in-expand 1s ease-in-out both;
}


 @-webkit-keyframes tracking-in-expand {
    0% {
      letter-spacing: -0.5em;
      opacity: 0;
    }
    40% {
      opacity: 0.6;
    }
    100% {
      opacity: 1;
    }
  }


```

## Desenvolvimento contínuo

Pretendo continuar focado em construir um conhecimento sólido nessas tecnologias. Ainda há muitos conceitos importantes para serem desenvolvidos. Todos os dias aprendo novos conceitos que são gradativamente adicionados ao meu repertório de ferramentas.

## Recursos úteis

- [Mdn](https://developer.mozilla.org/en-US/) - O Mozilla Developer Network (MDN) desempenha um papel crucial ao fornecer recursos abrangentes e atualizados para desenvolvedores web em todo o mundo.
- [W3School](https://www.w3schools.com/css/default.asp) - O W3Schools é um recurso online amplamente utilizado por desenvolvedores para aprender e aprimorar suas habilidades em tecnologias web.
- [Dev em Dobro](https://www.youtube.com/@DevemDobro) - Este é um canal onde encontro muito material. Tem muito conteúdo relacionado ao desenvolvimento. Recomendo a todos que querem aprender sobre esse e outros conceitos relacionados.

## Autor

[Fernando Mendes](https://www.linkedin.com/in/fernandomendesti/)
