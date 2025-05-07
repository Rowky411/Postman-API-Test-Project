## API Overview
The Valentino Artisan Coffee House API allows you to:
- Check the API status
- List and view details of available products
- Register as a client
- Create and retrieve orders

## Base URL
```bash
https://valentinos-coffee.herokuapp.com
```

## API Status
### GET /status
    Returns the current status of the API.
    #### Test: 
         - Asserts that the status code is 200.
## Products
### GET /products
    Fetch a paginated list of products.
    #### Tests:
         - Status code 200
### GET /products/:productId
    Fetch details of a single product by ID.
    #### Tests:
         - Status code 200
         - Valid JSON response
         - Schema validation
    
     
