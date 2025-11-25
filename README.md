# 🚀 FormSpace - Formulário de Confirmação de Presença


> *Uma interface moderna e responsiva para confirmação de presença em eventos exclusivos.*
<img width="1917" height="1057" alt="image" src="https://github.com/user-attachments/assets/12e5f1e7-24e0-4700-b073-1319fa5dec07" />

## 💻 Sobre o Projeto

O **BoostInvite** é uma página de aterrissagem (Landing Page) focada na conversão de convidados para um evento. O projeto consiste em um formulário de RSVP (Répondez S'il Vous Plaît) com um design "Split Screen" (tela dividida): de um lado o formulário funcional e do outro as informações visuais do evento.

O layout foi desenvolvido com uma paleta de cores escura (Dark Mode), utilizando gradientes e elementos flutuantes para criar uma estética premium.

## 🛠️ Tecnologias Utilizadas

O projeto foi construído utilizando as melhores práticas do desenvolvimento Web moderno:

* **HTML5 Semântico**: Estrutura acessível e organizada.
* **CSS3 Moderno**:
    * **CSS Grid & Flexbox**: Para o layout responsivo (`#layout`).
    * **CSS Variables**: Para facilitar a manutenção de cores e fontes (`var(--bg)`, `var(--text-primary)`).
    * **CSS Nesting**: Escrita de CSS mais limpa e hierárquica (ex: `header { ... }` dentro de `main`).
* **Design Responsivo**: Adaptável para diferentes tamanhos de tela.

## 🎨 Layout e Design

O design foi pensado na experiência do usuário (UX):

1.  **Sidebar Informativa**: Gradiente roxo/azul com imagens rotacionadas para dar dinamismo.
2.  **Formulário Clean**: Campos claros com estados de `:focus` e `:hover` para feedback visual.
3.  **Tipografia**: Uso da fonte *Poppins* para garantir legibilidade e modernidade.

## 📂 Estrutura de Pastas

```bash
/
├── assets/
│   └── imgs/          # Imagens do layout
├── modules/
│   └── css/
│       ├── global.css # Variáveis e resets
│       ├── form.css   # Estilização específica do formulário
│       ├── aside.css  # Estilização da barra lateral decorativa
│       └── index.css  # Arquivo centralizador de estilos
└── index.html         # Estrutura principal
