# Multipage HTML Project

A modular, responsive multipage website structure using **HTML5** and **CSS3**. The project includes separate partials (sections) like header, hero, about, catalog, and more — making it easy to maintain and scale.

---

## ✨ Features

- Clean and modular HTML5 structure
- Responsive design with [modern-normalize](https://github.com/sindresorhus/modern-normalize)
- Partial file loading (`<load = "partials/...">`) for better code organization *(used with build tools like Parcel, Gulp, or Vite)*
- Sections included:
  - Header
  - Hero
  - About Us
  - Catalog
  - Advertisement
  - Sale
  - Reviews
  - Contact Us
  - Footer

---

## 📁 Project Structure

project/
├── index.html
├── css/
│ └── main.css
├── partials/
│ ├── header.html
│ ├── hero.html
│ ├── about-us.html
│ ├── catalog.html
│ ├── advertisement.html
│ ├── sale.html
│ ├── reviews.html
│ ├── contact-us.html
│ └── footer.html


---

## 🚀 How to Use

> This project uses the `<load ... />` syntax, which requires a bundler or template engine that supports partial imports (e.g. [Parcel](https://parceljs.org/), [Vite](https://vitejs.dev/), or custom Gulp setups).

1. Clone or download the repository.
2. Make sure your development environment supports partial HTML loading.
3. Open the project with a bundler that processes partials.
4. Open `index.html` in the browser (via development server).

---

## 📌 Technologies Used

- **HTML5** – semantic markup
- **CSS3** – styling and layout
- **Modern Normalize** – consistent cross-browser baseline
- **Modular HTML structure** – using partials for maintainability

---

## 🛠 Requirements (If Using Build Tools)

- Node.js and npm
- A bundler or HTML preprocessor that supports `load` or similar directives (e.g., Parcel, Pug, EJS, or custom pipelines)

---

## 📄 License

This project is for learning and demo purposes. No license is attached by default.
