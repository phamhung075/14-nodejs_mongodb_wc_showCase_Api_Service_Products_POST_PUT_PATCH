# nodejs_mongodb_wc_showCase_Api_Service_Products_POST_PUT_PATCH

## Description

This project is a Node.js API service using MongoDB, designed for showcasing products. It supports various HTTP methods including POST, PUT, and PATCH, enabling users to create, update, and modify product data efficiently.

## Installation

To install this project, follow these steps:

1. Clone the repository: `git clone https://github.com/phamhung075/14-nodejs_mongodb_wc_showCase_Api_Service_Products_POST_PUT_PATCH.git`
2. Navigate to the project directory: `cd nodejs_mongodb_wc_showCase_Api_Service_Products_POST_PUT_PATCH`
3. Install dependencies: `npm install`

## Usage

This API provides several endpoints for managing products:

- **POST `/products`**: Add a new product.
    
    - Usage: `POST [API_BASE_URL]/products`
    - Body: `{ "name": "Product Name", "description": "Product Description", ... }`
- **PUT `/products/:id`**: Update a product by ID.
    
    - Usage: `PUT [API_BASE_URL]/products/:id`
    - Body: `{ "name": "New Product Name", ... }`
- **PATCH `/products/:id`**: Partially update a product by ID.
    
    - Usage: `PATCH [API_BASE_URL]/products/:id`
    - Body: `{ "description": "Updated Description" }`

For more detailed examples, refer to see README.png

## Contributing

Contributions are welcome! Please refer to the following guidelines:

1. Fork the repository.
2. Create a new branch for your feature.
3. Commit your changes.
4. Push to the branch and open a pull request.

## License

This project is licensed under the [MIT License](https://chat.openai.com/c/LICENSE.md).
