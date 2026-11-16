# ClovAid – Charity Book Store

A responsive one-page web shop for a community book donation service. Visitors browse second-hand books, add them to a cart, and check out with a donation. The money collected goes to charity.

I first built it as a project for the Web Technologies course at IMC University of Applied Sciences Krems and keep improving it here.

## Features

- **Book catalogue** with 16 titles, prices and cover images
- **Shopping cart**: add books, change quantities, remove items, or clear the cart
- **Automatic totals**: subtotal, a 10% discount on orders of 3 or more books, tax, and the final total
- **Checkout form** with built-in validation for name, address, phone and email
- **Order confirmation** that shows the buyer's details and an order summary
- **Responsive layout** that works on phones, tablets and desktops

## Built with

- HTML5 and CSS3
- JavaScript, with no frameworks
- Bootstrap 5 for the layout, collapsible panels and form styling

## Run it locally

No installation is needed.

1. Clone or download this repository.
2. Open `index.html` in your browser.

## Project structure

```
index.html      – page layout: catalogue, cart, checkout and confirmation
css/style.css   – custom styling on top of Bootstrap
js/scripts.js   – product list, cart logic, totals, checkout and confirmation
img/            – book cover images
```

## What I learned

- Managing application state, the cart, in plain JavaScript
- Updating the page (DOM) dynamically when the user changes something
- Validating forms on the client side
- Building responsive layouts with Bootstrap's grid and components

## Ideas for next steps

- Save the cart in `localStorage` so it survives a page reload
- Put the tax and discount rules in one place so every part of the page uses the same values
- Add search and filtering by genre or price
- Connect to a small backend (Node.js with a database) to store orders
