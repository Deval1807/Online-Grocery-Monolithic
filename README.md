# Backend for Online Grocery Applicaion (Monolithic Architecture)

This is a simple backend project for an online grocery shopping application designed using monolithic architecture. The application consists of three main modules: Customer, Products, and Shopping, with secure authentication.

---

Also checkout the Microservices Version of the same Project

[Micorservices Architecture](https://github.com/Deval1807/Online-Grocery-Microservices)


## Table of Contents

1. [Getiing Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Cloning](#cloning)
    - [Configuration](#configuration)
    - [Starting the Project](#starting-the-project)
    - [Usage](#usage)
2. [Contribution](#contribution)
3. [Contact](#contact)


## Getting Started

### Prerequisites

- Node.js installed
- MongoDB database


### Clonning

Clone the Repository

```bash
git clone https://github.com/Deval1807/Online-Grocery-Monolithic
cd Online-Grocery-Monolithic
```


### Configuration

- Create a new file `.env` in all the 3 services' folders, i.e. customer, products and shopping
    - Make sure to have the following configuration in them

        ```env
        APP_SECRET=<your_secret_key>
        MONGODB_URI=<your_mongodb_url>
        PORT=<prot_no>
        ```


### Starting the Project

- Install the dependencies:
        ```bash
        npm install
        ```
- Make sure you have set up the `.env` files (see [Configuration](#configuration))
- Starting the Services
    ```bash
    npm start
    ```


### Usage

- Once the service is up and running,
- Visit  `http://localhost:<PORT>` 
- Use a tool like Postman to access API endpoints and make requests


## Contribution

We welcome contributions from the community. To contribute, please fork the repository, create a new branch, and submit a pull request. Make sure to follow the coding standards and ethical practices. 


## Contact

For questions or support, please contact Deval Darji by following ways:

1. LinkedIn: [Deval Darji](https://www.linkedin.com/in/deval-darji-a15002226/)

2. Email: [deval135darji@gmail.com](mailto:deval135darji@gmail.com)