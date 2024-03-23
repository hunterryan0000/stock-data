# Stock Data Service

A Spring Boot application that retrieves stock data from an external API, persists it into a PostgreSQL database, and provides access to the data through RESTful endpoints.

## Features

- Fetch and store daily open/close stock data from the Polygon API.
- Persist stock data in a PostgreSQL database.
- REST API to access historical stock data.

## Getting Started

### Prerequisites

- JDK 11 or higher
- Maven 3.6 or higher
- PostgreSQL
- pgAdmin (optional, for database management)

### Installation

1. Clone the repository:
   `git clone https://github.com/hunterryan0000/stock-data.git`

2. Navigate to the project directory:
   `cd stock-data-service`

3. Create the PostgreSQL database:
   (Provide instructions on setting up the database with pgAdmin or the PostgreSQL CLI)

4. Update `application.properties` with your database credentials:
   (Provide example configuration)

5. Run the application:
   `./mvnw spring-boot:run`

## API Endpoints

- `GET /api/stocks/{ticker}/{date}`: Fetch and store stock data for a specific ticker and date.
- EX: `https://api.polygon.io/v1/open-close/AAPL/2023-01-09?adjusted=true&apiKey=*`

## Contributing

Contributions are welcome. Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.
