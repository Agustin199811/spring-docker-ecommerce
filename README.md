# Spring Boot Ecommerce Order Status using Dockerfile and Docker Compose

This Spring Boot project provides an efficient solution for order management and tracking in an ecommerce setting. It enables customers to access real-time status updates on their purchases, enhances internal logistics and customer service coordination, and promotes a transparent, satisfying shopping experience. This not only strengthens day-to-day business operations but also fosters customer loyalty by providing clear, up-to-date information about their orders.

## Project Status

This project is currently in development and is being worked on for version 1.0.0.

## Technologies Used

- Java 17
- Spring Boot
- Maven
- MySQL
- Spring Data JPA
- Docker

## Installation and Setup

1. Clone this repository to your local machine using the following command:
    ```bash
    git clone https://github.com/Agustin199811/spring-docker-ecommerce.git

2. Import the project into your preferred IDE (e.g., IntelliJ IDEA or Eclipse) as a Maven project.

3. Run the Spring Boot application. The application will be available at `http://localhost:8081`.
    - Navigate to the root directory of your project (where your docker-compose.yml file is located).
        - `Build the Docker Compose`:
            + docker-compose build
        - `Run the Docker container:`
            + docker-compose up

## Usage


The Product Order Status REST API exposes the following endpoints:

- `GET /api/orders`: Get all orders.
- `GET /api/orders/customer/{customer}`: find order by customer name.
- `POST /api/orders`: Create a new orders.

You can use tools such as Postman or cURL to send HTTP requests to these endpoints.

## Deploy on Render

Switch to the `deploy` branch to upload to the Render cloud provider

To deploy the application on the Render cloud provider, follow these steps:

1. **Switch to the `deploy` branch**:
   ```bash
   git checkout deploy

## AWS with EC2
![image](https://github.com/Agustin199811/spring-docker-ecommerce/assets/91472854/ca39c3bb-6caa-4b6f-bb72-5748d4f26c06)

![image](https://github.com/Agustin199811/spring-docker-ecommerce/assets/91472854/e06228ea-8211-4f65-8138-4fa029bdedc4)

![image](https://github.com/Agustin199811/spring-docker-ecommerce/assets/91472854/81f94c8a-bb99-4ad8-b7f7-5a7e642fb5d9)

![image](https://github.com/Agustin199811/spring-docker-ecommerce/assets/91472854/26340c4e-a507-4f42-afde-180730014ede)

![image](https://github.com/Agustin199811/spring-docker-ecommerce/assets/91472854/54de6808-9e90-45d6-b365-41d62a1ee41a)

![image](https://github.com/Agustin199811/spring-docker-ecommerce/assets/91472854/fd429188-1247-4e66-a307-05d284e8d7ab)

## Contribution

If you wish to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b my-new-feature`.
3. Make your changes and commit them: `git commit -am 'Add a new feature'`.
4. Push your changes to your forked repository: `git push origin my-new-feature`.
5. Create a new pull request and describe your changes in detail.

## License

This project is licensed under the MIT License. You can find more information in the `LICENSE` file.

## Contact
Authors: Toapanta Agustin; Llano Edison

If you have any questions or suggestions, feel free to contact the development team at (toapantaagustin9c@gmail.com).
