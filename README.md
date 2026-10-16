# VUTeats (View to Eat)

A food-ordering web app for a restaurant, similar to Uber Eats. Customers can browse the menu, create an account and log in, place orders, and contact the restaurant.

## Features

- Single-page navigation between the Home, About, Contact and Orders views
- Menu browsing with food images (burgers, pizza, wings, coffee, milkshakes)
- User sign-up and login (`auth.php`)
- Placing orders and viewing them (`orders.php`)
- Contact form that saves customer messages (`contact.php`)

## Built with

- HTML5, CSS3 and JavaScript for the front end
- PHP for the server-side logic
- JSON files in `data/` for storing users, orders and messages
- Font Awesome for icons

## Project structure

```
Vuteats/
├── index.html      # Main page and all views
├── style.css       # Styling
├── script.js       # View switching and front-end logic
├── auth.php        # Login and registration
├── orders.php      # Order handling
├── contact.php     # Contact form handling
├── data/           # JSON data files
├── images/         # Menu and logo images
└── video/          # Demo video
```

## Getting started

**Prerequisite:** PHP 7.4 or newer installed on your computer.

```bash
git clone https://github.com/vhakota/Vuteats.git
cd Vuteats
php -S localhost:8000
```

Then open http://localhost:8000 in your browser.

> The VS Code Live Server extension only serves static files, so it can't run the PHP parts. Use the PHP command above instead.

## Screenshots

[Add 2-3 screenshots here, for example: `![Home page](images/screenshot-home.png)`]

A short demo video is in the `video/` folder.

## My role

the front-end layout, the ordering logic, the login system... the whole project.

## Limitations and future improvements

- This is a learning project, and data is stored in JSON files. The next step would be moving it to a MySQL database.
- Review security before any real use: hash passwords and validate all user input.
- Add online payments and order status tracking.

## Author

**Tshikota Fulufhedzeani**: Information Technology graduate, Vaal University of Technology

- LinkedIn: https://www.linkedin.com/in/fulufhedzeani-tshikota-745633354/
- GitHub: https://github.com/vhakota
