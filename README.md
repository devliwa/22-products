# 22 Products Project

A JavaScript project that displays a list of products with the ability to search and filter them.  
This project is great for practicing DOM manipulation, working with arrays/objects, and building dynamic user interfaces.

---

## Features
- Display products with images, names, and prices  
- Search products dynamically using text input  
- Filter products by category  
- Responsive design for different screen sizes  

---

## Built With
- **HTML5** for structure  
- **CSS3** for styling  
- **JavaScript (ES6)** for interactivity  

---

## Demo Preview
[22 Products Project](https://devliwa.github.io/22-products/index.html) 
<img width="1279" height="636" alt="Screenshot 2025-09-08 at 12 20 52 PM" src="https://github.com/user-attachments/assets/ee7b538d-eea4-4389-bfc8-fbc6142d78b6" />


---

## What I Learned
- Looping through arrays of objects and rendering content to the DOM  
- Implementing search and filter features in JavaScript  
- Building reusable UI components for product listings  

#### Structure (HTML)

- section.products

  - div.title
    - h2(products)
    - div.title-underline
  - div.products-center
    - div.products-container
      - a.single-product href="product.html"
        - img.single-product-img.img
        - footer
          - h5.name (product title)
          - span.price($9.99)

- create product.html
- basic structure

#### Loading and Error

- (CSS Loading Spinner)[https://youtu.be/DqqZEpctZ8w]
- in .products-center
- div.loading
- p.error

#### API Docs

- (Course API)[https://www.course-api.com/]

- (Products)[https://www.course-api.com/javascript-store-products]

- (Single Product)[https://www.course-api.com/javascript-store-single-product?id=rec43w3ipXvP28vog]

#### Fetch Products

- select .products-center
- fetch products
- log result
- try/catch

#### Loading and Error

- add loading while fetching
- add error in catch

#### Display Products - Setup

- return data from fetchProducts
- create displayProducts(list)
- create start()
- invoke fetchProducts and displayProducts in start
- invoke start

#### Display Products - Complete

- iterate over list
- pull out all the values
- set productsDOM equal to result

#### Single Product

- link styles.css
- a.btn.home-link(back home)
- section.product
- div.product-wrapper
  - img.img
  - div.product-info
    - h3 (title)
    - h5 (company)
    - span (price)
    - div.colors
      - span.product-color
    - p (lorem text)
    - button.btn(add to cart)

#### product.js setup

- create product.js
- link product.html
- select .product
- get single product url
- setup fetchProduct(),displayProduct(),start()

#### Loading, Error, Fetch Single Product

- fetch single product
- setup loading and error
- make id dynamic
- new URLSearchParams
- window.location.search
- get(keyName)

#### Display Single Product

#### Display Colors

- iterate over colors array
- return span with dynamic color value
