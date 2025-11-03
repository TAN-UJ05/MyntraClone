# 🛍️ Myntra Clone - E-Commerce Store

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript)


A **responsive Myntra-like e-commerce website clone** built with **HTML, CSS, and JavaScript**.  
Users can browse products, filter by category, search, add items to a cart, and view totals dynamically.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🏷️ Product Categories | Men, Women, Kids, and All Products |
| 🔎 Search | Real-time product search by name |
| 🛒 Shopping Cart | Add/remove items, dynamic cart count, total price |
| 🎨 Responsive Design | Works on mobile, tablet, and desktop screens |
| 💻 Lazy Loading | Images load efficiently for better performance |
| 🧩 Interactive UI | Hover effects, buttons, modals for better UX |

---

## 🖥️ Project Structure

```
index.html       -> Main HTML file
style.css        -> Embedded CSS (can separate if needed)
script.js        -> Embedded JS (can separate if needed)
assets/          -> Product images (optional, using online URLs in this version)
```

---

## 🛠️ How It Works

### Categories Filter

Click buttons to filter products:

- **All** → Shows all products  
- **Men/Women/Kids** → Shows category-specific products

### Search

Type in the search bar and press **Search** to filter products by name.

### Add to Cart

Click **Add to Cart** on a product:

- Cart count updates dynamically  
- Click the cart icon 🛒 to view cart contents  
- Remove items if needed  
- Total price updates automatically

---

## 🏷️ Code Overview

**HTML Structure**

- `header` → Logo, navigation links, search bar  
- `div.categories` → Category filter buttons  
- `div.products` → Grid of products generated via JS  
- `div.cart` → Fixed cart icon with item count  
- `div#cart-modal` → Modal showing cart items  
- `footer` → Footer content  

**JavaScript Functions**

- `displayProducts(products)` → Renders product cards dynamically  
- `filterCategory(category)` → Filters products by category  
- `searchProducts()` → Filters products by search query  
- `addToCart(productId)` → Adds product to cart or increases quantity  
- `updateCartCount()` → Updates cart item count badge  
- `viewCart()` → Opens cart modal  
- `removeFromCart(productId)` → Removes product from cart  
- `closeCart()` → Closes cart modal

---

## 📊 Sample Product Object

```javascript
{
    id: 1,
    name: "Men's T-Shirt",
    price: 1299,
    category: "men",
    imageUrl: "https://static.zara.net/assets/public/1608/8156/fcdb430ab03e/cadb8dea5c46/00962379251-a1/00962379251-a1.jpg?ts=1760623929791&w=473"
}
```

---

## ⚡ How to Run

1. Clone the repository:

```bash
git clone https://github.com/YourGitHubUsername/myntra-clone.git
```

2. Open `index.html` in a browser  
3. Interact with products, search, and cart  

> No server required; fully client-side.

---

## 🚀 Future Improvements

- Add **localStorage** to persist cart data  
- Implement **login/signup** for personalized cart  
- Add **payment gateway integration**  
- Enhance design with **animations & transitions**  
- Implement **pagination** for large product lists  

---

## 📫 Contact

- **GitHub:** https://github.com/TAN-UJ05 
- **Email:** tanujjoshi669@gmail.com  

---

## ⚖️ License
MIT License  
Made with ❤️ using HTML, CSS, and JavaScript
