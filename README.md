# OmniStore  

OmniStore is a modern e-commerce platform that delivers a seamless shopping experience. Built with a robust tech stack, it encompasses user management, product reviews, cart functions, order processing, and secure payment methods. 

Deployed link: https://eccomers96.netlify.app/ 

## Features  

- **User Management**: Registration, login, and profile management.  
- **Product Catalog**: Browse, search, and review products.  
- **Shopping Cart**: Add, update, and remove items from the cart.  
- **Order Processing**: Checkout and view order history.  
- **Secure Payments**: Encrypted transactions with JWT and Spring Security.  
- **Responsive UI**: Built with React for optimal user experience.  

## Tech Stack  

- **Backend**:  
  - Java  
  - Spring Framework  
  - Spring Boot  
  - Spring Data JPA  
  - Hibernate  
  - MySQL  
  - Swagger  
  - Spring Security  
  - JSON Web Tokens (JWT)  
  - BCrypt  

- **Frontend**:  
  - JavaScript  
  - React  

- **Build Tool**:  
  - Maven  

- **HTTP Client**:  
  - Axios  

## Getting Started  

Follow these instructions to set up and run OmniStore locally.  

### Prerequisites  

- Java 11 or higher  
- Maven  
- Node.js and npm  
- MySQL  

### Installation  

1. **Clone the repository**:  
    ```bash  
    git clone https://github.com/VishnuKumarVerma/OmniStore.git  
    cd OmniStore  
    ```  

2. **Set up the database**:  
    - Create a MySQL database named `omnistore_db`.  
    - Update the database credentials in `backend/src/main/resources/application.properties`.  

3. **Build and run the backend**:  
    ```bash  
    cd backend  
    mvn clean install  
    mvn spring-boot:run  
    ```  

4. **Set up the frontend**:  
    ```bash  
    cd frontend  
    npm install  
    npm start  
    ```  

5. **Access the application**:  
   - Open your browser at [http://localhost:3000](http://localhost:3000) for the frontend.  
   - Access the API documentation at [http://localhost:8080/swagger-ui/](http://localhost:8080/swagger-ui/) for backend API.  

## Usage  

- Register a new user or log in with existing credentials.  
- Explore products, manage your cart, and proceed to checkout.  

## API Documentation  

Access detailed API documentation via Swagger once the backend is running. It is located at:  

  http://localhost:8080/swagger-ui/


## Contributing  

Contributions are welcome! To contribute:  

1. Fork the repository.  
2. Create your feature branch (`git checkout -b feature/YourFeature`).  
3. Commit your changes (`git commit -m 'Add some feature'`).  
4. Push to your branch (`git push origin feature/YourFeature`).  
5. Open a pull request.  

## License  

Distributed under the MIT License. For more details, please refer to the `LICENSE` file.  

## Contact  

**Vishnu Kumar Verma**  
[GitHub Profile](https://github.com/VishnuKumarVerma)  
Email: vishhnukumarverma574@gmail.com
