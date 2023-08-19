# Simple JavaScript IDE Documentation

The Simple JavaScript IDE is a basic web-based code editor that allows users to write JavaScript code, run it, and see the output. It also features syntax highlighting for JavaScript code and the ability to execute mathematical operations.

## Features

- Syntax highlighting for JavaScript code.
- Execute JavaScript code and see the output.
- Evaluate mathematical operations and display the result.
- Support for both clicking a button and pressing Enter key for code execution.

## Usage

1. Open the HTML file in a web browser.
2. In the textarea, enter your JavaScript code or mathematical operation (e.g., "5 + 5").
3. Click the "Run Math Operation" button to evaluate a mathematical operation and display the result.
4. View the output in the designated output section below the textarea.

## Dependencies

- This project uses CodeMirror for syntax highlighting. Ensure that you have included the necessary CodeMirror CSS and JavaScript files.

## Code Structure

- `index.html`: The main HTML file containing the user interface elements and JavaScript code.
- `style.css`: Contains the CSS styling for the UI elements.
- `script.js`: Contains the JavaScript code for event listeners, code execution, and `console.log` override.

## Limitations

- The project uses `eval()` for code execution and mathematical operations. This may pose security risks, so it is not recommended for production use.
- CodeMirror is not integrated in this version, focusing on simplicity.

## Contributing

Contributions are welcome! Feel free to fork the repository, make improvements, and submit a pull request.

## License

This project is licensed under the [MIT License](/LICENSE.txt).

---

Created by [MD. Jashim Uddin](ju.cu.acc@gmail.com)
