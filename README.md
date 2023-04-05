# ecommerce
This is an attempt to create an e-commerce clone to demonstrate my web development skills.  I will also do my very best to document everything so I can practice my writing skills which I am, I think, average at best. If possible, I would also like to add software testing/unit testing in the mix but as of the moment, I do not have any idea how to implement that. Currently, I am learning to write test (manual testing) in order for me to see my vision work. This is a work in progress and although I am very scared whether I can finish this 100% or not, I still feel very excited about this project.

## The E-commerce website will have the following features:
- Product Page: this will be the main page of the website. Upon accessing the website, the user will be greeted right away with the item catalogue. The user will then be able to choose from the items and item categories, with the option to add the item to 'cart'. When the user is done adding items to cart, he/she may proceed with the checkout page that will require the user to login or register (if there is no registered account yet).

- Login Page: all transaction require users to login to the website first before checking out purchase, adding/posting items for sale, and other website features

- Register Page: allows the user to register an account to the e-commerce website

- Admin Dashboard Page: every user will have the power to add his/her own items for sale. Thus, every user that has an online shop setup will have his/her own admin dashboard that will display the following:
    - Inventory: the seller will have an overview of the items listen in his/her store. The admin/seller will have the power to create, edit, update, delete items listed.
    - Shipping Status of Items: this page will show the seller items ordered from him/her and shipping status of items (ex. 'for shipping' or 'shipped') so that the seller can track the shipping status of the items.

- Product Reviews: buyers of a certain product can post product reviews of a product that they have bought. They can also rate the product using star-rating method.

- Order History: users will have the ability to check their order history.

- Related Products: the website will recommend similar items to the user (products other customers bought similar to the item bought).

- Auto-email of Order Summary: in every purchase, the application will email the user's registered email address an electronic receipt of that certain purchase.

- SMS auto-send of Order Status: when seller updates the shipping status of a product/order, an SMS update will be sent to the buyer's registered mobile number to update him/her the shipping status of the product.

## Technologies I plan to use:
- HTML5
- CSS
    - Bootstrap (may or may not be used)
- JavaScript
    - jQuery (may nor may not be needed)
    - Node.JS for backend
    - Express
    - AJAX
- MySQL
- Stripe API (for checkout)
- Some automailer API for Auto-email of order summary feature
- Some SMS API for SMS auto-send feature

## Projected Timeline:
### April 5, 2022 to April 6, 2022:
    - Some preliminary planning and this cool README.md
    - Product Page Wireframe
    - Login Page Wireframe
    - Register Page Wireframe
    - Item Details Wireframe
    - Shopping Cart Wireframe
    - Admin Dashboard: Orders Wireframe
    - Admin Dashboard: Products Wireframe
        - Admin Dashboard: Edit Product Wireframe
        - Admin Dashboard: Add Product Wireframe

### April 7, 2022 to April 9, 2022:
    Frontend for:
        - Product Page
        - Login Page
        - Register Page
        - Item Details Page
        - Shopping Cart Page
        - Admin Dashboard: Orders Page
        - Admin Dashboard: Products Page
            - Admin Dashboard: Edit Product Page
            - Admin Dashboard: Add Product Page

### April 10, 2022 to April 11, 2022:
    - Database Design/ERD
    - Pre-populate database with sameple data

### April 12, 2022:
    - Connect products table to Products Page
    - Login Page Functionality
    - Register Page Functionality
    - Connect items table to Item Details Page

### April 13, 2022:
    - Connect database to admin dashboard features

### April 14, 2022:
    - Product reviews feature

### April 15, 2022:
    - Order history feature

### April 16, 2022:
    - Related products feature

### April 17, 2022:
    - AJAX

### April 18, 2022:
    - Connect to Stripe API

### April 19, 2022 to April 20, 2022:
    - Auto-email feature

### April 21, 2022 to April 22, 2022:
    - Auto-SMS feature

### April 23, 2022:
    - Some final documentation
    - Deployment
