# Tek-Electronics - MERN app

# App Installation
1. Clone the repository:
```console
git clone https://github.com/hamzaaacodes/tek-electronics.git
```
2. Navigate to the project directory:
```console
cd tek-electronics
```
3. Install backend dependencies:
```console
cd server
npm install
```
4. Install frontend dependencies:
```console
cd client
npm install
```
5. Starting app - start the backend server:
```console
cd server
npm start
```
6. The backend server will run on http://localhost:5000.
7. Start the frontend development server:
```console
cd client
npm start
```
8. The frontend development server will run on http://localhost:3000.

# How it Works?
## Registeration / Login
1. Onces you visit the Home page of app it will redirect you to Login Page.
2. If you don't have account, you have to Register first.
3. Once you Register yourself you are able to Login
4. You can Login and get Authenticate with JWT-token.
## Admin (CRUD operations on Products)
5. You can see Admin Panel on the top-right corner of Header
6. To perform CRUD operation you have to Login as Admin
### NOTE:
* Admin Panel does not authenticate with JWT nor you can make account on that
* I've hardcoded the Admin credentials i.e., **username/password: humantek**
7. So you will Login as Admin by using above given Admin credentials, you are able to perform CRUD on products.
8. You can Add product with fields: Product Name, Brand, Price, Category and you can also Upload Product Image.
9. The Products you will add will be shown on "Shop Now" page for the customers.
## Buying Products and Generating Invoice
10. Now, you as a customer can buy Products by adding them to Cart.
11. Go to "Shop Now" pick the products you want to buy by clicking "Add to Cart"
12. You can remove products you added to your Cart by clicking "Remove from Cart"
13. You can see you Cart buy open Off Canvas using Cart Button to check your Billing details.
14. Once you done Shopping you can generate Invoice by clicking "Generate Invoice"
15. Once you Generate the Invoice, the invoice records get save in Database.
16. You can check your Invoices on "Invoices" page.
17. You can also delete the Invoices records records.
## Search Invoices with Product Name
17. From the Search tab on "Invoices" page you can Search Invoices by Product Names.
