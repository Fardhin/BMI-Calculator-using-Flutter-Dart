# BMI-Calculator-using-Flutter-Dart


This is a simple Flutter app to calculate the Body Mass Index (BMI) based on a user's weight and height in feet and inches. The app takes the user's input for height (in feet and inches) and weight (in kilograms), calculates the BMI, and displays the result along with the corresponding BMI category (Underweight, Normal weight, Overweight, Obesity).

## Features

- **Height Input**: Users can input their height in feet and inches.
- **Weight Input**: Users can input their weight in kilograms.
- **BMI Calculation**: The app calculates BMI using the formula:
  \[
  BMI = \frac{\text{Weight (kg)}}{\text{Height (m)}^2}
  \]
- **BMI Categories**: Based on the BMI value, the app categorizes the result into:
  - Underweight: BMI < 18.5
  - Normal weight: 18.5 ≤ BMI < 24.9
  - Overweight: 25 ≤ BMI < 29.9
  - Obesity: BMI ≥ 30
- **Dynamic UI**: The background color and text color change according to the BMI category.
- **Error Handling**: If invalid input is provided (such as negative or non-numeric values), the app displays an error message.

## Installation

To run this app locally, follow these steps:

1. **Clone the repository** or download the code files.
2. **Install Flutter** if you haven't already by following the [official Flutter installation guide](https://flutter.dev/docs/get-started/install).
3. **Run the app**:
   ```bash
   flutter run
