# Restful Booker Postman Collection

A comprehensive Postman collection for testing the [Restful Booker API](https://restful-booker.herokuapp.com/) with automated test cases and data-driven testing capabilities.

## Overview

This repository contains a complete test suite for the Restful Booker API, a sample API that provides a booking management system. The collection includes various test scenarios covering CRUD operations, filtering, and validation.

## Files

### 📋 Postman Collection
- **Restful Booker API - Example Automated Test Suite.postman_collection.json**
  - Complete Postman collection with automated test scripts
  - Includes request definitions, test cases, and assertions
  - Pre-built test scenarios for common API operations

### 🌍 Environment Configuration
- **restful-booker.postman_environment.json**
  - Postman environment file with API configuration
  - Contains base URLs, variables, and setup for running tests
  - Configure this with your API endpoint details

### 📊 Test Data
- **booking-filters.csv**
  - Data-driven test cases for booking filter functionality
  - Contains test scenarios for filtering by:
    - Firstname
    - Lastname
    - Check-in date
    - Check-out date
    - Single and combined filter parameters
  - Includes both positive and negative test cases
  - Examples: no filters, invalid data, date range validation

## Getting Started

### Prerequisites
- [Postman](https://www.postman.com/downloads/) installed on your system

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

4. **Run Tests**
   - Select the imported collection
   - Click "Run" to execute all test cases
   - Use the `booking-filters.csv` for data-driven tests

## Features

- ✅ Automated test scripts with assertions
- 🔄 Data-driven testing capabilities
- 📝 Comprehensive API coverage
- 🧪 Pre-configured test scenarios
- 📋 Filter testing with multiple parameter combinations

## Test Scenarios Covered

The collection includes test cases for:
- Creating bookings
- Retrieving bookings
- Updating bookings
- Deleting bookings
- Filtering bookings by various criteria
- Validating API responses
- Error handling

## API Documentation

For more information about the Restful Booker API, visit:
[https://restful-booker.herokuapp.com/](https://restful-booker.herokuapp.com/)

## Contributing

Feel free to contribute improvements, additional test cases, or bug fixes.

## License

This project is open source and available for educational and testing purposes.