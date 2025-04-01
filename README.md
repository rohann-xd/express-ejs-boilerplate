# Express + EJS Boilerplate

A simple, clean, and ready-to-use boilerplate to kickstart your web development projects using **Express.js** with **EJS** templating. This template is designed for beginners and developers who want a quick setup to serve static files (HTML, CSS, JS) and render dynamic content with EJS.

---

## Features

- **Express.js** for server-side development  
- **EJS** for flexible templating  
- Easy static file handling (CSS, JavaScript, Images)  
- Quick project setup for beginners and experienced developers  
- Modular folder structure for scalability  

---

## Project Structure

```
my-website/
├── public/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── script.js
│   └── index.html
├── views/
│   └── index.ejs
├── node_modules/
├── package.json
├── server.js
└── README.md
```

- **public/** - Contains all static files (CSS, JS, images).  
- **views/** - Holds EJS templates.  
- **server.js** - Express server configuration.  
- **package.json** - Project metadata and dependencies.  

---

## Installation & Usage

### 1. Clone the Repository

```
git clone https://github.com/rohann-xd/express-ejs-boilerplate.git
cd express-ejs-boilerplate
```

### 2. Install Dependencies

```
npm install
```

### 3. Run the Server

```
node server.js
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the website in action.

---

## How to Customize

- **Add New Routes:**  
  Update **server.js** to add new routes for different pages.

- **Dynamic Content with EJS:**  
  Use EJS syntax (`<%= %>` or `<%- %>`) to render dynamic data.

- **Static Assets:**  
  Place images, fonts, or additional CSS/JS files in the **public/** folder.

---

## Contributing

Contributions are welcome!  
- Fork the repository  
- Make your changes  
- Submit a pull request  

---

## License

This project is licensed under the **GNU General Public License v3.0 (GPL-3.0)**. For more information, see [GPL-3.0](https://www.gnu.org/licenses/gpl-3.0.en.html).

---

## Acknowledgments

- [Express.js](https://expressjs.com/) - Fast, unopinionated, minimalist web framework  
- [EJS](https://ejs.co/) - Simple templating language for JavaScript
