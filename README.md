Calculator class:

__init__(self): Initializes the calculator by creating the main window, setting its properties, and initializing variables such as total_expression and current_expression.

bind_keys(self): Binds keys for numerical digits, operators, Enter key for evaluation, and Backspace key for backspacing.

create_special_buttons(self): Calls functions to create special buttons like clear, equals, square, and square root.

create_display_labels(self): Creates two labels for displaying the total expression and current expression in the calculator window.

create_display_frame(self): Creates a frame for the display labels with a specified height and background color.

add_to_expression(self, value): Adds a value (digit or operator) to the current expression and updates the display label.

create_digit_buttons(self): Creates digit buttons (0-9 and '.') and binds them to add_to_expression function.

append_operator(self, operator): Appends an operator to the current expression, updates the total expression, and clears the current expression for the next input.

create_operator_buttons(self): Creates operator buttons (+, -, *, /) and binds them to append_operator function.

clear(self): Clears both the current and total expressions and updates the display labels.

create_clear_button(self): Creates a clear button and binds it to the clear function.

square(self): Calculates the square of the current expression and updates the display label.

create_square_button(self): Creates a square button and binds it to the square function.

sqrt(self): Calculates the square root of the current expression and updates the display label.

create_sqrt_button(self): Creates a square root button and binds it to the sqrt function.

evaluate(self): Evaluates the total expression, updates the current expression, and clears the total expression for the next input.

create_equals_button(self): Creates an equals button and binds it to the evaluate function.

backspace(self): Removes the last character from the current expression and updates the display label.

create_buttons_frame(self): Creates a frame for the calculator buttons.

update_total_label(self): Updates the total label by replacing operators with their corresponding symbols for better readability.

update_label(self): Updates the current label with the current expression, limiting the displayed characters to 11.

run(self): Runs the Tkinter main loop to start the calculator application.

__main__ block: Creates an instance of the Calculator class and runs the calculator application when the script is executed.






