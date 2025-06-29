# TestAutomationReqnrollC#Project

This project is an automated UI test suite for the [saucedemo.com](https://www.saucedemo.com/) login page using Reqnroll (SpecFlow), NUnit, and Selenium WebDriver on .NET 8.

## Prerequisites

- .NET 8 SDK
- Edge or Chrome browser

## Setup

1. Clone the repository.
2. Run `dotnet restore` to install dependencies.
3. Install Reqnroll CLI (if not already):  
   `dotnet tool install --global Reqnroll.Tool`

## Running Tests

- Run all tests and generate reports with:  
  `dotnet reqnroll test`

## Reports

- After running tests, open `Reports/TestExecutionReport.html` for the results.

## Project Structure

- `Features/` – Gherkin feature files
- `StepDefinitions/` – Step definition classes
- `Pages/` – Page Object Model classes
- `Reports/` – Test reports

## Customizing Reports

- Edit `reqnroll.json` to change report format or output directory.

## Adding Tests

- Add new `.feature` files in `Features/`.
- Implement steps in `StepDefinitions/`.

---

For more, see [Reqnroll documentation](https://www.reqnroll.net/docs/).
