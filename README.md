<img src="./header.gif" width="100%">
# Shifting Symmetry

Shifting Symmetry is a web project that showcases a dynamically shifting background pattern designed to create a hypnotic visual experience. The background, composed of symmetrical, diamond-shaped repeating lines, moves randomly across the screen, providing an engaging and visually stimulating effect.


## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Features

- **Hypnotic Visuals:** A dynamically shifting background pattern that creates an illusionary and hypnotic effect.
- **User Consent:** A built-in consent popup that warns users of potential illusions and hypnosis before allowing them to view the full effect.
- **Randomized Motion:** The background pattern shifts randomly every second, with varied directions and distances to keep the visuals engaging.
- **Responsive Design:** The project is built to be fully responsive and works on all screen sizes.

## Demo

Check out the live demo here: [Shifting Symmetry Live Demo](link-to-live-demo) *(Add a link to your live demo if available)*

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/tensor35/shifting-symmetry.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd shifting-symmetry
   ```

3. **Open the `index.html` file in your browser:**
   You can simply double-click on the `index.html` file, or you can serve it using a local development server if you prefer.

## Usage

Once you open the project in your browser:

1. **Consent Popup:** The page will load with a blurred background and a consent popup. Users must click "I Consent" to proceed.
2. **Background Animation:** After consent, the background pattern will start shifting randomly across the screen every second.

## Customization

You can customize the project by modifying the following:

- **Background Image:** Replace the `assets/pattern.png` file with your preferred pattern image.
- **Shifting Range:** Adjust the shifting range in the JavaScript code by changing the values in the `getRandomOffset` function.
- **Blur Effect:** Modify the initial blur effect by changing the `filter` property in the `.background-container` CSS class.
- **Consent Text:** Edit the text in the consent popup by modifying the HTML content inside the `consent-popup` div.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`.
3. Commit your changes: `git commit -m 'Add your feature'`.
4. Push to the branch: `git push origin feature/your-feature-name`.
5. Open a pull request.

Please ensure that your code adheres to the existing code style and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

- **Inspiration:** The concept of shifting patterns is inspired by various visual arts and optical illusions.
- **Tools:** This project was developed using standard web technologies, including HTML, CSS, and JavaScript.
- **Contributors:** Thanks to all who have contributed to improving this project.
