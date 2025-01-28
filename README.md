# Projeto X-Men

Este é um projeto de uma página web interativa onde o usuário pode selecionar personagens do universo X-Men para visualizar informações detalhadas sobre cada um deles. O layout da página é responsivo, se ajustando a diferentes tamanhos de tela, e utiliza uma abordagem simples de front-end com HTML, CSS e JavaScript.

## Sumário

- [Descrição do Projeto](#descrição-do-projeto)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Estrutura de Diretórios](#estrutura-de-diretórios)
- [Como Rodar o Projeto](#como-rodar-o-projeto)
- [Contribuição](#contribuição)

## Descrição do Projeto

O objetivo deste projeto é criar uma interface visual onde os usuários possam escolher entre diversos personagens dos X-Men. Ao selecionar um personagem, a página exibe uma imagem ampliada do personagem junto com informações detalhadas sobre suas habilidades, nome e descrição. A interação é dinâmica e a seleção de personagem é destacada visualmente.

### Funcionalidades:
- **Seleção de Personagem**: O usuário pode clicar em um dos personagens listados para visualizar mais informações sobre ele.
- **Exibição de Informações**: Após a seleção, o nome e a descrição do personagem são exibidos na seção lateral.
- **Responsividade**: O layout da página se adapta a diferentes resoluções de tela para garantir uma boa experiência em dispositivos móveis, tablets e desktops.

## Tecnologias Utilizadas

- **HTML**: Estrutura básica da página.
- **CSS**: Estilização da página, incluindo responsividade.
  - **Reset CSS**: Normalização de margens, preenchimentos e box-sizing.
  - **Responsivo CSS**: Media queries para adaptar o layout para diferentes dispositivos.
  - **Estilo CSS**: Estilização geral da página com foco em tipografia, cores e layout.
- **JavaScript**: Futuro código para interatividade (não implementado no momento).
- **Imagens**: Imagens dos personagens, incluindo uma logo para a página.

## Estrutura de Diretórios

```plaintext
main/
│
├── src/
│   ├── css/
│   │   ├── reset.css          # Estilos de reset
│   │   ├── responsivo.css     # Estilos para responsividade
│   │   └── style.css          # Estilos principais da página
│   ├── html/
│   │   └── index.html         # Arquivo principal HTML
│   ├── js/
│   │   └── script.js          # Arquivo JavaScript (não implementado)
│   └── imagens/
│       ├── logo.svg           # Logo da página
│       ├── card-ciclope.jpg   # Imagem do personagem Ciclope
│       ├── card-jean-grey.jpg # Imagem do personagem Jean Grey
│       ├── card-lince-negra.jpg # Imagem do personagem Lince Negra
│       ├── card-magneto.jpg   # Imagem do personagem Magneto
│       ├── card-noturno.jpg   # Imagem do personagem Noturno
│       ├── card-tempestade.jpg # Imagem do personagem Tempestade
│       ├── card-vampira.jpg   # Imagem do personagem Vampira
│       └── card-wolverine.jpg # Imagem do personagem Wolverine
```

## Como Rodar o Projeto

1. Clone este repositório para o seu ambiente local:
   ```bash
   git clone https://github.com/seu-usuario/projeto-xmen.git
   ```

2. Acesse o diretório do projeto:
   ```bash
   cd projeto-xmen
   ```

3. Abra o arquivo `index.html` em seu navegador para visualizar a página.

## Contribuição

1. Faça o fork do repositório.
2. Crie uma branch para a sua modificação (`git checkout -b minha-modificacao`).
3. Faça as alterações necessárias e comite-as (`git commit -am 'Adicionando nova funcionalidade'`).
4. Envie a branch para o seu repositório remoto (`git push origin minha-modificacao`).
5. Abra um pull request para a branch principal.

---
