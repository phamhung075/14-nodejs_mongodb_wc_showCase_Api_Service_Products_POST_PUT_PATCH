# Node.js MongoDB Showcase Projects


This is a personal project series based on the lessons by @anonystick ([https://github.com/anonystick](https://github.com/anonystick)).
## 1. [Authentication and API Key Management (HS256)](https://github.com/phamhung075/2-nodejs_mongodb_wc_showCase_Dynamic_for_ApiKey_and_Permissions_HS256/tree/master)

## 2. [ErrorHandler ApiResponse](https://github.com/phamhung075/3-nodejs_mongodb_wc_showCase_ErrorHandler_API)

## 3. [Success Handler ApiResponse](https://github.com/phamhung075/4-nodejs_mongodb_wc_showCase_ApiResponseUseClass/tree/master?tab=readme-ov-file)

## 4. [SignUp and Login Public Access](https://github.com/phamhung075/5-nodejs_mongodb_wc_showCase_SignUpLogin)

## 5. [Logout Authentication](https://github.com/phamhung075/6-nodejs_mongodb_wc_showCase_LogoutAuthentication)
## 6. [Refresh Token and Token Verification](https://github.com/phamhung075/7-nodejs_mongodb_wc_showCase_RefreshToken_verifyToken)
## 7. [Schema for Products in E-commerce](https://github.com/phamhung075/8-nodejs_mongodb_wc_showCase_Schema_Products_Ecommerce)
## 8. [API for Products Using Factory Pattern](https://github.com/phamhung075/11-nodejs_mongodb_wc_showCase_Api_Service_use_Factory_Pattern_Products_Senior_lv)

## 9. [API Service for Product Draft, Publish, and Unpublish](https://github.com/phamhung075/12-nodejs_mongodb_wc_showCase_Api_Service_Products_isDraft_isPublish_unPublish)
## 10. [API Service for Product Data Retrieval](https://github.com/phamhung075/13-nodejs_mongodb_wc_showCase_Api_Service_Products_findAll_findOne_selectData_unSelectData)
## 11. API Service for Products: PATCH

### Introduction

`14-nodejs_mongodb_wc_showCase_Api_Service_Products_POST_PUT_PATCH` is a Node.js application demonstrating the implementation of PATCH HTTP methods in product management services using MongoDB. This project showcases how to handle creating, updating, and partially updating product data in an e-commerce platform.

### Installation

- Clone the repository:

    `git clone https://github.com/phamhung075/14-nodejs_mongodb_wc_showCase_Api_Service_Products_POST_PUT_PATCH.git`
    
- Change to the directory:

    `cd 14-nodejs_mongodb_wc_showCase_Api_Service_Products_POST_PUT_PATCH`
    
- Install dependencies:

    `npm install`
    

### Features

- **Product Model** (`./models/product.model.js`): Defines the product data structure and schema in MongoDB.
- **Product Service** (`./services/product.service.js`): Manages the business logic for adding, updating, and patching product data.
- **Product Repository** (`./repositories/product.repo.js`): Handles database operations for product services.
- **Product Controller** (`./controllers/product.controller.js`): Orchestrates API endpoints for product data manipulation using PATCH methods.
- **Utilities** (`./utils/utils.js`): Includes utility functions such as `updateNestedObjectParser` to support complex update operations.

### Usage

- Demonstrates CRUD operations (Update) with an emphasis on Update operations through PATCH methods.
- Suitable for e-commerce platforms requiring dynamic product management capabilities.

### MongoDB Connection

- Connect to MongoDB using: `mongodb://localhost:27017/yourDatabase`

### Additional Notes

- The project emphasizes RESTful API design principles and best practices for managing product data.
- The implementation can be adapted or extended for different e-commerce application requirements.

### Postman Examples

- **Signup**, **Login**, **Logout** examples as in the previous project.
- **Token Refresh** examples as in the previous project.
- **Create Product** examples as in the previous project.
- **Publish Product** examples as in the previous project.
- **UnPublish Product** examples as in the previous project.
- **get all Draft Products** examples as in the previous project.
- **get all Published Products** examples as in the previous project.
- **Find Product** examples as in the previous project.
- **Find All Products** examples as in the previous project.
- **Search Products by name** examples as in the previous project.
- **Modify Product** examples
``` 
@url_dev=http://localhost:3052/v1/api/product/

### Modify Product
PATCH {{url_dev}}/[PRODUCT_ID]
Content-Type: application/json
x-api-key: [API_KEY]
x-client-id: [SHOP_ID]
authorization: [ACCESS_TOKEN]

{
    "product_name": "New Leggings polaire green",
    "product_type": "Clothing",
    "product_attributes": {
                "material": "Paper"
            }
}
```

For more detailed examples, refer to see [README.png](./help14.png).
