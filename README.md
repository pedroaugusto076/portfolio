# 💼 Portfólio Pessoal – Pedro Augusto

## 📌 Visão Geral

Este projeto consiste no desenvolvimento do meu **portfólio profissional responsivo**, criado com foco em:

* Apresentação de habilidades técnicas
* Exibição de projetos
* Identidade visual moderna
* Experiência de navegação fluida
* Responsividade para múltiplos dispositivos

O objetivo principal foi construir uma aplicação web leve, interativa e visualmente profissional utilizando apenas tecnologias front-end puras.

---

# 🚀 Tecnologias Utilizadas

## 🔹 Front-End

* **HTML5** – Estrutura semântica da aplicação
* **CSS3** – Estilização moderna e responsiva
* **JavaScript (ES6+)** – Interatividade e manipulação do DOM

## 🔹 Recursos e Bibliotecas

* **Google Fonts (Poppins)** – Tipografia personalizada
* **Boxicons** – Ícones vetoriais
* **ScrollReveal.js** – Animações baseadas em scroll
* **Media Queries** – Responsividade avançada
* **CSS Variables (Custom Properties)** – Organização e padronização visual

---

# 🎨 Principais Funcionalidades Implementadas

## ✅ Layout Responsivo

* Estrutura adaptável para mobile, tablet e desktop
* Design Mobile-First
* Breakpoints otimizados (320px, 576px, 768px, 992px)

---

## ✅ Menu Responsivo (Hambúrguer)

* Toggle dinâmico via JavaScript
* Classe `.show` controlada por evento de clique
* Fechamento automático ao selecionar link

```javascript
nav.classList.toggle('show')
```

---

## ✅ Scroll Spy (Link Ativo Dinâmico)

O menu identifica automaticamente qual seção está visível na tela, aplicando a classe `active-link`.

```javascript
if(scrollDown > sectionTop && scrollDown <= sectionTop + sectionHeight){
    sectionsClass.classList.add('active-link')
}
```

Isso melhora a experiência do usuário e navegação.

---

## ✅ Animações com ScrollReveal

Elementos aparecem suavemente conforme o usuário navega pela página.

```javascript
const sr = ScrollReveal({
    origin: 'top',
    distance: '60px',
    duration: 2000,
    delay: 200
});
```

---

## ✅ Sistema de Variáveis CSS

Uso de Custom Properties para padronização visual:

```css
:root {
  --first-color: hsl(224, 89%, 60%);
  --second-color: hsl(224, 56%, 12%);
  --body-font: "Poppins", sans-serif;
}
```

Isso facilita manutenção e escalabilidade do design.

---

# 🎯 Seções do Portfólio

* 🏠 Home – Apresentação pessoal
* 👤 Sobre – Descrição profissional
* 🛠️ Habilidades – Skills com barras visuais
* 💼 Trabalhos – Galeria de projetos
* 📩 Contato – Formulário de contato

---

# 📈 Conceitos Aplicados

* Estruturação semântica HTML
* Organização visual com CSS Grid
* Uso de Flexbox
* Controle de estados via JavaScript
* Manipulação de classes dinamicamente
* Design responsivo moderno
* Experiência do usuário (UX)
* Hierarquia visual
* Performance (site leve, sem frameworks pesados)

---

# 🔧 Como Executar o Projeto

1️⃣ Clone o repositório:

```
git clone https://github.com/seuusuario/portfolio.git
```

2️⃣ Abra o arquivo:

```
index.html
```

Nenhuma instalação adicional é necessária.

---

# 💡 Objetivo Profissional

Este projeto foi desenvolvido com foco em:

* Demonstrar domínio de front-end puro
* Mostrar organização de código
* Aplicar boas práticas de estruturação
* Criar presença digital profissional

---

© Pedro Augusto – Portfólio Profissional
