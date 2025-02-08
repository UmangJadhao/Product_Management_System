# Product Management System with React and Spring Boot

A **Product Management System** developed using **React** for the frontend and **Spring Boot** for the backend. This simple web application allows users to **add, view, update**, and **delete** product details.

### Key Features:
- **Add Product**: Users can add new products by entering the product name, description, price, and other relevant details.
- **View Products**: All products are displayed on the home page with options to view the product details.
- **Update Product**: Users can update the product details, including changing the product's name, description, and price.
- **Delete Product**: Users can delete products from the system when they are no longer needed.
- **Responsive UI**: The application has a simple and intuitive user interface built using **React** and **Bootstrap**.

### Technologies Used:
- **Frontend**: React, JSX, HTML, CSS, Bootstrap
- **Backend**: Spring Boot, Java
- **Database**: MySql
- **API**: RESTful API for communication between the frontend and backend
- **Tools**: Maven (for managing dependencies and building the Spring Boot app)

### Functionalities:
- **Add Product**: A form to input product details (name, description, price).
- **Home Page**: Displays all added products with options to **Update** or **Delete** each product.
- **CRUD Operations**: The system supports the full range of CRUD operations (Create, Read, Update, Delete) for product management.
- **Backend API**: The Spring Boot backend exposes REST APIs for performing CRUD operations on products.

### How to Use:
1. **Clone the Repository**: Clone the repository to your local machine.
2. **Frontend**:
   - Navigate to the **React** frontend folder and run `npm install` to install dependencies.
   - Start the development server using `npm start`.
3. **Backend**:
   - Navigate to the **Spring Boot** backend folder and use Maven or your preferred method to run the Spring Boot application (`mvn spring-boot:run`).
4. **Access the App**: Open your browser and go to `http://localhost:3000` to use the application.

### Future Enhancements:
- **Product Search**: Add functionality to search for products by name or category.
- **User Authentication**: Implement authentication for users to manage products securely.
- **Pagination**: Add pagination to the product list for better navigation when the number of products grows.
- **Product Categories**: Implement a feature to categorize products (e.g., electronics, furniture, etc.).
- **Data Validation**: Add more form validation on the frontend and backend to ensure valid product data is submitted.
