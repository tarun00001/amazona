# Amazon
1 Introduction
2 Install Tools
3 Create React App
4 Create Git Repository
6 List feature product and added css
7 a) npm i react-router-dom
  b) create route for home screen
  c) create router for product screen  
8 a) added express server
  b) added nodemon as dev dependency
9 a) set proxy in package.json in frontend folder
  b) npm i axios
  c) use state hook
  d) use effect hook
  e) use reducer hook
10 manage state by reducer hook
  a) define reducer
  b) update fetch data
  c) get state from reducer 
11 Added bootstrap ui  
12 components:- 1)product 2)rating
13 create product detail screen
  1. fetch products
  2. create 3 columns for image, info and screen.
14 create loading and message component.
  1. create loading component
  2. use spinner component
  3. create message component 
  4. create utils.js to define getError function  
15 Implement Add to cart
  1. create React context
  2. define reducer
  3. create store provider
  4. implement add to cart button click handler  
16 complete add to cart
  1. check exist item in the cart
  2. check out in stock in backend  
17 Create cart screen
  1. create 2 column
  2. display items list
  3. create action column  
18 complete cart screen
  1. click handler for inc/dec item
  2. click handler for remove item
  3. click handler for checkout
19  create signin screen
  1. create signin form
  2. add email and password
  3. add signin button  
20. connect to mongodb database
  1. create atlas mongodb database
  2. install local mongodb database
  3. npm i mongoose
  4. connect to mongodb database
21. Seed Sample Products
    1. create Product model
    2. create seed route
    3. use route in server.js
    4. seed sample product   
22. Seed Sample Users
    1. create user model
    2. seed sample users   
23. Create Signin Backend API
    1. create signin api
    2. npm install jsonwebtoken
    3. define generateToken      
24. Complete Signin Screen
    1. handle submit action
    2. save token in store and local storage
    3. show user name in header   
25. Create Shipping Screen
    1. create form inputs
    2. handle save shipping address
    3. add checkout wizard bar    
26. Create Sign Up Screen
    1. create input forms
    2. handle submit
    3. create backend api   
27. Implement Select Payment Method Screen
    1. create input forms
    2. handle submit   
28. Create Place Order Screen
    1. show cart items, payment and address
    2. handle place order action
    3. create order create api 
    4. calculate order summary   
28. Implement Place Order Action
    1. handle place order action
    2. create order create api       
30. Create Order Screen
    1. create backend api for order/:id
    2. fetch order api in frontend
    3. show order information in 2 cloumns
31. Pay Order By PayPal
    1. generate paypal client id
    2. create api to return client id
    3. install react-paypal-js
    4. use PayPalScriptProvider in index.js
    5. use usePayPalScriptReducer in Order Screen
    6. implement loadPaypalScript function
    7. render paypal button
    8. implement onApprove payment function
    9. create pay order api in backend    