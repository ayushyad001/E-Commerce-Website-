# MiniShop — Single-File E-Commerce Website (HTML + CSS + JavaScript)

MiniShop is a **single-file** e-commerce website built using only **HTML, CSS, and JavaScript**.  
It includes a modern UI, product listing, search/filter/sort, product details modal, cart drawer, checkout demo, order history, and a simple **Admin Panel** to add/edit/delete products.

> ✅ No backend required (data is stored in your browser using `localStorage`)

---

## Features

### Customer Side
- Product listing (grid)
- Search products
- Filter by category
- Sort products (Featured, Price, Name)
- Product details popup (Modal)
- Cart drawer
  - Add to cart
  - Increase / decrease quantity
  - Remove item
- Checkout (demo)
- Orders history (saved in `localStorage`)

### Admin Panel (Demo)
- Admin login (demo password)
- Add product
- Edit product
- Delete product
- Reset demo products

> ⚠️ Admin security is only **front-end demo**. Real projects should use a backend authentication system.

---

## Project Files

- `index.html` → Full project (HTML + CSS + JS in one file)
- `README.md` → This documentation file

---

## How to Run

1. Create a folder, for example: `minishop`
2. Save the website code as: `index.html`
3. Save this documentation as: `README.md`
4. Open `index.html` in your browser (Chrome/Edge/Firefox)

✅ Done! Your store will run offline (except product images which use online URLs).

---

## Admin Login

- Click **🛠 Admin** button
- Enter password:  
  **`admin123`**

Then you can add/edit/delete products.

---

## Data Storage

This project uses browser `localStorage` for:
- Products
- Cart
- Orders
- Admin login state

If something breaks (due to old saved data), reset storage:

### Reset Local Storage (Fix Errors)
Open Developer Console (F12 → Console) and run:

```js
localStorage.clear();
location.reload();
