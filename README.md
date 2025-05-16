# Currency Converter

Welcome to the **Currency Converter**! This project is a challenge proposed by **Oracle** and **Alura**, developed using **Java** and the **Gson** library for JSON file handling.

## Features

* **Currency Conversion**: Converts values between different currencies using up-to-date exchange rates.
* **JSON Integration**: Reads and writes data to JSON files using the Gson library.
* **User Input**: The user can select source and target currencies and enter the amount to convert.
* **Conversion History**: Saves and displays a history of conversions in a JSON file.
* **Error Handling**: Includes validation for user input and file operations.

## Technologies Used

* **Java** for application logic
* **Gson** for parsing and generating JSON
* **File Handling** for reading/writing data
* **Command Line Interface (CLI)** for interaction

## How to Use

1. The application loads currency data and conversion history from JSON files.
2. The user selects the source and target currency.
3. The user inputs the amount to be converted.
4. The system performs the conversion and displays the result.
5. The conversion is saved in a history file (`history.json`).
6. The user can continue converting or exit the application.

## How to Run the Project

1. Clone this repository:

   ```sh
   git clone https://github.com/PauloBrazilian/One-Oracle-Next-Education--Currency-Converter
   ```
2. Access the project folder:

   ```sh
   cd currency-converter-java
   ```
3. Compile and run the project (using Java 17+):

   ```sh
   javac -cp gson-2.8.9.jar src/Main.java -d out
   java -cp "out;gson-2.8.9.jar" Main
   ```

💡 Make sure you have the `gson-2.8.9.jar` library in your project directory or add it to your dependencies if using a build tool like Maven or Gradle.

---

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/50/Oracle_logo.svg/512px-Oracle_logo.svg.png" alt="Oracle Logo" width="150"/>
  &nbsp;&nbsp;&nbsp;
  <img src="https://www.alura.com.br/assets/img/home/alura-logo.svg" alt="Alura Logo" width="55"/>
</p>

