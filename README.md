## Flask Application Design for E-commerce Website

### HTML Files
- **home.html**: Main landing page of the website, showcasing featured products, categories, and promotions.
- **products.html**: Displays a list of all available products, with options for filtering, sorting, and pagination.
- **product-details.html**: Dedicated page for each product, including detailed description, images, reviews, and purchase options.
- **cart.html**: Displays the contents of the user's shopping cart, with options to modify quantities, remove items, and checkout.
- **checkout.html**: Final checkout page, where users can provide shipping and payment information to complete their purchase.

### Routes
- **Home**: `/` - Main landing page route, displays the `home.html` page.
- **Products**: `/products` - List of all products route, displays the `products.html` page.
- **Product Details**: `/product/<product_id>` - Dedicated product page route, displays the `product-details.html` page.
- **Add to Cart**: `/cart/add/<product_id>` - Route for adding a product to the user's shopping cart.
- **Update Cart**: `/cart/update/<product_id>` - Route for updating the quantity of a product in the user's cart.
- **Remove from Cart**: `/cart/remove/<product_id>` - Route for removing a product from the user's cart.
- **Checkout**: `/checkout` - Checkout page route, displays the `checkout.html` page.
- **Order Confirmation**: `/order-confirmation` - Order confirmation page route, displays the order details after successful checkout.