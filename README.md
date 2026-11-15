# LUXE Fashion Store (Frontend Demo)

## Run
1. Extract the ZIP.
2. Open the `LUXE-FASHION-STORE` folder in VS Code.
3. Open `index.html` with Live Server, or double-click it to open in a browser.
4. Use **Create an account** to sign up, then sign in on another visit if needed.

## Features
- Signup, login and logout demo
- Product listing, search, category filter and sorting
- Wishlist add/remove
- Product add, edit and delete in Product Studio (`admin.html`)
- Responsive minimal-luxury design
- Browser LocalStorage persistence

## Important
This is a frontend-only educational demo. User passwords are stored in browser LocalStorage in plain text, so do not use real passwords or real personal information. There is no secure authentication, server, PHP or MySQL. Product Studio is not protected by an admin role; anyone using the browser can open it. Product and wishlist data are local to the current browser. Product photos and Google Fonts need an internet connection.

## Files
- `index.html` — storefront
- `login.html`, `signup.html` — demo authentication pages
- `wishlist.html` — saved products
- `admin.html` — product CRUD interface
- `css/style.css` — design and responsive styling
- `js/` — app, auth, products, wishlist and admin logic
