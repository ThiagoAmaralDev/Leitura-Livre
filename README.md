
# 📚 Biblioteca Digital Responsiva

> Uma interface de biblioteca digital moderna e fluida, construída do zero para desafiar os limites do CSS puro. Sem frameworks. Sem atalhos.

<img width="968" height="628" alt="image" src="https://github.com/user-attachments/assets/1f3e32ba-8515-4d08-a75c-06ee5eabe68d" >

---

## 🎯 O Desafio

O maior objetivo deste projeto foi criar uma experiência de usuário (UX) consistente, elegante e de alta performance em qualquer tamanho de tela. O foco principal foi dominar o design responsivo utilizando exclusivamente recursos nativos da web, provando que é possível atingir fluidez e adaptabilidade sem inflar o projeto com frameworks pesados (como Tailwind ou Bootstrap).

---

## ✨ Principais Funcionalidades

* **📱 Menu Mobile Adaptado:** Navegação que se transforma inteligentemente de uma barra lateral/topo em um menu hambúrguer compacto e funcional.
* **🔄 Navegação Fluida:** Transições suaves entre as seções da biblioteca, garantindo que o usuário não sinta quebras na experiência.
* **📐 Grid & Flexbox Power:** Layout totalmente maleável que se reorganiza perfeitamente desde telas de smartphones antigos até monitores Ultrawide.
* **⚡ Performance Extrema:** Carregamento instantâneo graças à ausência de dependências externas e scripts desnecessários.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação semântica e acessível.
* **CSS3 (Puro):**
  * *Custom Properties* (Variáveis CSS) para fácil manutenção de cores e espaçamentos.
  * *Flexbox* e *CSS Grid* para o sistema de layout responsivo.
  * *Media Queries* avançadas para a adaptação de quebras de tela.
* **JavaScript (Vanilla):** Apenas o estrito necessário para a manipulação de estado do menu mobile.

---

## 🚀 Como Executar o Projeto

Não há necessidade de instalar dependências complexas (`npm install`). Basta clonar e abrir!

1. Clone o repositório:
```bash
   git clone [https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/seu-usuario/nome-do-repositorio.git)

```

2. Entre na pasta do projeto:

```bash
   cd nome-do-repositorio

```

3. Abra o arquivo `index.html` no seu navegador de preferência ou utilize a extensão **Live Server** no VS Code.

---

## 🧠 Aprendizados e Soluções Técnicas

Durante o desenvolvimento, a maior virada de chave foi arquitetar o CSS de forma modular para que o menu mobile não parecesse uma "gambiarra" sobreposta ao desktop, mas sim uma evolução natural do mesmo código.

A fluidez entre as seções foi resolvida utilizando o poder de `scroll-behavior: smooth` aliado a transições de opacidade (`transition`), mantendo a performance e a taxa de quadros (FPS) elevadas durante a navegação.

---


Feito com ☕ por [Thiago Amaral](https://github.com/ThiagoAmaralDev)

