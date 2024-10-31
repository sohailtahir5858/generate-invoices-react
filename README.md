# Invoice Generator

A React-based application for generating invoices. This project allows users to create, review, and print invoices as PDFs with options to customize billing details, currency, rate, discounts, and more.

## Features

- **Checkout Page**: Complete form for billing details and cart item operations.
- **Invoice Generation**: Allows customization of invoice details such as currency, rate, discounts, date, notes, and invoice number.
- **Invoice Preview and Review**: A dedicated page/modal to review the final draft of the invoice before printing.
- **PDF Export**: Option to save the final invoice as a PDF.
- **Responsive Design**: Styled with Bootstrap for mobile and desktop views.


## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/sohailtahir5858/generate-invoice-react.git
    cd invoice-generator
    ```

2. **Install Dependencies**:
    ```bash
    npm install
    ```

3. **Run the Development Server**:
    ```bash
    npm start
    ```
    The server runs on `http://localhost:3000`.

## Available Scripts

- **`npm start`**: Runs the app in development mode.
- **`npm test`**: Launches the test runner.
- **`npm run build`**: Builds the app for production.
- **`npm run eject`**: Removes the single build dependency.

## Usage

1. **Add Billing Details**: Enter customer billing information on the checkout page.
2. **Manage Cart Items**: Add, update, or remove items, set quantity, and apply discounts.
3. **Review Invoice**: Review the draft on the preview page or in a modal.
4. **Print or Save as PDF**: Generate and save the final invoice as a PDF.

## Technologies & Packages Used

- **React**: For building the UI components and managing the state.
- **Bootstrap**: For responsive styling and layout.
- **File Saver** (`file-saver`): For saving the generated PDF invoice.
- **html2canvas**: To capture the invoice area as a canvas.
- **jsPDF**: To convert the HTML content to PDF format.
- **React Icons**: For adding icons to buttons and UI elements.
- **React Bootstrap**: For Bootstrap components in React.

## Packages and Dependencies

```json
"dependencies": {
  "bootstrap": "^5.1.0",
  "file-saver": "^2.0.5",
  "html2canvas": "^1.3.2",
  "jspdf": "^2.3.1",
  "react": "^17.0.2",
  "react-bootstrap": "^2.0.0-beta.6",
  "react-dom": "^17.0.2",
  "react-icons": "^4.2.0",
  "react-scripts": "4.0.3"
}
