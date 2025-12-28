# ShopSphere Frontend
Modern React e-commerce app with product browsing, cart, wishlist, filters, and checkout. Connects to ShopSphere API backend.

## Demo Link
[Live Demo](https://e-commerce-fe-six-lake.vercel.app/)

## Quick Start
git clone https://github.com/Rjesh-Kumar/Shopper-FE.git

cd Shopper-FE

npm install

npm run dev


## Technologies
[](https://github.com/Rjesh-Kumar/Shopper-FE#technologies)
- React 19
- React Router  
- Vite  
- Bootstrap 5  
- Bootstrap Icons  
- React Bootstrap  
- Axios  

## Features
**Home (/):**  
- Landing page with featured products  
- Quick search and navigation  

**Product Listing (/products):**  
- Browse all products with category population  
- Real-time search by name  
- Advanced filters (price range, category, rating, sort)  
- Add to cart/wishlist directly from cards  

**Product Details (/product/:id):**  
- Full product specs (price, discount, sizes, images)  
- Quick add to cart/wishlist  

**Shopping Cart (/cart):**  
- Manage quantities and sizes  
- Price breakdown with discounts  
- Delivery charge calculation  
- Proceed to checkout  

**Wishlist (/wishlist):**  
- Saved products management  
- Move to cart option  

**Profile & Checkout:**  
- Address management (/addresses)  
- Order history (/orders)  
- Complete checkout flow  

## API Reference
**Backend:** https://e-commerce-be-wheat.vercel.app/

GET /api/products

List all products  
Sample Response: `{ "data": { "products": [{ "_id", "name", "price", "category", "discount", ... }] } }`

GET /api/categories

All product categories  
Sample Response: `{ "data": { "categories": [{ "_id", "name", "description" }] } }`

POST /api/wishlist/:userId/add

Add to wishlist  
Body: `{ "productId": "..." }`

POST /api/orders/:userId/create

Create order from cart

Create order from cart

## Contact
For bugs or feature requests: rajeshkumarrour40@gmail.com