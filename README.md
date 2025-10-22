
<p align="center">
  <img src="./img/recipe-app.gif" alt="React Recipe App" width="800"/>
</p>

<h1 align="center">📌 React Recipe App  </h1>

<div align="center">
  <h3>
    <a href="https://recipe-app-umitdev.netlify.app/">
      🖥️ Demo
    </a>
     | 
    <a href="https://github.com/Umit8098/React-Project-Recipe-App.git">
      📂 Repository
    </a>
  </h3>
</div>

## Table of Contents

- [Table of Contents](#table-of-contents)
- [✨ Overview](#-overview)
- [📖 Description](#-description)
- [🚀 Features](#-features)
- [🗂️ Project Skeleton](#️-project-skeleton)
- [🛠️ Built With](#️-built-with)
- [⚡ How To Use](#-how-to-use)
- [📌 About This Project](#-about-this-project)
- [🙏 Acknowledgements](#-acknowledgements)
- [📬 Contact](#-contact)

---

## ✨ Overview

<div align="center"> 

  <img src="./img/recipe.png" alt="recipe-app" width="700"/>
  
  --- 
  
  <img src="./img/detail.png" alt="recipe-app" width="700"/> 

  ---

</div>

- React Recipe App, kullanıcıların Edamam API aracılığıyla yemek tariflerini arayabileceği, detaylı besin değerlerini görüntüleyebileceği modern bir tarif uygulamasıdır.
- Kullanıcı girişi (login), özel sayfa koruması (Private Router) ve dinamik yönlendirme özellikleriyle birlikte geliştirilmiştir.

---

## 📖 Description

- Bu proje, React Router, Styled Components ve Axios kullanılarak oluşturulmuş bir tarif arama uygulamasıdır.
- Kullanıcılar arama çubuğuna istedikleri yemeği yazarak Edamam API’sinden veri çekebilir, her tarifin detay sayfasında besin değerlerini ve içeriklerini görüntüleyebilirler.
- Bazı sayfalar (örneğin About ve Detail) yalnızca giriş yaptıktan sonra erişilebilir.

---

## 🚀 Features

- 🌐 API Integration with `https://api.edamam.com/api/recipes/v2`
- ⚛️ React Router v6 ile client-side routing
- 🔐 PrivateRouter ile korumalı sayfalar
- 🌐 Edamam Recipe Search API entegrasyonu
- 💅 Styled Components ile modern, responsive tasarım
- 💾 Session Storage ile kullanıcı oturum yönetimi
- 📱 Mobil uyumlu navbar ve hamburger menü
- 🚀 Deployed on GitHub Pages
- 🚀 Netlify üzerinde canlı deploy
  
---

## 🗂️ Project Skeleton

```
src/
 │
 |----readme.md   
 │
 ├─ assets/
 │     ├─ coding.svg
 │     ├─ diet.svg
 │     └─ default-image.png
 │
 ├─ components/
 │   ├─ cards/
 │   │    ├─ Cards.jsx
 │   │    └─ Cards.style.jsx
 │   │
 │   ├─ globalStyles/
 │   │    ├─ Flex.jsx
 │   │    ├─ Global.styles.jsx
 │   │    └─ Theme.js
 │   │
 │   ├─ header/
 │   │    ├─ Header.jsx
 │   │    └─ Header.style.jsx
 │   │
 │   └─ nav/
 │        ├─ Navbar.jsx
 │        └─ Navbar.style.jsx
 │
 ├─ pages/
 │   ├─ about/
 │   │    ├─ About.jsx
 │   │    └─ About.style.jsx
 │   │
 │   ├─ detail/
 │   │    ├─ Detail.jsx
 │   │    └─ Detail.jsx
 │   │
 │   ├─ home/
 │   │    ├─ Home.jsx
 │   │    └─ Home.style.jsx
 │   │
 │   ├─ login/
 │   │    ├─ Login.jsx
 │   │    └─ Login.style.jsx
 │   │
 │   └─ register/
 │        └─ Registerjsx
 │
 ├─ router/
 │    ├─ AppRouter.jsx
 │    └─ PrivateRouter.jsx
 │   
 ├─ App.js
 └─ index.js
```

---

## 🛠️ Built With

- [⚛️ React](https://react.dev/)  
- [🧭 React Router v6](https://reactrouter.com/) 
- [💅 Styled Components](https://styled-components.com/) 
- [📦 Axios](https://axios-http.com/) 
- [🍴 Edamam Recipe API](https://developer.edamam.com/edamam-recipe-api) 
- [GitHub Pages](https://pages.github.com/) 
- [Netlify](https://www.netlify.com/) 

---

## ⚡ How To Use

To clone and run this application, you'll need [Git](https://git-scm.com/), [Node.js](https://nodejs.org/), and a package manager (`yarn` or `npm`) installed on your computer.

```bash
# Clone this repository
$ git clone https://github.com/Umit8098/React-Project-Recipe-App.git

# Navigate into the project folder
$ cd React-Project-Recipe-App

# Install dependencies
$ yarn  
$ yarn start

# or using npm
$ npm install
$ npm start
```
- Then open http://localhost:3000 to view it in your browser.

---

## 📌 About This Project

🔸 Bu proje, Clarusway Frontend Developer eğitimi kapsamında React Router ve API kullanımı konularını pekiştirmek amacıyla geliştirilmiştir.
🔸 Amaç, kullanıcı giriş kontrolü (PrivateRoute), API entegrasyonu ve responsive tasarımın aynı projede nasıl kullanılabileceğini göstermektir.
🔸 Proje Netlify üzerinde deploy edilmiştir.

---

## 🙏 Acknowledgements

- [🎓Clarusway](https://clarusway.com/) – for the training resources
- [📘React Documentation](https://react.dev/)
- [🧭React Router Docs](https://reactrouter.com/en/main/start/overview)
- [💅 Styled Components](https://styled-components.com/)
- [🍴 Edamam Recipe API](https://developer.edamam.com/edamam-recipe-api) 


---

## 📬 Contact

<!-- - Website [your-website.com](https://{your-web-site-link}) -->
- GitHub [@Umit8098](https://github.com/Umit8098)

- Linkedin [@umit-arat](https://linkedin.com/in/umit-arat/)
<!-- - Twitter [@your-twitter](https://{twitter.com/your-username}) -->
