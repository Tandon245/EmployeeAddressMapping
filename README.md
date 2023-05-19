# Employee-Address Management System

The Employee-Address Management System is a Java-based project that provides a robust solution for modeling and managing the relationship between Employees and their Addresses. Built using Spring Boot and JPA, this project offers a RESTful API for performing CRUD operations on the Employee and Address models. The data is stored in a MySQL database, ensuring efficient and reliable data management.

## Technologies Used

The following technologies are utilized in this project:

- Java
- Spring Framework
- Hibernate
- MySQL

## API Endpoints

The system provides the following API endpoints for seamless integration and interaction with the application:

### Employee Endpoints

- `GET /employees`: Retrieve a list of all employees.
- `GET /employees/{id}`: Retrieve an employee by their ID.
- `POST /employees`: Create a new employee.
- `PUT /employees/{id}`: Update an existing employee.
- `DELETE /employees/{id}`: Delete an employee.

### Address Endpoints

- `GET /addresses`: Retrieve a list of all addresses.
- `GET /addresses/{id}`: Retrieve an address by its ID.
- `POST /addresses`: Create a new address.
- `PUT /addresses/{id}`: Update an existing address.
- `DELETE /addresses/{id}`: Delete an address.

## Controllers

The project includes two controllers to handle requests related to the Employee and Address models:

### EmployeeController

The `EmployeeController` handles requests related to the Employee model, providing a seamless interface to perform CRUD operations.

### AddressController

The `AddressController` handles requests related to the Address model, enabling the manipulation of address information effortlessly.

## Services

The project includes two services responsible for implementing the business logic and handling CRUD operations on the Employee and Address models:

### EmployeeService

The `EmployeeService` encapsulates the logic for performing CRUD operations on the Employee model, ensuring efficient and secure data management.

### AddressService

The `AddressService` facilitates CRUD operations on the Address model, providing comprehensive functionality to manage address information with ease.

## Repositories

The project utilizes two repositories to interact with the data source and perform database operations:

### EmployeeRepository

The `EmployeeRepository` provides access to the Employee data source, allowing seamless retrieval and storage of employee-related information.

### AddressRepository

The `AddressRepository` facilitates interaction with the Address data source, ensuring efficient and reliable management of address information.

## Summary

The Employee-Address Management System is a Java-based solution that offers a professional and efficient way to manage employee and address information. Leveraging the power of Java, Spring Framework, Hibernate, and MySQL, it provides a RESTful API for performing CRUD operations on both the Employee and Address models. To contribute to this project, simply fork the repository, make your enhancements, and submit a pull request.

We welcome contributions and look forward to further improving this management system to meet the evolving needs of businesses and organizations.
