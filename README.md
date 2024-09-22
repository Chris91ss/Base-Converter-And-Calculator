---

### Base Converter and Calculator App

This app is a comprehensive tool designed for converting numbers between different numerical bases and performing arithmetic operations in any base from 2 to 16. It is perfect for developers, students, or anyone dealing with number systems outside of base 10.

#### Key Features:

- **Base Converter:**
  - Convert numbers between any two bases (from base 2 to base 16).
  - Choose from multiple conversion methods:
    - Base 10 as an intermediary
    - Rapid conversions
    - Substitution method
    - Successive divisions method

- **Base Calculator:**
  - Perform arithmetic operations in any base with these calculation methods:
    - Addition in base p
    - Subtraction in base p
    - Multiplication of a number by a digit in base p
    - Division of a number by a digit in base p

- **Documentation Tab:**
  - A dedicated **Documentation** tab provides detailed explanations of the app’s logic in **pseudocode**, making it easy for users to understand how each conversion and calculation method works.

- **User-Friendly Interface:**
  - With an easy-to-navigate design, input numbers, select bases, and immediately view results, making it simple to switch between methods and operations.

---

#### Available Online

The app is now available for use in the browser on itch.io! You can try it out here: [Base Converter and Calculator](https://chris91s.itch.io/base-converter-calculator).

---

### Code Overview

The app’s code structure is carefully designed for efficiency and modularity, allowing easy maintenance and updates. Below is an overview of the primary components and their functions:

1. **Conversion Logic (ConvertLogic):**
   - Handles all conversion methods, including:
     - Conversion using base 10 as an intermediary.
     - Rapid conversions for bases that are powers of 2.
     - Substitution method for more complex base conversions.
     - Successive divisions for direct conversions between any two bases.

2. **Calculation Logic (CalculateLogic):**
   - Manages arithmetic operations across different bases:
     - Supports addition, subtraction, multiplication, and division.
     - Includes error checking for invalid inputs, ensuring numbers are valid for the selected base.
     - Handles edge cases such as leading zeros, negative results (for subtraction), and remainder handling (for division).

3. **UI Handling (UIDisplay):**
   - Manages the swapping between the different tabs: Converter, Calculator, and Documentation.
   - Ensures a clean and responsive user interface, allowing for real-time updates as users input numbers and select methods.

4. **Error Handling and Validation:**
   - Each input is validated based on the selected base, ensuring only valid digits for the chosen base are accepted.
   - Appropriate error messages are displayed in case of invalid input or failed operations.

5. **Test Suite (TestFunctions):**
   - The app includes a set of unit tests to validate the core conversion and calculation logic.
   - Ensures that changes or updates to the app don’t break existing functionality.

This modular approach allows for easy expansion, testing, and debugging. The code is well-commented, making it easy to understand and modify.

---

### How to Download and Launch the Build:

To run the app locally, follow these steps:

1. **Download the build**: Go to the repository and download the **zip file** named **"Build"** from the main branch.
2. **Extract the files**: Unzip the contents of the file to a folder of your choice.
3. **Locate the executable**: Inside the extracted folder, find the file named **Base Converter & Calculator.exe**.
4. **Launch the app**: Double-click the executable to start the app.

   You should also see accompanying files such as:
   - **Base Converter & Calculator_Data** (folder)
   - **MonoBleedingEdge** (folder)
   - **UnityPlayer.dll** (file)

   Ensure all files are kept together in the same folder for the app to run correctly.

---

#### Perfect for Learning and Practical Use

Whether you're studying binary, octal, hexadecimal, or any other base, this app provides a versatile and accessible way to perform conversions and calculations. The added documentation makes it a great learning tool, while the variety of methods ensures practicality in any scenario.

---
