<p align="center">
  <img src="https://github.com/user-attachments/assets/a309174f-50fa-4030-bce7-15abb997514c" alt="image"/>
</p>

# Typing Speed Test Game

Welcome to the **Typing Speed Test Game**! This web application allows users to test and improve their typing speed in a fun and interactive way. The game presents a random paragraph for users to type within a specified time limit while tracking their performance metrics.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Responsive Design](#responsive-design)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Typing Speed Measurement**: Calculates Words Per Minute (WPM) based on user input.
- **Error Tracking**: Counts the number of mistakes made during typing.
- **Time Limit**: Users have a fixed time (60 seconds) to complete the typing task.
- **Try Again Button**: Allows users to restart the game easily.
- **Responsive Design**: Fully responsive layout that works on various screen sizes.

## Technologies Used

- HTML
- CSS
- JavaScript

## Getting Started

To get started with the Typing Speed Test Game, follow these steps:

1. **Clone the Repository**
   ```
   git clone https://github.com/GZ30eee/typing-speed-app.git
   cd typing-speed-app
   ```

2. **Open in Your Browser**
   Open `index.html` in your preferred web browser.

## Usage

1. Start typing the displayed text in the input field.
2. The timer will start counting down from 60 seconds.
3. Your WPM, mistakes, and characters per minute (CPM) will be displayed in real-time.
4. Click the "Try Again" button to reset the game and load a new paragraph.

## How It Works

The game randomly selects a paragraph from a predefined list and displays it for the user to type. As the user types, the application tracks their input, calculates WPM and mistakes, and updates the display accordingly. The game ends when the timer reaches zero, at which point users can see their performance metrics.

### Key Functions

- `loadParagraph()`: Loads a random paragraph for typing.
- `initTyping()`: Handles user input and updates performance metrics.
- `initTimer()`: Manages the countdown timer.
- `resetGame()`: Resets all metrics and loads a new paragraph.

## Responsive Design

The Typing Speed Test Game is designed to be fully responsive, ensuring an optimal experience on devices of all sizes. The layout adjusts seamlessly for mobile phones, tablets, and desktops.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Thank you for checking out the **Typing Speed Test Game**! We hope you enjoy testing your typing skills!
