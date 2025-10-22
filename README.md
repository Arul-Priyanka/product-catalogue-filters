Product Catalog — Teal & Navy Theme
Overview
This is a static HTML/CSS/JS product catalog website using Tailwind CSS. The catalog displays a variety of products in a 3-column grid layout and provides several interactive filters to help users quickly find items.
Key features:
    •	20 sample products with icons instead of images.
    •	Sidebar with dynamic filters:
    o	Dropdown filter by main category (e.g., Electronics, Kitchen, Accessories, Furniture).
    o	Filter buttons for product category and product type.
    o	Price range filter (min & max).
    o	Search bar and sort options.
    •	Responsive layout (3-column on large screens, stacked on mobile).
    •	Dynamic grouping of products by category.
    •	Uses id attributes and data attributes to enable dynamic filtering.
    •	Color theme: Teal and Navy Blue.
Folder Structure
project-root/
  │
  ├─ index.html        # Main HTML file
  ├─ style.css         # Optional additional styles
  ├─ script.js         # JavaScript logic (filtering, rendering)
  └─ README.md         # This file
How to Run
1.	Clone or download the repository.
2.	Open index.html in a web browser (Chrome, Firefox, Edge, etc.).
3.	No server is needed — this is a fully static site.
Features & Usage
Filters
•	Category Dropdown: Located in the sidebar. Select a main category to filter products. Uses the products' id and data-category attributes for filtering.
•	Category & Type Buttons: Click to toggle active filters.
•	Price Range: Input min and max prices and click Apply.
•	Search: Type keywords to filter titles, categories, and types.
•	Sort: Sort products by default, price low→high, or price high→low.
•	Clear: Resets all filters including the dropdown.
Product Grid
•	Products are grouped dynamically by category.
•	Each product has a unique id (e.g., prod-1) and a data-category attribute.
•	Grid updates automatically when filters change.
Customization
•	Add/remove products in the products array in script.js.
•	Update icon, title, category, type, price, or rating as needed.
•	Modify colors or spacing via Tailwind CSS utility classes.
•	Add more filter types if needed by following the existing pattern.
Technologies
•	HTML5
•	CSS3 with Tailwind CSS v3+
•	JavaScript ES6
•	No external backend — fully static.
Notes
•	The site uses icons instead of images for product visuals.
•	The filtering system leverages id attributes for product cards and data attributes for categories, ensuring dynamic filtering works seamlessly.
•	The site is mobile-friendly and responsive.
License
This project is open-source and free to use under the MIT License.


# product-catalogue-filters
a product catalogue with filters
