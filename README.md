# react-native-temperature-converter
# Temperature Converter App

A simple React Native application for converting temperatures between Celsius and Fahrenheit.

## Key Features

* **Input Field:** Allows users to enter a temperature value.
* **Real-time Conversion:** Displays the converted temperature as the user types.
* **Unit Toggle:** A button to switch between Celsius and Fahrenheit as the input unit.
* **Dynamic Background:** The app's background color changes based on the displayed temperature.

## Technologies Used

* React Native

## Getting Started

1.  **Clone the repository:**
    ```bash
    git clone [repository URL]
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd [project directory name]
    ```
3.  **Install dependencies:**
    ```bash
    npm install
    # or
    yarn install
    ```
4.  **Start the application:**
    ```bash
    npx react-native run-android # For Android
    # or
    npx react-native run-ios   # For iOS
    ```

## Core Concepts Demonstrated

* **Layout:** Basic structuring of UI elements.
* **Text Input:** Handling user input.
* **Components:** Creating reusable UI elements (e.g., `DisplayTemperature`).
* **State Management:** Updating and displaying temperature values.
* **Temperature Conversion:** Implementing the logic for Celsius to Fahrenheit and vice versa.
* **Event Handling:** Responding to button presses.
* **`useEffect` Hook:** Performing side effects like changing the background programmatically based on temperature.

## Further Development

Potential future enhancements include:

* More sophisticated UI/UX.
* Saving conversion history.
* Displaying temperature ranges (e.g., "Freezing," "Warm").
* Error handling for invalid input.
