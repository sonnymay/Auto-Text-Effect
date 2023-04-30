# Auto-Text-Effect


![Auto Text Effect](./assets/auto-text-effect-screenshot.png)

This repository contains the source code for an engaging text effect created by [Sonny May](https://github.com/sonnymay). The Auto Text Effect animates text by automatically typing, erasing, and retyping it. The live demo of the effect can be found at https://sonnymay.github.io/Auto-Text-Effect/.

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Configuration](#configuration)
5. [Technologies Used](#technologies-used)
6. [Contributing](#contributing)
7. [License](#license)

## Features

- Engaging typewriter-style text effect
- Automatically types, erases, and retypes text
- Configurable typing speed, erasing speed, and pause duration
- Supports multiple strings and looped playback

## Installation

To set up the Auto Text Effect on your local machine, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/sonnymay/Auto-Text-Effect.git
```

2. Navigate to the project directory:

```bash
cd Auto-Text-Effect
```

3. Open `index.html` in your favorite web browser.

## Usage

Simply include the `auto-text.js` file in your project and add the `data-auto-text` attribute to any HTML element you want the text effect to be applied to.

```html
<script src="auto-text.js"></script>
<h1 data-auto-text></h1>
```

## Configuration

To configure the Auto Text Effect, you can set the following `data-` attributes on the target HTML element:

- `data-strings`: A comma-separated list of strings to be displayed (e.g., `"Hello,World,Auto Text Effect"`).
- `data-type-speed`: The typing speed in milliseconds (default: `100`).
- `data-erase-speed`: The erasing speed in milliseconds (default: `50`).
- `data-pause-duration`: The pause duration between typing and erasing in milliseconds (default: `2000`).
- `data-loop`: Set to `true` if you want the effect to loop indefinitely (default: `false`).

## Technologies Used

- HTML
- CSS
- JavaScript

## Contributing

If you want to contribute to this project, please submit a pull request with your proposed changes or improvements. Any contributions are welcome and appreciated.

## License

This project is licensed under the [MIT License](./LICENSE).
