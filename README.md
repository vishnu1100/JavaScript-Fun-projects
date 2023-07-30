# Fun Projects with HTML, CSS, and JavaScript


Welcome to my repository showcasing a collection of fun and exciting web projects developed with HTML, CSS, and JavaScript! Each project is designed to bring joy, creativity, and a touch of magic to your browsing experience. So, let's embark on this colorful journey together!

## Table of Contents

1. [Introduction](#introduction)
2. [Projects](#projects)
    - [1. Analog Clock ](#Project1-Analog-Clock)
    - [2. Password Generator ](#project-2-interactive-emoji-garden)
    - [3. QR Code Generator ](#project-3-gravity-defying-ball)
    - [4. To Do List ](#project-3-gravity-defying-ball)
    - [5. Calculator ](#project-3-gravity-defying-ball)
3. [How to Run](#how-to-run)
4. [Contributing](#contributing)
5. [License](#license)

## Introduction

This repository is a playground of whimsical web projects that leverage the power of HTML, CSS, and JavaScript to create delightful and entertaining experiences. Whether you're a seasoned developer or just starting your coding journey, you're sure to find something here that sparks your interest.

# Projects
<br>
<br>

# Project 1: Analog Clock


## Overview

This project is a simple analog clock developed using JavaScript, HTML, and CSS. The clock displays the current time in a traditional analog format with hour, minute, and second hands.

## Features

- Real-time updating: The clock updates every second to display the accurate time.
- Smooth animation: The clock hands move gracefully to show the time transition.
- Interactive design: Users can interact with the clock, adjusting the time manually by clicking and dragging the clock hands.


## Screenshots

![Screenshot 1](/screenshots/clock.png)


## Installation

To run this website locally, follow these steps:

1. Clone this repository to your local machine using the following command:

   ```bash
   git clone https://github.com/vishnu1100/JavaScript-Fun-projects.git
   ```

2. Open `index.html` in your preferred web browser.

## Font Styles

For this project, we have used the following fonts:

- **Roboto** (Google Fonts): Used for the digital time display.
- **Arial** (fallback): Used as the fallback font for maximum compatibility.

Make sure you have a stable internet connection to load the Google Fonts properly. If there are any issues, you can also download the font files and include them locally.

## Demo

Check out the live demo [here](https://vishnu1100.github.io/JavaScript-Fun-projects/Analog%20Clock/).



## Usage

The analog clock will automatically start displaying the current time once you open the `index.html` file in your browser. The hour, minute, and second hands will move accordingly to show the real-time.

## Customization

You can customize the following aspects of the clock:

- **Clock Size**: Adjust the size of the clock in the CSS file to fit your design requirements.
- **Clock Hands**: Modify the appearance of the hour, minute, and second hands using CSS styles.
- **Color Scheme**: Change the colors of the clock hands and clock face according to your preference.
- **Mode Options**: Can be Changed to Dark And Light Mode.

Feel free to experiment with the code and make it your own!

## Contributions

Contributions are always welcome! If you find any issues or want to add new features, please create a pull request. We appreciate your feedback and support.

## License

This project is licensed under the [MIT License](LICENSE).

---

Happy Coding! 🕒

---

<br>
<br>
<br>
<br>

# Project 2: Password Generator




## Password Generator



A simple and secure password generator developed with JavaScript that allows you to create strong and unique passwords with various font styles for added fun!

## Introduction

In an age where cyber threats are ever-increasing, having strong and unique passwords is crucial for safeguarding your online accounts. The Password Generator project aims to provide you with an easy-to-use tool that generates secure passwords tailored to your requirements.

## Features

- Customize password length to fit your needs.
- Choose from various font styles to make your passwords unique and visually appealing.
- Option to include uppercase, lowercase, numbers, and special characters in the generated password.
- Copy the generated password to your clipboard with a single click for quick and easy use.
- No need for an internet connection; it runs entirely on the client-side.

## Installation

1. Clone this repository to your local machine using:

```bash
git clone https://github.com/vishnu1100/JavaScript-Fun-projects.git
```

2. Navigate to the project directory:

```bash
cd password-generator
```

## Screenshots


![Screenshot 2](/screenshots/password.png)


## Usage

1. Open `index.html` in your web browser.

2. Adjust the settings as per your preferences:
   - Set the password length.
   - Check/uncheck the character options you want to include in the password.
   - Select your favorite font style from the available options.

3. Click the "Generate Password" button to create your customized password.

4. Use the "Copy Password" button to copy the generated password to your clipboard for immediate use.


## Demo

Check out the live demo [here](https://vishnu1100.github.io/JavaScript-Fun-projects/Password%20Generator/).


## Fonts

The Password Generator project comes with a variety of font styles to enhance your password aesthetics. You can easily add more font styles by following these steps:

1. Go to the [Google Fonts](https://fonts.google.com/) website.

2. Find the font you want to add and click on the "Select this style" button.

3. Click on the "Embed" tab, and you will see a link tag.

4. Copy the link tag and paste it into the `<head>` section of the `index.html` file, just before the closing `</head>` tag.

5. That's it! The new font style will now be available in the password generator.

## Contributing

Contributions to this project are welcome! If you find any issues or have ideas to improve the password generator, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Give it a try and create your strong and stylish passwords! Happy coding! :lock::rocket:



<br>
<br>
<br>
<br>

# Project 3: QR Code Generator 


## Introduction

The QR Code Generator is a JavaScript library that allows you to generate QR codes for various types of data, such as URLs, text, contact information, and more. This library is easy to integrate into your web applications and provides customizable options for QR code appearance.

QR codes are commonly used to encode data and can be scanned by most modern smartphones, making them an excellent choice for sharing information in a quick and convenient way.

## Features

- Generate QR codes for URLs, text, phone numbers, email addresses, and contact information.
- Customize QR code size, color, background, and error correction level.
- Lightweight and easy-to-use JavaScript library.
- Cross-platform compatibility.

## Installation

You can install the QR Code Generator library via npm:

```bash
npm install qr-code-generator-js
```

Alternatively, you can include the script directly in your HTML:

```html
<script src="path/to/qr-code-generator.min.js"></script>
```

## Usage

To use the QR Code Generator library, first, include the script in your HTML file as shown above. Then, you can create a QR code by calling the `generateQRCode` function with the data you want to encode.

```javascript
const data = "https://github.com/yourusername";
const qrCodeOptions = {
  size: 200,
  color: "#000000",
  background: "#ffffff",
  errorCorrectionLevel: "M",
};

const qrCodeImage = QRCodeGenerator.generateQRCode(data, qrCodeOptions);
document.getElementById("qrcode-container").appendChild(qrCodeImage);
```

## Examples

You can find more usage examples in the [examples](https://github.com/vishnu1100/JavaScript-Fun-projects) directory of this repository.

## Contributing

Contributions to this project are welcome! If you find any issues or have ideas to improve the password generator, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](./LICENSE).

---

Feel free to use, modify, and distribute this library to suit your needs. If you encounter any issues or have suggestions for improvement, please create an issue on GitHub. Happy coding!


## Demo

Check out the live demo [here](
https://vishnu1100.github.io/JavaScript-Fun-projects/QR%20Code%20Generator/).

## Installation

To run this website locally, follow these steps:

1. Clone this repository to your local machine using the following command:

   ```bash
   git clone https://github.com/vishnu1100/JavaScript-Fun-projects.git
   ```

2. Open the `index.html` file in your preferred web browser.

## Screenshots

![Screenshot 1](/screenshots/qr.png)





## Contributing

Contributions are always welcome! If you have any creative ideas or improvements, feel free to open an issue or submit a pull request. Let's make this repository an ever-growing collection of fun web projects together.

## License

This repository is licensed under the [MIT License](LICENSE), so you're free to use, modify, and distribute the code as you like. Attribution is appreciated but not required.

---

Thank you for stopping by! I hope you find these projects as enjoyable to explore as they were to create. If you have any questions or suggestions, feel free to reach out. Happy coding! 🌈✨

<br>
<br>
<br>
<br>

# Project 4: To Do List 



## Description

Welcome to Awesome To-Do List! This is a simple and elegant task management application developed using JavaScript. Stay organized and boost your productivity by easily adding, updating, and marking tasks as completed. The project showcases the power of JavaScript in creating a smooth and interactive user experience.

## Features

- Add tasks with due dates and priority levels
- Update and edit existing tasks
- Mark tasks as completed
- Filter tasks based on priority or completion status
- Beautiful and responsive user interface
- Cross-browser compatibility

## Demo

Check out the live demo of the project [here](https://vishnu1100.github.io/JavaScript-Fun-projects/To%20Do%20List/).

## Screenshots

![Screenshot 1](/screenshots/todo.png)


## Installation

Follow these steps to run the Awesome To-Do List on your local machine:

1. Clone this repository to your local machine using the following command:

   ```
   git clone https://github.com/vishnu1100/JavaScript-Fun-projects.git
   ```

2. Navigate to the project directory:

   ```
   cd awesome-todo-list
   ```

3. Open the `index.html` file in your preferred web browser.

## How to Use

1. Add a new task by typing the task description, selecting a due date, and setting its priority.
2. Click on a task to edit its details or mark it as completed.
3. Use the filter options to view tasks based on priority or completion status.
4. Enjoy a well-organized and efficient way of managing your tasks!

## Font Styles

The Awesome To-Do List project utilizes the following font styles:

- **Roboto**: A clean and modern font for the overall user interface.
- **Open Sans**: Used for headers and prominent elements to create a stylish and attractive look.

## Technologies Used

- JavaScript
- HTML5
- CSS5

## Contributions

We welcome contributions to make Awesome To-Do List even better! If you find any issues or want to add new features, please feel free to submit a pull request.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Contact

For any inquiries or feedback, please contact us at `Vishnusanthoshvr@gmail.com`.

---

Thank you for checking out our Awesome To-Do List project! We hope you find it helpful in organizing your tasks and staying productive. Happy task managing! 😄



<br>
<br>
<br>
<br>

# Project 5: Calculator
## Calculator Project



## Description

The Calculator project is a simple web application built using HTML, CSS, and JavaScript that provides basic arithmetic calculations. This project aims to showcase my skills in web development and demonstrate how I can implement core functionalities in a user-friendly calculator.

## Live Demo

Check out the live demo of the project [here](https://vishnu1100.github.io/JavaScript-Fun-projects/calculator/).

## Features

- Addition, subtraction, multiplication, and division operations
- Clear button to reset the input
- Responsive design for various screen sizes

## Preview

![Preview](/screenshots/calc.png)

## Installation

Follow these steps to run the Awesome To-Do List on your local machine:

1. Clone this repository to your local machine using the following command:

   ```
   git clone https://github.com/vishnu1100/JavaScript-Fun-projects.git
   ```


3. Open the `index.html` file in your preferred web browser.

## Usage

Simply open the `index.html` file in your web browser to access the calculator. Enter numbers and click on the respective operation buttons to perform calculations. Press the "C" button to clear the input.

## Font Styles

The calculator project uses the following custom font styles to enhance the user interface:

- Header Font: Roboto
- Button Font: Montserrat

To include these fonts in your project, add the following lines to the `<head>` section of your HTML file:

```html
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
```

Then, in your CSS file, set the appropriate font-family for the elements:

```css
body {
  font-family: 'Roboto', sans-serif;
}

.button {
  font-family: 'Montserrat', sans-serif;
}
```

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Happy calculating! If you have any questions or feedback, please don't hesitate to contact me at vishnusanthoshvr@gmail.com. Thank you for checking out this project! 🚀 
