# Katalon DemoQA Project

This project contains automated test cases for the DemoQA form submission feature using Katalon Studio version Katalon_Studio_Windows_64-10.3.2. It includes positive and negative test scenarios to validate form inputs, submissions, and error handling.

## Prerequisites

- **Katalon Studio**: Download and install Katalon Studio from the official website: [https://www.katalon.com/download/](https://www.katalon.com/download/).
- **Java**: Ensure Java is installed on your system (Katalon requires Java 8 or higher).
- **Git**: To clone the repository.

## Installation

1. **Clone the Repository**:
   ```
   git clone https://github.com/shidqiadiatma/Katalon-DemoQA.git
   cd Katalon-DemoQA
   ```

2. **Open in Katalon Studio**:
   - Launch Katalon Studio.
   - Select **File > Open Project**.
   - Navigate to the cloned directory and select the project file (e.g., `pnm-technical-test.prj`).
   - Click **Open** to load the project.

## Running the Tests

1. **Open Test Suites**:
   - In Katalon Studio, navigate to the **Test Suites** folder in the **Tests Explorer** panel.
   - Available test suites:
     - `TS_Positive/TS_Submit_Positive.ts`: Runs positive test cases for successful form submissions.
     - `TS_Negative/TS_Submit_Negative.ts`: Runs negative test cases for validation failures.

2. **Execute a Test Suite**:
   - Right-click on the desired test suite (e.g., `TS_Submit_Positive.ts`).
   - Select **Run** or **Debug**.
   - Choose the browser (e.g., Chrome, Firefox) and execution profile if prompted.
   - The tests will run automatically, and results will be displayed in the **Log Viewer** and **Reports** tab.

3. **View Reports**:
   - After execution, go to the **Reports** tab to view detailed test results, including pass/fail status, screenshots, and logs.

## Project Structure

- **Test Cases**: Contains individual test cases for positive and negative scenarios.
- **Test Suites**: Groups test cases for batch execution.
- **Object Repository**: Stores UI elements for the DemoQA form.
- **Data Files**: Test data files (e.g., Excel, images) used in tests.
- **Scripts**: Groovy scripts for custom keywords and utilities.

## Contributing

- Fork the repository.
- Create a new branch for your changes.
- Commit and push your changes.
- Submit a pull request.

## License

This project is for educational purposes. Refer to Katalon Studio's licensing terms.
