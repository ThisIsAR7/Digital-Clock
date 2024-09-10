# Digital Clock

This is a stylish and interactive world clock web application designed and developed by [AR7](https://arvinrezaei.com/). It displays the current time in hours, minutes, and seconds with an elegant circular graphical interface.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)

## Demo

To see a live demo of the hoverboard, open the `index.html` file in a web browser. You will see a grid of squares that change color and glow when you hover over them.

## Features

- Displays current time in hours, minutes, and seconds
- AM/PM indicator
- Circular graphical representation of time
- Responsive design

## Installation



1. Clone the repository:
    ```sh
    git clone https://github.com/ThisIsAR7/Digital-Clock.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Digital-Clock-main
    ```

## Usage

Open the `index.html` file in your preferred web browser to see the world clock in action.

### Project Structure

- **HTML**: The structure of the world clock
- **CSS**: Styling for the world clock, located in `css/style.css`
- **JavaScript**: Time functionality, located in `js/script.js`

### Example

The world clock includes a circular graphical interface for displaying the time. The `hours`, `minutes`, and `seconds` are shown in separate circles with different colors.

```html
<div id="time">
    <div class="circle" style="--clr:#FD5D5D">
        <svg>
            <circle cx="70" cy="70" r="70"></circle>
            <circle cx="70" cy="70" r="70" id="hh"></circle>
        </svg>
        <div id="hours">00</div>
    </div>
    <div class="circle" style="--clr:#00A9FF">
        <svg>
            <circle cx="70" cy="70" r="70"></circle>
            <circle cx="70" cy="70" r="70" id="mm"></circle>
        </svg>
        <div id="minutes">00</div>
    </div>
    <div class="circle" style="--clr:#FFBB64">
        <svg>
            <circle cx="70" cy="70" r="70"></circle>
            <circle cx="70" cy="70" r="70" id="ss"></circle>
        </svg>
        <div id="seconds">00</div>
    </div>
    <div class="ap">
        <div id="ampm">AM</div>
    </div>
</div>
