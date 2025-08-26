# Travel-Booking-Application

Automated Regression Test Suite Framework

Overview

This project designs an automated regression test suite framework for the Travel Booking Application (IRCTC/MakeMyTrip Clone), focusing on flight-related functionalities. It uses Java technologies, Selenium for UI testing, REST-Assured for API validation, and Spring Boot RESTful APIs for test management.

Prerequisites

Java 17+ Maven MySQL (or H2 for development) ChromeDriver for Selenium

Setup Instructions

Clone the repository: git clone <repository-url> Navigate to the project directory: cd regressionframework Configure application.properties with database credentials. Run mvn clean install to build the project. Start the application: mvn spring-boot:run Access APIs via Postman or curl (e.g., POST /tests/integrate).

Directory Structure

src/main/java: Core Java code src/test/java: Unit/integration tests reports/: Generated test reports logs/: Test failure logs and screenshots db-scripts/: Database schema scripts

Usage

Integrate tests via /tests/integrate Schedule tests via /schedule/run Generate reports via /reports/generate
