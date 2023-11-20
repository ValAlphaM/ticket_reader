# Ticket Reader Project

The Ticket Reader project is a Python application designed to extract and process information from receipts/tickets, including total amount, date, and transaction description. The project utilizes OCR (Optical Character Recognition) to analyze images of tickets and then organizes the extracted data for further use.

## Prerequisites

Before running the Ticket Reader project, ensure that you have the following prerequisites installed:

- Python (version 3.x)
- Tesseract OCR: [Installation Guide](https://github.com/tesseract-ocr/tesseract)
- Required Python packages: Install dependencies using `pip install -r requirements.txt`

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/ValAlphaM/ticket-reader.git
   cd ticket_reader
   ```

2. Install dependencies

    ```bash
    pip install -r
    ```
 
3. Run the application

    ```bash
    python main.py
    ```

## Usage 

1. Launch the application.
2. Select the Google Sheet to store ticket information.
3. Choose ticket images to analyze.
4. Validate and upload the recognized tickets to the Google Sheet.

## Features

- Optical Character Recognition (OCR) for ticket information extraction.
- Integration with Google Sheets for data storage.
- User-friendly Tkinter GUI for interaction.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Special thanks to the Tesseract OCR project for providing the OCR functionality.
- Inspiration and guidance from similar projects and open-source contributors.