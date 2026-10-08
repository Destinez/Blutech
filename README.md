
# Remote Front-End Software Engineer Test Project

> **Note:** This is a front-end take-home assessment I completed for Blutech Solutions LLC (Figma design → React/Vite, API-driven searchable product catalogue with Context state). It is not a production product.

## Blutech Solutions LLC

### Overview

This project is a test assignment for the Remote Front-End Software Engineer position at Blutech Solutions LLC. The main objectives are to implement a given UI design and integrate it with an API using API Context state management.

### Project Structure

- **UI Implementation:** The UI is implemented based on the provided Figma design with Vite ReactJS and reactstrap library.
- **API Integration:** Data is fetched from a provided API endpoint and rendered in a data table using fetch.
- **State Management:** API Context is used to manage the application state.

### Figma Design

The UI design is based on the provided Figma file:
[Blutech Solution Figma Design](https://www.figma.com/design/5YoDO1EKuVGMJK77g2CY43/Blutech-solution?node-id=425-359&t=fCesi5WRWJUPge5L-0)

### API Endpoint

The data is fetched from the following API endpoint:
[API Documentation](http://3.88.1.181:8000/docs)

- Endpoint: `http://3.88.1.181:8000/products/public/catalog`

### Features

- **Responsive Navigation Bar:** A top navigation bar with a search input and a user dropdown menu.
- **Search and Filter Modal:** A modal that opens upon clicking the search button, containing search and filter inputs.
- **Data Table:** Displays data fetched from the API in a structured table format.
- **API Context:** Manages state throughout the application.

### Setup Instructions

1. **Clone the repository**
   ```sh
   git clone https://github.com/Destinez/Blutech.git
   cd Blutech
   ```

2. **Install dependencies**
   ```sh
   npm install
   ```

3. **Start the development server**
   ```sh
   npm run dev
   ```

4. **Open** `http://localhost:5173/`

To create a production build: `npm run build` (output in `dist/`).


### Usage

- Navigate to the home page to view the product catalog on the datatable.
- Use the search bar and filter modal on the Nav bar to search and filter items.


## Authors

- [Obaro Destiny Udurie](https://www.github.com/destinez)

