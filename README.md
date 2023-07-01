A Python-GUI-calculator 
Here,for GUI representation tkinter is imported.Calculation a global variable which is assigned with a empty string but during execution it will store mathematical operation.
add_to_calculation(symbol) function is used for taking value and storing in calculation.
Calculation is done under evaluate_calculation() function through calling eval.If any exception comes so to handle that we used except.
To clear the field we used clear_field() function.
After that initialization of the window size of the calculator.
Create tkinter Button widgets for numbers 1-9, 0, and basic arithmetic operations. Set their text, command (linked to the respective add_to_calculation() function calls), width, and font.
The lambda function lambda: add_to_calculation(1) is created and assigned as the command for the button. When this button is clicked, the lambda function is executed, and it calls the add_to_calculation() function with the argument.
Clear_field and evaluate_calculation we are not here calling the function rather executing.
Call root.mainloop() to start the event loop and display the GUI. The program will continue running until the window is closed.
