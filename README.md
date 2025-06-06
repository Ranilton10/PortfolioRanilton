# 🌐 Portfólio e Projeto Sinalize

Este repositório contém um site pessoal de portfólio desenvolvido por **Ranilton Araújo da Silva Raposo Júnior**, estudante de Ciências da Computação. O site é composto por duas páginas principais:

- `Portfolio.html`: Apresentação pessoal e profissional.
- `sinalize.html`: Descrição detalhada do projeto educativo **Sinalize**.

## 🔧 Tecnologias Utilizadas

### 1. **HTML**
- Utilizado como estrutura base das páginas.
- Uso semântico de tags como `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`, etc.
- Inclusão de imagens (`<img>`) e links (`<a>`).
- Botões com eventos interativos.

### 2. **CSS**
- Arquivo externo: `css/style.css`.
- Responsável pela formatação visual do site (cores, espaçamento, layout responsivo).
- Uso de classes como `.menu`, `.intro`, `.interesses`, `.projeto`, entre outras.

### 3. **JavaScript**
- Interação com o usuário através de funções simples, diretamente no arquivo HTML ou em `js/script.js`.
- Funções utilizadas:
  - `mostrarMensagem()` – exibe um alerta com uma mensagem de boas-vindas.
  - `mostrarDetalhes()` – alterna a visibilidade de uma seção com mais informações sobre o Projeto Sinalize.


---

## 📄 Descrição das Páginas

### 1. `Portfolio.html`

#### ✅ Conteúdo Apresentado:
- **Cabeçalho de navegação** com links para:
  - Início (esta própria página)
  - Projeto Sinalize (`sinalize.html`)
- **Apresentação pessoal** com nome e formação.
- **Seção de interesses profissionais**, destacando:
  - Programação com Python e JavaScript
  - Interesse em UI/UX e boas práticas
  - Procura por estágios
- **Seção com resumo do Projeto Sinalize**
  - Descrição básica
  - Botão para revelar mais detalhes
  - Imagem ilustrativa do projeto

#### 🔘 Botões e suas funções:

- `Clique aqui`  
  ➤ Mostra um **alerta** com a mensagem:  
  _"Obrigado por visitar meu portfólio!"_

- `Saiba mais sobre o Sinalize`  
  ➤ Exibe (ou esconde) um **bloco oculto** com mais informações sobre o projeto, incluindo:
  - Texto descritivo do objetivo
  - Explicação sobre a mecânica do jogo
  - Imagem do jogo
  - Link para acessar a página detalhada


### 2. 'Sinalize.html'

# 🧠 Projeto Sinalize

Este projeto consiste em uma página web explicativa sobre o **Projeto Sinalize**, uma proposta educativa que une **tecnologia** e **acessibilidade**, estimulando o aprendizado da **Língua Brasileira de Sinais (Libras)** e da **Língua Portuguesa** por meio de um jogo da memória interativo.

---

## 📄 Sobre o Arquivo `sinalize.html`

A página `sinalize.html` é uma página estática que apresenta de forma detalhada o funcionamento do **Projeto Sinalize**.

### ✅ Conteúdo da Página

- **Título principal**: `Projeto Sinalize`
- **Descrição introdutória**: Explica a proposta do projeto, seu foco em acessibilidade e educação inclusiva.
- **Explicação das dinâmicas do jogo** com base nos números sorteados em um dado:
  - **1 ou 2** → A criança precisa associar uma carta em Libras com uma em Português. Se for correto, o LED verde pisca e a criança avança uma casa.
  - **3** → Mesmo processo, mas com dois pares. Se corretos, a criança avança uma casa.
  - **4** → A criança deve representar o gesto de uma carta em Libras. Se acertar, avança uma casa.
  - **5** → Número sortido. Ao cair, a criança avança uma casa sem desafio.
  - **6** → A criança desafia o oponente com uma carta em português. Se o oponente errar na escolha da carta em Libras, a criança avança, senão o oponente avança.
- **Imagem** ilustrativa do jogo (`SinalizeExemplo.png`), localizada na pasta `img/`.
- **Link de navegação** para voltar à página inicial do portfólio (`Portfolio.html`).

---

## 🔘 Botões e Funcionalidades

### `Voltar para o portfólio`
- Este é um link simples (`<a>`), não um botão com script.
- Ao clicar, redireciona o usuário para a página principal do portfólio (`Portfolio.html`), onde está a apresentação pessoal do autor.



