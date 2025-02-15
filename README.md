# JulesAI - README

## Project Overview
JulesAI is a project designed to automate testing using Playwright. This repository contains test scripts for validating login functionality, UI components, and other web application features.

## Prerequisites
Before running the project, ensure you have the following installed:
- Node.js (v16 or later)
- npm or yarn
- Playwright

## Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/aprajputcode/JulesAI.git
   cd JulesAI
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
   or if using yarn:
   ```bash
   yarn install
   ```

3. Install Playwright browsers:
   ```bash
   npx playwright install
   ```

## Running Tests
To execute the test cases, use the following command:
```bash
npx playwright test
```

To run tests with headed mode (UI visible):
```bash
npx playwright test --headed
```

To run a specific test file:
```bash
npx playwright test tests/login.spec.ts
```

## Assignment Details
This repository includes automation scripts for testing login functionality of Harold Waste demo application. The tests cover:
- Successful login
- Invalid login (wrong password)
- Empty credentials validation
- Shadow DOM element handling
- Network Task

## Test Framework
- **Playwright** is used for automation testing
- **Expect assertions** are used for validations

## Network Task
Screenshots related to the network task have been attached in the root folder. These screenshots provide insights into network requests and responses captured during test execution.
