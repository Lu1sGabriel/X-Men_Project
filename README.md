Claro, adicionei mais detalhes ao README e removi a seção de licença conforme solicitado. Veja abaixo a versão mais completa:

# Projeto X-Men

Este projeto consiste em uma página web interativa para selecionar personagens do universo X-Men. O usuário pode visualizar informações detalhadas sobre cada personagem ao clicar em sua imagem. A página foi desenvolvida com HTML, CSS (incluindo estilos responsivos) e JavaScript, proporcionando uma interface agradável e funcional, adaptada para diferentes dispositivos.

## Sumário

- [Descrição do Projeto](#descrição-do-projeto)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Estrutura de Diretórios](#estrutura-de-diretórios)
- [Como Rodar o Projeto](#como-rodar-o-projeto)
- [Funcionalidades Implementadas](#funcionalidades-implementadas)
- [Contribuição](#contribuição)

## Descrição do Projeto

O **Projeto X-Men** é uma página interativa onde os usuários podem selecionar e visualizar detalhes de diferentes personagens dos X-Men. O layout foi projetado para ser simples e direto, com uma navegação fácil, permitindo aos usuários explorar informações como nome, descrição e imagem ampliada de cada herói ou vilão.

Quando o usuário clica sobre qualquer personagem na lista, ele é destacado visualmente, e as informações do personagem selecionado são exibidas na seção lateral. A escolha do personagem é realizada de forma dinâmica, permitindo uma experiência de usuário fluida.

### Objetivos do Projeto:
- **Interface interativa**: Permitir a seleção de personagens e a exibição de informações em tempo real.
- **Responsividade**: Garantir que a página funcione bem em diferentes dispositivos, como desktops, tablets e smartphones.
- **Estilo agradável**: Utilização de imagens e tipografia para criar uma aparência atraente e coerente com a temática dos X-Men.

## Tecnologias Utilizadas

- **HTML**: Utilizado para estruturar o conteúdo da página, criando os elementos básicos como imagens, listas e textos.
- **CSS**: Estilização da página e criação de um layout responsivo para garantir uma boa experiência em qualquer dispositivo.
  - **Reset CSS**: Normaliza o comportamento dos elementos para eliminar discrepâncias entre navegadores.
  - **Responsivo CSS**: Media queries são utilizadas para ajustar o layout em telas menores, como smartphones e tablets.
  - **Estilos Gerais**: Definidos para criar um visual consistente com o tema e garantir que o design seja limpo e legível.
- **JavaScript**: Embora não esteja implementado no momento, o código JavaScript será usado para manipular dinamicamente a seleção de personagens e suas descrições.
- **Imagens**: Imagens dos personagens X-Men, incluindo uma logo para representar o projeto e várias imagens dos personagens a serem exibidas na interface.

## Estrutura de Diretórios

A estrutura de diretórios do projeto está organizada da seguinte forma:

```plaintext
main/
│
├── src/
│   ├── css/
│   │   ├── reset.css          # Estilos de reset para normalização de margens e preenchimentos
│   │   ├── responsivo.css     # Estilos para responsividade em dispositivos móveis e tablets
│   │   └── style.css          # Estilos principais da página, incluindo cores, fontes e layout
│   ├── html/
│   │   └── index.html         # Arquivo principal HTML que contém a estrutura da página
│   ├── js/
│   │   └── script.js          # Arquivo JavaScript (não implementado, futuro código para interatividade)
│   └── imagens/
│       ├── logo.svg           # Logo da página, exibida no cabeçalho
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

Para rodar este projeto em seu ambiente local, siga os passos abaixo:

1. **Clone o repositório**:
   Se você ainda não possui o repositório, clone-o para sua máquina local com o seguinte comando:
   ```bash
   git clone https://github.com/seu-usuario/projeto-xmen.git
   ```

2. **Acesse o diretório do projeto**:
   Navegue até a pasta do projeto utilizando o terminal:
   ```bash
   cd projeto-xmen
   ```

3. **Abra o arquivo HTML no navegador**:
   Você pode simplesmente abrir o arquivo `index.html` no seu navegador preferido. Não há necessidade de servidores ou configurações adicionais, pois este projeto é uma página estática.

4. **Verifique o funcionamento**:
   O layout deve se ajustar conforme o tamanho da tela. Teste em diferentes dispositivos para garantir que a responsividade esteja funcionando corretamente.

## Funcionalidades Implementadas

- **Seleção de Personagens**: O usuário pode clicar nas imagens dos personagens para selecioná-los.
- **Exibição de Detalhes**: Ao selecionar um personagem, a imagem ampliada e a descrição do personagem aparecem na seção lateral.
- **Responsividade**: O layout é adaptado automaticamente para diferentes tamanhos de tela, garantindo que a página seja usável em dispositivos móveis e desktops.

### Funcionalidades Futuras:
- **Interatividade via JavaScript**: Implementação de interatividade com JavaScript, como mudar a imagem e a descrição do personagem automaticamente quando um novo personagem for selecionado.
- **Efeitos de Transição**: Adição de animações suaves ao selecionar personagens, tornando a interação mais dinâmica.
- **Inclusão de Mais Personagens**: Adição de mais personagens do universo X-Men para expandir a interação.

## Contribuição

Se você deseja contribuir para este projeto, siga os passos abaixo:

1. **Faça um fork do repositório**:
   Clique em "Fork" no GitHub para criar uma cópia do repositório em sua conta.

2. **Crie uma nova branch**:
   No seu repositório forkado, crie uma nova branch para suas modificações:
   ```bash
   git checkout -b minha-modificacao
   ```

3. **Faça as alterações desejadas**:
   Edite os arquivos conforme necessário. Lembre-se de que este projeto utiliza HTML, CSS e JavaScript.

4. **Faça commit das suas alterações**:
   Depois de realizar as alterações, faça commit delas:
   ```bash
   git commit -am 'Adicionando nova funcionalidade'
   ```

5. **Envie a branch para o seu repositório remoto**:
   ```bash
   git push origin minha-modificacao
   ```

6. **Abra um pull request**:
   Volte para o repositório original e abra um pull request para a branch principal.

---
