<p align="center">
  <img src="https://dummyimage.com/1200x250/0d0d0d/ff7ad1&text=AAG+Sele%C3%A7%C3%B5es+%7C+Mobile+App+Prototype" width="100%" style="border-radius: 12px;" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-em%20desenvolvimento-ff7ad1?style=for-the-badge&labelColor=111" />
  <img src="https://img.shields.io/badge/feito%20com-HTML%20%7C%20Tailwind%20%7C%20JS-7d5fff?style=for-the-badge&labelColor=111" />
  <img src="https://img.shields.io/badge/mobile-first-1E90FF?style=for-the-badge&labelColor=111" />
</p>

---

# 📱 AAG Seleções — App Oficial  
Interface mobile-first para organização de estudos, editais, provas e desempenho.

<p align="center">
  <img src="https://i.imgur.com/OK7mZ8b.gif" width="260px" style="border-radius: 20px;" />
  <br>
  <em>Preview ilustrativo da navegação mobile</em>
</p>

---

## 🌟 Visão Geral  
O **AAG Seleções** é um protótipo funcional de aplicação mobile usando apenas **HTML + TailwindCSS + JavaScript**, com foco em:

- navegação fluida entre telas  
- identidade visual elegante em rosa e roxo  
- UX intuitivo e limpo  
- layout mobile-first real  

O app simula uma experiência completa — login, dashboard, planner, editais, provas e boletins de desempenho.

---

## 🎨 Tecnologias Utilizadas

- **HTML5**
- **TailwindCSS (via CDN)**
- **JavaScript Vanilla**
- **Google Fonts (Montserrat + Playfair Display)**
- **Lucide Icons**
- **Glassmorphism**
- **Dark Mode automático**

---

## 🚀 Funcionalidades

### 🔐 Login  
- Entrada com CPF e senha  
- Botão gov.br  
- Layout moderno + microanimações  

### 🏠 Dashboard  
- Saudação personalizada  
- Alerta de prazos  
- Cards informativos e atalhos  
- Barra de busca  

### 🗓️ Planner  
- Agenda semanal  
- Lista de tarefas  
- Guias de estudo  

### 📄 Editais  
- Editais abertos  
- Resumo das bancas  

### 📝 Provas  
- Provas agendadas  
- Resultados disponíveis  

### 🏆 Resultado da Prova  
- Classificação final  
- Barras animadas  
- Painel de notas  

---

## 🧭 Navegação entre Telas  

```js
function nav(screen) {
    document.querySelectorAll(".app-screen").forEach(s => s.classList.add("hide"));
    document.querySelector(`#screen-${screen}`).classList.remove("hide");
}
