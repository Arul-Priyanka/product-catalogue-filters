

# Product Catalog with filters

## Overview

A **static HTML/CSS/JS product catalog** website built using **Tailwind CSS**.
It displays products in a 3-column responsive grid and includes interactive filters for easy browsing.

### Key Features

* 20 sample products with **icons** instead of images.
* Sidebar with dynamic filters:

  * **Dropdown filter** by main category (Electronics, Kitchen, Accessories, Furniture, etc.)
  * **Category & type buttons** for quick selection
  * **Price range** filter (min & max)
  * **Search bar** and **sort options**
* Responsive layout (3-column on large screens, stacked on mobile)
* Products dynamically grouped by category
* Uses `id` and `data-` attributes for filtering
* Color theme: **Teal & Navy Blue**

---

## Folder Structure

```
project-root/
│
├─ index.html        # Main HTML file
├─ style.css         # Optional additional styles
├─ script.js         # JavaScript logic (filtering, rendering)
└─ README.md         # This file
```

---

## How to Run

1. Clone or download the repository.
2. Open `index.html` in a web browser (Chrome, Firefox, Edge, etc.).
3. No server needed — fully static website.

---

## Features & Usage

### Filters

* **Category Dropdown**: Select a main category to filter products using `id` and `data-category` attributes.
* **Category & Type Buttons**: Toggle active filters by clicking.
* **Price Range**: Set min & max price and click Apply.
* **Search**: Filter products by keywords in title, category, or type.
* **Sort**: Options to sort by default, price low → high, or price high → low.
* **Clear Filters**: Resets all filters including dropdown.

### Product Grid

* Products are **dynamically grouped** by category.
* Each product has a unique `id` and a `data-category` attribute.
* Grid updates automatically when filters change.

---

## Customization

* Add or remove products in the `products` array in `script.js`.
* Update icon, title, category, type, price, or rating.
* Modify colors or spacing using **Tailwind CSS** classes.
* Add more filter types following the existing pattern.

---

## Technologies

* HTML5
* CSS3 with Tailwind CSS v3+
* JavaScript ES6
* Fully static — no backend required

---

## Notes

* Icons are used instead of images for product visuals.
* Filtering system leverages `id` and `data-` attributes for dynamic updates.
* Fully responsive and mobile-friendly.


## License

This project is open-source and free to use under the **MIT License**.


If you want, I can also **enhance it further with emojis, badges, and a professional GitHub README style** that stands out visually. Do you want me to do that next?
