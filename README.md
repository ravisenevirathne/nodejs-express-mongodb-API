This is a Backend REST API Implementation using NodeJS, Express, MongoDB

To test the API use below Postman requests

- Save a Product 
```
POST http://localhost:3000/products

{
    "name": "Apples",
    "quantity": 10,
    "price": 1,
    "image": "https://media.istockphoto.com/id/1337091069/photo/moisturizing-soap-bar.jpg?s=1024x1024&w=is&k=20&c=FXL4ih6Ht1L-0h4WQQaYOmicMqurr5SNw3JcHN2yZzo="

}
```
- List All Products
```
GET http://localhost:3000/products
```
- List single product by ID
```
GET http://localhost:3000/products/65ec59b314d12aad135510f0
```
- UPDATE product by ID
```
PUT http://localhost:3000/products/65ec59b314d12aad135510f0

{
    "name": "NEW shampoo",
    "quantity": 10,
    "price": 5,
    "image": "https://media.istockphoto.com/id/1337091069/photo/moisturizing-soap-bar.jpg?s=1024x1024&w=is&k=20&c=FXL4ih6Ht1L-0h4WQQaYOmicMqurr5SNw3JcHN2yZzo="
}

```

- DELETE a product by ID
```
DELETE http://localhost:3000/products/65ec59c414d12aad135510f2
```
