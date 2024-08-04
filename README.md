# PRODIGY_WD_02
# Stopwatch Application

This is a simple Stopwatch application built using HTML, CSS, and JavaScript. It provides a user-friendly interface for starting, stopping, and resetting a timer.

## Features

- Start, stop, and reset the timer
- Displays time in hours, minutes, and seconds
- Responsive design with a centered layout

## Technologies Used

- HTML
- CSS
- JavaScript

## Getting Started

To view and use the Stopwatch application locally, follow these steps:

1. **Clone the repository** or download the HTML file.
2. Open the HTML file in your preferred web browser (e.g., Chrome, Firefox, Safari).
3. The stopwatch application will be displayed, and you can start using it.

## Code Overview

### HTML Structure
The main structure consists of:
- A `<div>` for displaying the time
- Buttons for controlling the timer: Start, Stop, and Reset

### CSS Styles
The CSS styles are embedded in the `<style>` tag in the `<head>` section of the HTML document:
- **Body**: Centers the stopwatch on the screen with a background image.
- **Stopwatch**: Styled with a white background, padding, rounded corners, and a subtle shadow.
- **Buttons**: Styled with different colors for each action (start, stop, reset).

### JavaScript Functionality
The JavaScript handles the timer logic:
- **startTimer()**: Initiates the timer and updates the display every 10 milliseconds.
- **stopTimer()**: Stops the timer and calculates the time difference.
- **resetTimer()**: Resets the timer back to `00:00:00`.
- **updateDisplay()**: Updates the time displayed based on the elapsed time.

### Event Listeners
Event listeners are added to buttons to execute the respective functions when clicked.

## Contact

For any inquiries or feedback, feel free to reach out to the project creator.

## License

This project is open-source and available under the MIT License. You are free to modify and use it as you wish.
