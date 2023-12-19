# Project README

## Golang CRUD Operations with SQLite, Gin, and GORM

### Overview

This project is a Golang-based application that provides RESTful APIs for CRUD (Create, Read, Update, Delete) operations. The project utilizes SQLite as the database, Gin as the web framework, and GORM as the Object Relational Mapping (ORM) library.

### Features

- **CRUD Operations**: Perform Create, Read, Update, and Delete operations on the data stored in the SQLite database.
- **Gin Framework**: Utilizes the Gin web framework to handle HTTP requests and responses.
- **GORM ORM**: Implements GORM to interact with the SQLite database and manage the data model.
- **RESTful APIs**: The project exposes RESTful APIs to interact with the data using standard HTTP methods.

### Technical Stack

- **Golang**: The project is developed using the Go programming language.
- **SQLite**: The lightweight, embedded database is used for data storage.
- **Gin**: The web framework is employed to handle HTTP requests and route them to the appropriate handlers.
- **GORM**: As the Object Relational Mapping library, GORM facilitates database interactions.

### Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/atharvaw1/golang-REST-crud.git
   ```

2. **Navigate to the Project Directory:**
   ```bash
   cd golang-REST-crud
   ```

3. **Install Dependencies:**
   ```bash
   go get
   ```

4. **Run the Application:**
   ```bash
   go run main.go
   ```

   The application will start, and the RESTful APIs will be accessible at `http://localhost:8080`.

### API Endpoints

- **Create Record:**
  - `POST /grocery` 

- **Retrieve All Records:**
  - `GET /groceries` 

- **Retrieve Single Record:**
  - `GET /groceries/:id`

- **Update Record:**
  - `PUT /grocieries/:id` 

- **Delete Record:**
  - `DELETE /grocieries/:id`



### Contributing

Feel free to contribute to this project by opening issues or submitting pull requests. Follow the standard GitHub workflow for collaboration.


