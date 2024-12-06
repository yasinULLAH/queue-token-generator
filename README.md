```markdown
# Advanced Queue Token Generator

A web-based application for generating customizable queue tokens for events. It allows users to choose token formats (Standard, Arabic-Indic, Roman Numerals, Alphanumeric), generate a specified number of tokens, and customize the display layout. The app includes features for adding repeating or static text above and below each token, applying watermarks, adjusting token arrangements, and exporting the results to PDF.

## Features

- **Token Formats**: 
  - Standard (0-9)
  - Arabic-Indic (٠-٩)
  - Roman Numerals
  - Alphanumeric (Customizable)
  
- **Customizable Layout**:
  - Number of tokens to generate
  - Tokens per row
  - Rows per page
  - Page size options: Letter (8.5" x 11") and Legal (8.5" x 14")
  
- **Text Customization**:
  - Add static or repeating text before and after the token number
  - Add event name and guest name to each token
  
- **Watermarks**:
  - Add customizable watermarks with adjustable font size, color, and frequency on each page
  - Watermarks can be rotated and displayed multiple times
  
- **Inline Editing**:
  - Right-click functionality for repeating text above or below the token number
  
- **PDF Export**:
  - Export the generated tokens as a PDF for printing
  
- **Responsive Design**:
  - Adapts to different screen sizes, with proper layout for mobile devices and desktops
  
- **Print Settings**:
  - Hide non-essential UI elements when printing, showing only the token boxes and content

## How to Use

1. **Choose Token Format**:
   - Select your preferred token format from the dropdown: Standard, Arabic-Indic, Roman Numerals, or Alphanumeric.

2. **Enter Token Count**:
   - Specify how many tokens you need to generate.

3. **Set Layout**:
   - Adjust how many tokens appear per row and how many rows per page.
   - Choose between Letter or Legal page sizes for the layout.

4. **Add Text**:
   - Enter custom text that will appear above or below the token number.
   - You can also add static or repeating text for the event name and guest name.

5. **Watermark Settings**:
   - Choose watermark text, color, and the number of times it will appear on each page.
   - Optionally, rotate the watermark at different angles.

6. **Generate Tokens**:
   - Click the "Generate Tokens" button to see the tokens arranged in the desired format.

7. **Export as PDF**:
   - Click the "Export to PDF" button to download the generated tokens as a PDF for printing.

8. **Print Settings**:
   - When printing, only the tokens and their content will be visible, hiding unnecessary UI elements.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/queue-token-generator.git
   ```

2. Open `index.html` in your browser.

No server-side installation is required; the application works entirely in the browser.

## Dependencies

- [jsPDF](https://github.com/parallax/jsPDF) - For exporting content to PDF.
- [html2canvas](https://github.com/niklasvh/html2canvas) - For rendering the layout to canvas before exporting.
- JavaScript, HTML, and CSS for front-end design.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature-name`)
5. Create a new Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Special thanks to the developers of jsPDF and html2canvas for their amazing libraries.
```

This README provides an overview of the project, instructions on how to use it, and guidance on contributing and licensing. You can customize the URL and repository details as necessary.
