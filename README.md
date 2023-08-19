# Mohammad-Sakib-Hossain_API_Testing_Report

# API Testing Report Repository

Welcome to the API Testing Report repository! This repository contains documentation and reports related to the testing of our API endpoints. The purpose of this repository is to maintain a record of API test scenarios, results, and recommendations.

## Table of Contents

- [Introduction](#introduction)
- [Environment Setup](#environment-setup)
- [Test Scenarios](#test-scenarios)
- [Test Results](#test-results)
- [Recommendations](#recommendations)
- [Conclusion](#conclusion)
- [Appendices](#appendices)

## Introduction

This section provides an overview of the API testing process, the purpose of the tests, and the scope of the testing effort.

## Environment Setup

Describe the environment setup required to perform API testing. Include information about the tools, software, and dependencies needed to execute the test scenarios.

## Test Scenarios

###  Test Scenario 1: Customer Flight Booking.

- **Description:** Test the customer flight booking functionality.
- **Endpoint:** `/api/register`
- **HTTP Method:** POST
- **Test Steps:**
  1. Send a POST request with valid user flight booking data.
  2. Verify the response status code and structure.
  3. Check if the booking is added to the database.
- **Expected Outcome:** Successful flight booking with a 200 OK response.

###  Test Scenario 2: Check Customer Flight Booking Details.

- **Description:** Test to check the customer flight booking details functionality.
- **Endpoint:** `/api/register`
- **HTTP Method:** GET
- **Test Steps:**
  1. Send a GET request with valid user id.
  2. Verify the response status code and structure.
  3. Check if the booking data is correct and stored in the database.
- **Expected Outcome:** Successful flight booking details with a 200 OK response.

###  Test Scenario 3: Customer Flight Booking Authentication.

- **Description:** Test the customer flight booking authentication functionality.
- **Endpoint:** `/api/register`
- **HTTP Method:** POST
- **Test Steps:**
  1. Send a POST request with valid username and password.
  2. Verify the response status code and structure.
  3. Check if the Accesstoken is generated and updated in the environment.
- **Expected Outcome:** Successful token generated with a 200 OK response.

###  Test Scenario 4: Customer Flight Booking Details Full Update.

- **Description:** Test the customer flight booking details full update functionality.
- **Endpoint:** `/api/register`
- **HTTP Method:** PUT
- **Test Steps:**
  1. Send a PUT request with all the updated valid user flight booking data.
  2. Verify the response status code and structure.
  3. Check if the updated booking data is successfully added to the database.
- **Expected Outcome:** Successful flight booking details updated with a 200 OK response.

Test Scenario 5: Customer Flight Booking Details Partial Update.

- **Description:** Test the customer flight booking details partial update functionality.
- **Endpoint:** `/api/register`
- **HTTP Method:** PATCH
- **Test Steps:**
  1. Send a PATCH request with only the updated valid user flight booking data.
  2. Verify the response status code and structure.
  3. Check if the updated booking data is successfully added to the database.
- **Expected Outcome:** Successful flight booking details updated with a 200 OK response.

  Test Scenario 6: Customer Flight Booking Details Delete.

- **Description:** Test the customer flight booking details delete functionality.
- **Endpoint:** `/api/register`
- **HTTP Method:** DELETE
- **Test Steps:**
  1. Send a DELETE request with valid user id.
  2. Verify the response status code and structure.
  3. Check if the customer flight booking details deleted from the database.
- **Expected Outcome:** Successful flight booking details deleted with a 201 created response.

## Test Results

- Total Test Scenarios: [6]
- Passed: [6]
- Failed: [0]
- Skipped: [0]

## Conclusion

Conclude the API testing report by summarizing the overall findings, lessons learned, and the significance of the testing effort.

## Appendices

Include any additional information that supports the API testing report, such as raw request and response data, logs, or any other relevant data.

## License

This repository is licensed under the [MIT License](LICENSE).

---

Feel free to clone this repository and adapt the structure for your own API testing efforts. If you have any questions or suggestions, please don't hesitate to open an issue or reach out to us.

Happy testing!
