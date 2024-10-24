Name: Akhilendra Pratap Singh                                                                                              
Company: CODTECH IT SOLUTIONS                                                                                           
ID: CT6WDS1922                                                                                           
Domain: Java Programming                                                                                           
Duration: September to October 2024                                                                                           

### **Calculator Project - Overview**

#### **Project Introduction**
The Calculator Project is a basic GUI-based Java application that allows users to perform simple arithmetic operations like addition, subtraction, multiplication, and division. The graphical user interface (GUI) is built using Java Swing, and it includes a text field for displaying the inputs and outputs, along with buttons representing numbers, operators, and other control functions (e.g., clear and delete). The calculator performs basic math calculations between two operands and displays the result in real-time.

#### **Key Features**
1. **Basic Arithmetic Operations**:
   - The calculator supports the following operations:
     - **Addition (+)**: Adds two numbers.
     - **Subtraction (-)**: Subtracts the second number from the first.
     - **Multiplication (*)**: Multiplies two numbers.
     - **Division (/)**: Divides the first number by the second.
  
2. **User Interface**:
   - The interface consists of a grid of buttons, including number buttons (0-9), operator buttons (+, -, *, /), a decimal point button (.), an equals button (=) for calculating results, and control buttons for clearing the input or deleting the last digit.
   - **Text Field**: A text field is used for input and output. Users input numbers and operations via the buttons, and the result is displayed in the text field.

3. **Error Handling**:
   - The application checks for valid inputs and supports clearing the input or deleting individual digits.
   - Handles basic errors like division by zero or incomplete input.

4. **Action Listener Integration**:
   - Every button is linked to an ActionListener that processes user input. The listener detects the user's button presses and updates the calculator's state accordingly.

#### **Classes and Methods**

##### 1. **Main Class: `calcu`**
   - This is the main class of the calculator, which extends `JFrame` and implements `ActionListener` to capture and respond to user actions.
   - **Constructor**: The constructor initializes the components, sets up the layout, and adds action listeners to each button.

##### 2. **Buttons and Components**:
   - **Number Buttons**: A set of 10 buttons (0-9) for numeric input.
   - **Function Buttons**: Buttons for operations (`+`, `-`, `*`, `/`), a decimal point button (`.`), and other control functions like equals (`=`), clear, and delete.
   - **JTextField**: A text field at the top of the calculator serves as both the input and output display.

##### 3. **Layout and GUI Setup**:
   - The calculator's buttons are arranged in a 4x4 grid using a `GridLayout`. This layout provides a clear, intuitive design for user interaction.
   - The frame includes a border layout with the text field at the top and the button panel in the center.

##### 4. **Event Handling (ActionListener)**:
   - **Number Button Handling**: When a user presses a number button, the corresponding digit is appended to the text field, allowing them to build a multi-digit number.
   - **Operator Handling**: When an operator button is pressed (`+`, `-`, `*`, `/`), the first number is saved, the operator is recorded, and the text field is cleared for the second input.
   - **Equals Button (`=`)**: When pressed, the calculator performs the operation based on the stored operator and operands and displays the result in the text field.
   - **Control Buttons**:
     - **Clear Button**: Resets the calculator by clearing the text field and resetting the operator and operands.
     - **Delete Button**: Removes the last digit from the current input.

##### 5. **Arithmetic Operations**:
   - When the equals button is pressed, the calculator evaluates the stored operator and operands and performs the corresponding calculation. The result is displayed in the text field.
   - The supported operations include addition, subtraction, multiplication, and division.

#### **Error Handling and Edge Cases**:
1. **Division by Zero**: The calculator should handle division by zero by displaying an appropriate error message or handling it gracefully.
2. **Empty Input**: The calculator checks for valid input before performing any operations.
3. **Multiple Decimal Points**: Prevents users from entering more than one decimal point in a number.

#### **User Interaction**:
- The user interacts with the calculator using a GUI that provides a clear, button-based interface for inputting numbers and operations.
- The buttons are responsive and provide real-time feedback as users enter numbers and calculations.

#### **Enhancements and Future Improvements**:
1. **Scientific Calculator Features**: Implement additional functionalities such as square roots, powers, and trigonometric functions.
2. **Keyboard Input**: Allow the calculator to accept keyboard input for faster and more intuitive user experience.
3. **Error Notifications**: Display error messages in the text field if invalid operations are attempted.
4. **Memory Functions**: Add memory buttons (M+, M-, MR) to store and recall numbers for future calculations.

#### **Conclusion**:
This Calculator Project provides a simple yet functional calculator application with basic arithmetic features. It demonstrates the use of Java Swing for building graphical interfaces and handling user interactions via event listeners. The project offers a foundation for further expansion into more advanced calculator features, and it's an excellent starting point for learning GUI programming in Java.
