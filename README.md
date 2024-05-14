# Express MongoDB REST API

This repository contains a simple REST API built using Express.js, MongoDB, and Node.js. The API supports basic CRUD (Create, Read, Update, Delete) operations for managing products.

## Usage

To run the project locally, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/Hariharanm95/Rest-API.git
    ```

2. Navigate into the project directory:

    ```bash
    cd Rest-API
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

4. Set environment variables:

    ```
    NODE_ENV=production
    MONGO_URL=<your MongoDB connection URL>
    PORT=<desired port number, default is 3000>
    ```

5. Start the server:

    ```bash
    npm run dev
    ```

## API Endpoints

The base route for accessing the API is:

```
http://localhost:3000/api/products
```

### Available Endpoints:

- **GET /api/products**: Get all products.
- **GET /api/products/:id**: Get a specific product by ID.
- **POST /api/products**: Create a new product.
- **PUT /api/products/:id**: Update a product by ID.
- **DELETE /api/products/:id**: Delete a product by ID.

## Postman Collection

![Postman Collection](https://github.com/Hariharanm95/Rest-API/assets/100566501/ef1ebfbc-d1dd-46ef-9564-119ef3c9ca61)

## Deployment

The API is also deployed on Render and can be accessed at:

[https://rest-api-mx3t.onrender.com](https://rest-api-mx3t.onrender.com)

## Contributing

Feel free to contribute to this project by opening issues or pull requests. Contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
