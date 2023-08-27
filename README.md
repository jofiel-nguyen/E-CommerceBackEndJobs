# E-Commerce Back End

Welcome to the E-Commerce Back End project! In this project, we will build the back end for an e-commerce website using the latest technologies. This back end will serve as the foundation for a fully functioning e-commerce platform, allowing your company to compete with other e-commerce giants.

## Project Overview

Internet retail, also known as **e-commerce**, is a massive industry, generating trillions of dollars in revenue. E-commerce platforms like Shopify and WooCommerce provide essential services to businesses of all sizes. Understanding the fundamental architecture of these platforms is crucial for any full-stack web developer.

Our task is to create the back end of an e-commerce site by modifying starter code. We will configure a functional Express.js API that uses Sequelize to interact with a MySQL database. This API will provide the necessary functionality for managing products, categories, and tags.

## User Story

As a manager at an internet retail company, you want a robust back end for your e-commerce website that leverages the latest technologies. This back end will empower your company to compete effectively in the competitive e-commerce market.

## Acceptance Criteria

To ensure the success of this project, we have defined the following acceptance criteria:

1. **Database Connection**: You should be able to connect to a database using Sequelize by providing the database name, MySQL username, and MySQL password via an environment variable file.

2. **Database Initialization**: When you run schema and seed commands, a development database should be created and populated with test data. This ensures that your system is ready for testing and development.

3. **Server Start**: When you invoke the application, your server should start, and Sequelize models should be synced to the MySQL database, ensuring that your API is ready to serve requests.

4. **GET Routes**: When you use API GET routes in tools like Insomnia for categories, products, or tags, the data for each of these routes should be displayed in a well-formatted JSON format.

5. **POST, PUT, and DELETE Routes**: When you test API POST, PUT, and DELETE routes in Insomnia, you should be able to successfully create, update, and delete data in your database. These routes should provide full CRUD (Create, Read, Update, Delete) functionality.

## Mock-Up

Here are some mock-up animations that demonstrate the functionality of our application in action:

- **GET Routes**: In Insomnia, you can see how our application handles "GET" requests for categories, products, and tags. It returns well-structured JSON data.

  ![GET Routes in Insomnia](./Assets/13-orm-homework-demo-01.gif)

- **Single Item GET**: This animation demonstrates how to retrieve a single category, product, or tag by its ID using "GET" requests in Insomnia.

  ![Single Item GET in Insomnia](./Assets/13-orm-homework-demo-02.gif)

- **POST, PUT, DELETE Routes**: In this animation, we show the functionality of "POST," "PUT," and "DELETE" routes for categories. You can create, update, and delete categories seamlessly using Insomnia.

  ![POST, PUT, DELETE Routes in Insomnia](./Assets/13-orm-homework-demo-03.gif)

## Getting Started

To get started with this project, please visit the GitHub repository: [E-Commerce Back End GitHub Repository](https://github.com/nhunguyen-debug/ORM-Wren-Rice)

Clone the repository to your local machine and follow the installation and usage instructions provided in the repository's README.

We hope this project helps you gain a deeper understanding of e-commerce back-end development and equips you with the skills necessary to compete in the ever-evolving e-commerce industry. Good luck with your project, and feel free to reach out if you have any questions or need assistance!

Happy coding! 🚀
