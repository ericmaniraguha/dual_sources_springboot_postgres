# Multiple DataSource Spring Boot Application

This is a Spring Boot application that demonstrates how to configure and use multiple data sources in a single application. It includes two separate data sources: "employee" and "manager".

## Table of Contents

- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Configuration](#configuration)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

- Java Development Kit (JDK) 8 or later
- PostgreSQL database server

## Getting Started

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/ericmaniraguha/dual_sources_springboot_postgres.git
   
2. 
Certainly, here's the entire content in markdown format for easy copying:

markdown
Copy code
# Multiple DataSource Spring Boot Application

This is a Spring Boot application that demonstrates how to configure and use multiple data sources in a single application. It includes two separate data sources: "employee" and "manager".

## Table of Contents

- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Configuration](#configuration)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

- Java Development Kit (JDK) 8 or later
- PostgreSQL database server

## Getting Started

1. Clone this repository to your local machine:

   `git clone https://github.com/ericmaniraguha/dual_sources_springboot_postgres.git`
   
2. Configure your PostgreSQL databases:

- Create databases named employeedb and managerdb.
- Configure the first.datasource and second.datasource properties in src/main/resources/application.properties to match your - PostgreSQL database settings.
3. Build and run the application:
  cd dual_sources_springboot_postgres
./mvnw spring-boot:run
## Configuration

- `application.properties`: Configuration properties for data sources and Hibernate settings.
- `com.multdatasource.MultipleDataSourceSpringBootApplication`: Main Spring Boot application class.

## Usage

The application exposes REST endpoints for saving employee and manager records.

- To save an employee, send a POST request to `/employee/save` with a JSON payload containing employee details.
- To save a manager, send a POST request to `/manager/save` with a JSON payload containing manager details.

## Contributing

Contributions are welcome! If you find any issues or improvements, please open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/your-feature-name`.
5. Open a pull request.

## License

This project is licensed under the MIT License.

GitHub Repository: [https://github.com/ericmaniraguha/dual_sources_springboot_postgres.git](https://github.com/ericmaniraguha/dual_sources_springboot_postgres.git)
![image](https://github.com/ericmaniraguha/dual_sources_springboot_postgres/assets/44385819/1be56edc-1220-4f3b-b407-877917dd32b4)
