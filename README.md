# BMI-Calculator-using-Flutter-Dart
BMI Calculator App
This is a simple Flutter app to calculate the Body Mass Index (BMI) based on a user's weight and height in feet and inches. The app takes the user's input for height (in feet and inches) and weight (in kilograms), calculates the BMI, and displays the result along with the corresponding BMI category (Underweight, Normal weight, Overweight, Obesity).

Features
Height Input: Users can input their height in feet and inches.
Weight Input: Users can input their weight in kilograms.
BMI Calculation: The app calculates BMI using the formula:
𝐵
𝑀
𝐼
=
Weight (kg)
Height (m)
2
BMI= 
Height (m) 
2
 
Weight (kg)
​
 
BMI Categories: Based on the BMI value, the app categorizes the result into:
Underweight: BMI < 18.5
Normal weight: 18.5 ≤ BMI < 24.9
Overweight: 25 ≤ BMI < 29.9
Obesity: BMI ≥ 30
Dynamic UI: The background color and text color change according to the BMI category.
Error Handling: If invalid input is provided (such as negative or non-numeric values), the app displays an error message.
Installation
To run this app locally, follow these steps:

Clone the repository or download the code files.
Install Flutter if you haven't already by following the official Flutter installation guide.
Run the app:
bash
Copy
Edit
flutter run
Usage
Enter Height: Input your height in feet and inches in the respective fields.
Enter Weight: Input your weight in kilograms in the weight field.
Calculate BMI: Tap on the "Calculate BMI" button to see the BMI and category.
View Result: After calculation, the BMI value and category will be displayed. The background color changes based on the category, and the category is displayed in corresponding colors.
Code Breakdown
Main Components:
BMICalculatorApp: The main stateless widget that sets up the app's theme and home screen.
BMICalculator: The stateful widget that contains the logic for input handling, BMI calculation, and displaying the results.
_BMICalculatorState: The state of the BMICalculator widget, where all the business logic (BMI calculation, state updates) happens.
Functions:
_calculateBMI(): This function reads the height and weight inputs, validates them, converts height to meters, calculates the BMI, and updates the state with the result and category.
Example Screenshots
Input Screen: Shows input fields for height and weight.
Result Screen: Displays the BMI result and category with dynamic background color.
License
This project is open-source and available under the MIT License.
