<div align="center">

# <img src="./assets/icon.png" alt="" width="40" align="top"> Vitória Rossini <img src="./assets/icon.png" alt="" width="40" align="top">

> Visite o site: [Vitoria Rossini - Landing Page](https://vitoria-rossini.vercel.app)

</div>

<br>

## Sobre o projeto

Landing page criada para Vitória Rossini, estudante de Fisioterapia no CEUNSP (Itu/SP) com formatura prevista para 2028.

Hoje, a página é a vitrine da jornada acadêmica dela e a porta de entrada para o seu Instagram de estudos, onde ela compartilha aulas, bastidores e tudo o que aprende na faculdade. Depois da formatura, o mesmo site vira o canal profissional para agendar atendimentos em clínica e a domicílio.

O visual foi construído a partir da identidade que ela já usa nos posts do Instagram: verde-sálvia, off-white, fumaça suave e anotações "escritas à mão". A intenção é que quem chegue à página se sinta acolhido e motivado, com tudo explicado de um jeito moderno e fácil de entender.

<br>

## Prévia

<img src="./assets/desktop-inicio.jpg" alt="Tela inicial: “Caso você ainda não me conheça...” com a foto da Vitória em moldura de arco" width="100%">

<table>
  <tr>
    <td width="50%">
      <img src="./assets/desktop-sobre.jpg" alt="Seção Minha história">
      <p align="center"><b>Minha história</b><br><sub>Por que a Fisioterapia, contado por ela</sub></p>
    </td>
    <td width="50%">
      <img src="./assets/desktop-formatura.jpg" alt="Seção de contagem regressiva para a formatura">
      <p align="center"><b>Contagem regressiva</b><br><sub>Anos, meses, dias, horas, minutos e segundos até a formatura</sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <img src="./assets/desktop-jornada.jpg" alt="Seção A jornada, com linha do tempo em quatro etapas">
      <p align="center"><b>A jornada</b><br><sub>Da sala de aula à especialização, um degrau de cada vez</sub></p>
    </td>
    <td width="50%">
      <img src="./assets/desktop-atendimento.jpg" alt="Seção de atendimentos em clínica e a domicílio">
      <p align="center"><b>Atendimentos (em breve)</b><br><sub>Clínica e domicílio, a partir da formatura</sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <img src="./assets/desktop-bastidores.jpg" alt="Seção Por trás do jaleco, com galeria de fotos">
      <p align="center"><b>Por trás do jaleco</b><br><sub>Galeria e o Instagram de estudos</sub></p>
    </td>
    <td width="50%">
      <img src="./assets/desktop-404.jpg" alt="Página 404 personalizada">
      <p align="center"><b>Página 404 temática</b><br><sub>“Ops! Essa página saiu do lugar...”</sub></p>
    </td>
  </tr>
</table>

### No celular

A maior parte das visitas chega pelo Instagram, então a página foi pensada primeiro para o celular.

<img src="./assets/mobile.jpg" alt="Quatro telas da versão mobile: início, minha história, contagem regressiva e bastidores" width="100%">

<br>

## Destaques

- **Contagem regressiva ao vivo** até a formatura, com anos e meses calculados pelo calendário real (não por médias).
- **Linha do tempo da jornada**: estudante → prática clínica → formatura → especialização, com o marcador "Estamos aqui".
- **Abertura animada**: o selo da Fisioterapia se desenha, o nome aparece escrito à mão e a tela se abre ao meio, revelando o início da página.
- **Animações artesanais**: frases que se escrevem à mão, uma seta que se desenha até a foto, ícones que se desenham ao aparecer, cortinas que revelam as fotos e parallax suave. Tudo feito em CSS, sem bibliotecas de animação.
- **Microinterações** no hover: os ícones sobem girando com efeito de mola, ficam verde-escuros, soltam um anel e têm o traço redesenhado; no menu as letras rolam e o selo dá uma volta; os botões ganham um brilho.
- **Responsiva**, sem rolagem lateral, testada de 360px até telas largas.
- **Acessível**: respeita a preferência "reduzir movimento" do sistema, tem navegação por teclado, textos alternativos nas fotos e boa legibilidade.
- **Pronta para compartilhar**: card de prévia para WhatsApp e redes sociais, sitemap, robots e ícone próprio para a tela inicial do iPhone.
- **Rápida**: página estática gerada no build, fotos otimizadas automaticamente (AVIF/WebP) e fontes servidas pelo próprio site.

<br>

## Identidade visual

<img src="./assets/identidade.png" alt="Identidade visual: logo, paleta de cores e tipografia" width="100%">

- **Logo**: redesenho do símbolo da Fisioterapia bordado no jaleco dela (serpentes entrelaçadas e raio), adaptado para a paleta do site.
- **Cores**: verde-sálvia e off-white, as cores preferidas dela, com verde-escuro para contraste, oliva para as anotações à mão e dourado nos detalhes.
- **Tipografia**: Montserrat nos títulos e textos, a mesma dos posts; Gochi Hand nas anotações "escritas à mão".

<br>

## Tecnologias

<div align="center">

[![Next.js](https://img.shields.io/badge/Next.js_16-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org) [![React](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev) [![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org) [![CSS Modules](https://img.shields.io/badge/CSS_Modules-1572B6?style=for-the-badge&logo=cssmodules&logoColor=white)](https://github.com/css-modules/css-modules) [![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com)

</div>

| Camada | Escolha |
| --- | --- |
| Framework | Next.js 16 (App Router), com a página gerada de forma estática |
| Interface | React 19 + TypeScript |
| Estilos | CSS Modules, sem frameworks de CSS |
| Animações | CSS puro (keyframes, IntersectionObserver e *scroll-driven animations*) |
| Imagens e fontes | `next/image` e `next/font` |
| Hospedagem | Vercel |

<br>

## Código-fonte

> [!NOTE]
> O código-fonte deste projeto é **privado**. Este repositório serve apenas como apresentação do trabalho.

<br>

## Direitos

Fotos, textos, nome e marca pertencem a **Vitória Rossini**. Todos os direitos reservados: não é permitido reproduzir ou reutilizar este conteúdo sem autorização.

<!-- Desenvolvido por: Guilherme Francisco Pereira-->

<div align="center">

> Feito com carinho, para a mulher da minha vida. Eu te amo meu amor! 💚

</div>
