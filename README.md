# Restful Booker Postman Collection

This is an **example** Postman collection for testing the [Restful Booker API](https://restful-booker.herokuapp.com/). It demonstrates how you might automate API testing with Postman, using example test cases and data-driven capabilities.  
**Note:** This collection is provided as a demonstration and is not intended as a comprehensive or exhaustive suite of tests.

## Overview

This repository contains a set of example requests and test scenarios for the Restful Booker API, a sample API that provides a booking management system. These collections illustrate common operations such as CRUD actions and basic filtering.

## Files

### 📋 Postman Collection
- **Restful Booker API - Example Automated Test Suite.postman_collection.json**
  - Example Postman collection with test scripts
  - Includes request definitions, basic test cases, and sample assertions
  - Covers standard API operations

### 🌍 Environment Configuration
- **restful-booker.postman_environment.json**
  - Postman environment file with API configuration
  - Contains base URLs and variables for running example requests
  - You may need to edit API endpoint variables

### 📊 Test Data
- **booking-filters.csv**
  - Example data for demonstrating data-driven tests (e.g., filter scenarios)
  - Contains sample test cases for filtering by firstname, lastname, dates, and their combinations
  - Includes positive and negative test cases for illustration

## Getting Started

### Prerequisites
- [Postman](https://www.postman.com/downloads/) installed

### Setup Instructions

1. **Import the Collection**
   - Open Postman
   - Click "Import" and select `Restful Booker API - Example Automated Test Suite.postman_collection.json`

2. **Import the Environment**
   - In Postman, click the environment dropdown
   - Select "Import" and choose `restful-booker.postman_environment.json`

3. **Configure Variables**
   - Update the environment variables with your API endpoint URL
   - Set any required authentication tokens if needed

4. **Run Example Tests**
   - Select the imported collection
   - Click "Run" to execute included test cases
   - Optionally, use `booking-filters.csv` for data-driven demonstration

## Features

- ✅ Example test scripts with assertions
- 🔄 Demonstration of data-driven testing
- 📝 Basic coverage of standard API operations
- 📋 Sample filter tests with different parameter combinations

## Example Test Scenarios Included

The collection includes example test cases for:
- Creating bookings
- Retrieving bookings
- Updating bookings
- Deleting bookings
- Filtering bookings by various criteria
- Validating basic API responses
- Handling error scenarios

## API Documentation

For more on the Restful Booker API, see:  
[https://restful-booker.herokuapp.com/](https://restful-booker.herokuapp.com/)

## Contributing

Contributions are welcome if you'd like to expand these examples or add more scenarios.

## License

This project is open source and available for educational and demonstration purposes.