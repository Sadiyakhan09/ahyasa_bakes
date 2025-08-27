# 🍰 Ahyasa Bakes Website

A responsive bakery website for **Ahyasa Bakes**, built with **Tailwind CSS** and **vanilla JavaScript**.
The site includes product showcase, cart functionality, enquiry form, and QR-based payment modal.

---

## 🚀 Features

* 🎨 Responsive UI with **Tailwind CSS**
* 🛒 **Cart system** (open/close drawer)
* 📱 Mobile navigation with drawer menu
* 💳 QR Code modal for payments
* 📝 Enquiry form with validation
* 🎯 Floating badge and card for quick access
* ⚡ JavaScript event handling with safe checks (no crashes if elements are missing)

---

## 🛠️ Tech Stack

* **HTML5**
* **Tailwind CSS** (installed via CLI/PostCSS, not CDN)
* **Vanilla JavaScript**

---

## 📂 Project Structure

```
ahyasa_bakes/
│── index.html        # Main entry point
│── script.js         # JavaScript logic (cart, QR, navigation, etc.)
│── style.css         # Tailwind input file
│── dist/
│    └── style.css    # Compiled Tailwind CSS (production build)
│── tailwind.config.js # Tailwind configuration
│── package.json      # NPM dependencies
```

---

## ⚙️ Setup & Installation

### 1️⃣ Clone the repo

```bash
git clone https://github.com/yourusername/ahyasa_bakes.git
cd ahyasa_bakes
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Run Tailwind in development

```bash
npx tailwindcss -i ./style.css -o ./dist/style.css --watch
```

### 4️⃣ Build for production

```bash
npx tailwindcss -i ./style.css -o ./dist/style.css --minify
```

---

## 📖 Usage

* Open `index.html` in your browser.
* Use **cart button** to open/close the cart drawer.
* Use **QR button** to show payment QR modal.
* Try **mobile navigation** to test responsive drawer.
* Fill out and submit the **enquiry form**.

---

## 🔒 Notes

* The script is wrapped in `DOMContentLoaded` and uses safe event bindings → prevents `null.addEventListener` errors.
* Tailwind CDN (`cdn.tailwindcss.com`) is removed for production. Use the compiled `dist/style.css` instead.

---

## 👨‍🍳 Author

Built with ❤️ by **BiBi_Sadiya** for Ahyasa Bakes.
