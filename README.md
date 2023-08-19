## Table of Contents

- [Introduction](#introduction)
- [Environment Setup](#environment-setup)
- [Test Scenarios](#test-scenarios)
- [Test Results](#test-results)
- [Conclusion](#conclusion)
- [Appendices](#appendices)

## Introduction

Welcome to the API Testing Report repository! This repository contains documentation and reports related to the testing of API of [api](https://restful-booker.herokuapp.com). This API tesing was done as an assignment for the Online Course: Complete SQA (Manual and Automation). 

Organization: [Bug Resistance](https://bugresistance.com/)

Course Instructor: Mohoshi Haque

## Environment Setup

API Testing: https://www.postman.com/

Web Browser : Google Chrome Version 115.0.5790.173 (Official Build) (64-bit)

Report Generation:
  1. Download the Postman Collection.
  2. Download the Postman Environment.
  3. Install Node.js from the [website](https://nodejs.org/en)
  4. Install Newman by Opening the Command Promt of our Device and run the command: npm install -g newman
  5. Open command promt in the directory where you saved the collection and environment file and run the command: newman run [name of your collection including the extension] -e [name of your environment including the extension] -r cli,htmlextra



## Test Scenarios

###  Test Scenario 1: Customer Flight Booking.

- **Description:** Test the customer flight booking functionality.
- **Endpoint:** `/api/booking/`
- **HTTP Method:** POST
- **Test Steps:**
  1. Send a POST request with valid user flight booking data.
  2. Verify the response status code and structure.
  3. Check if the booking is added to the database.
- **Expected Outcome:** Successful flight booking with a 200 OK response.

###  Test Scenario 2: Check Customer Flight Booking Details.

- **Description:** Test to check the customer flight booking details functionality.
- **Endpoint:** `/api/booking/userid`
- **HTTP Method:** GET
- **Test Steps:**
  1. Send a GET request with valid user id.
  2. Verify the response status code and structure.
  3. Check if the booking data is correct and stored in the database.
- **Expected Outcome:** Successful flight booking details with a 200 OK response.

###  Test Scenario 3: Customer Flight Booking Authentication.

- **Description:** Test the customer flight booking authentication functionality.
- **Endpoint:** `/api/auth`
- **HTTP Method:** POST
- **Test Steps:**
  1. Send a POST request with valid username and password.
  2. Verify the response status code and structure.
  3. Check if the Accesstoken is generated and updated in the environment.
- **Expected Outcome:** Successful token generated with a 200 OK response.

###  Test Scenario 4: Customer Flight Booking Details Full Update.

- **Description:** Test the customer flight booking details full update functionality.
- **Endpoint:** `/api/booking/userid`
- **HTTP Method:** PUT
- **Test Steps:**
  1. Send a PUT request with all the updated valid user flight booking data.
  2. Verify the response status code and structure.
  3. Check if the updated booking data is successfully added to the database.
- **Expected Outcome:** Successful flight booking details updated with a 200 OK response.

Test Scenario 5: Customer Flight Booking Details Partial Update.

- **Description:** Test the customer flight booking details partial update functionality.
- **Endpoint:** `/api/booking/userid`
- **HTTP Method:** PATCH
- **Test Steps:**
  1. Send a PATCH request with only the updated valid user flight booking data.
  2. Verify the response status code and structure.
  3. Check if the updated booking data is successfully added to the database.
- **Expected Outcome:** Successful flight booking details updated with a 200 OK response.

  Test Scenario 6: Customer Flight Booking Details Delete.

- **Description:** Test the customer flight booking details delete functionality.
- **Endpoint:** `/api/booking/userid`
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
Feel free to clone this repository and adapt the structure for your own API testing efforts. If you have any questions or suggestions, please don't hesitate to open an issue or reach out to me.

Happy testing!
