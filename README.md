# Calculations_of_times
This Java application simplifies the tracking and calculation of working hours and order durations. 
It efficiently processes user inputs for start and end times or dates, providing precise calculations for the duration of work periods and the intervals between order and delivery.

## Features
- **Working Hours Calculation**: Users can calculate the total duration between entered start and end times, with results displayed in hours and minutes.
- **Order Duration Calculation**: Determines the number of days between specified order placement and delivery dates.
- **Input Validation**: Employs regular expressions to validate input formats, ensuring all time and date entries meet the required `hh:mm` and `yyyy-mm-dd` standards.
- **Interactive Menu Interface**: Provides a user-friendly menu that guides users through the process of entering data and receiving computations.

## Usage Instructions
Upon launching the application, users will be greeted with a menu:
- **Choose Operation**: The menu will prompt users to select either the calculation of working hours (`1`) or order duration (`2`).
- **Input Data**:
  - For working hours: Input the start and end times. Enter 'now' to automatically use the current time, or specify times manually in `hh:mm` format.
  - For order durations: Enter the order and delivery dates. Use 'now' for the current date, or provide dates in `yyyy-mm-dd` format.
- **Submit and Calculate**: After entering the data, the application calculates and displays the results based on the chosen operation.

### Examples of Valid Inputs
- Time: `09:15`, `17:30`
- Date: `2023-03-15`, `2023-03-20`

### Outputs
- For working hours: "Hours worked: 8:15"
- For order durations: "Delivery took 5 days"

## Error Handling
- **Format and Validation Errors**: If an input does not match the expected format, the program alerts the user with an error message and requests the correct format be entered. This process repeats until valid input is provided.
- **Logical Input Checks**: The application ensures logical consistency, such as checking that end times are not earlier than start times or delivery dates are not prior to order dates.
- **Feedback on Errors**: Direct feedback is provided for any input mismatches or logical errors, guiding users to make necessary corrections.


