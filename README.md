# Tax Loss Harvesting Tool

# Tax Loss Harvesting Tool - KoinX Frontend Intern Assignment

## Overview

This React application implements a Tax Loss Harvesting tool as part of the KoinX Frontend Intern Assignment. It fetches mock data for capital gains and crypto holdings to allow users to simulate the effects of selling assets at a loss to offset capital gains, potentially reducing their tax liability. The interface provides a clear view of pre-harvesting and after-harvesting capital gains, updating dynamically based on user selections in the holdings table.

## Working Demo

[Tax\_Loss\_Harvesting\_Demo.mp4](https://github.com/ashokccbp/Tax-Loss-Harvesting-/blob/main/Tax_Loss_Harvesting_Demo.mp4)

## Deployed Link

[https://tax-loss-harvesting-henna.vercel.app/](https://tax-loss-harvesting-henna.vercel.app/)

## GitHub Repository

[https://github.com/ashokccbp/Tax-Loss-Harvesting-.git](https://github.com/ashokccbp/Tax-Loss-Harvesting-.git)

## Key Features

* **Capital Gains Overview:** Displays a summary of capital gains (short-term and long-term) before and after simulating tax loss harvesting. This includes profits, losses, net capital gains, and realised capital gains.
* **Interactive Holdings Table:** Presents a detailed list of crypto holdings, including their current price, average buy price, short-term gain/loss, and long-term gain/loss. Users can select individual holdings using checkboxes.
* **Real-time Updates:** The "After Harvesting" capital gains section updates in real-time as users select or deselect holdings in the table.
* **Potential Savings Indicator:** If the simulated harvesting leads to a reduction in realised capital gains, a message indicating the potential tax saving is displayed.
* **Select All Functionality:** The holdings table includes a "Select All" checkbox for easy selection/deselection of all holdings.
* **Responsive Layout:** The application is designed to be responsive and adaptable to various screen sizes, ensuring a consistent user experience across devices.

## Tech Stack

* **React:** For building the user interface and managing components.
* **Styled Components:** Used for styling components in a modular and maintainable way.
* **JavaScript:** The primary programming language.
* **Mock API:** Implemented using Promises within the React application to simulate data fetching for capital gains and holdings.

## Setup Instructions

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/ashokccbp/Tax-Loss-Harvesting-.git](https://github.com/ashokccbp/Tax-Loss-Harvesting-.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd Tax-Loss-Harvesting-
    ```
3.  **Install dependencies:**
    ```bash
    npm install
    # or
    yarn install
    ```
4.  **Start the application:**
    ```bash
    npm start
    # or
    yarn start
    ```
    Open your web browser and go to `http://localhost:3000` to view the application.

## Screenshots

*(Please add screenshots of the application's main sections here. This will greatly enhance the README.)*

## API Simulation

The application simulates API calls to fetch the holdings data and capital gains data. The responses used for this simulation are based on the dummy responses provided in the assignment description and are managed within the React application using Promises.

## State Management

The application primarily uses React's built-in `useState` and `useEffect` hooks for managing the component state and handling side effects, such as updating the "After Harvesting" calculations based on user selections.

## Component Structure (Brief Overview)

*(You can add a brief overview of your main components here if you like, e.g.:)*

* `CapitalGainsCard`: Displays the "Pre-Harvesting" and "After Harvesting" capital gains information.
* `HoldingsTable`: Renders the list of crypto holdings with selection checkboxes.
* Each row in the table might be a separate component (`HoldingRow`).

## Bonus Features Implemented

* ✅ **Mobile Responsiveness:** The layout adapts to different screen sizes.
* ✅ **Clean, Reusable Components:** The application is built with modular and reusable React components.
* ✅ **Proper State Management:** Utilizes `useState` and `useEffect` effectively.
* ✅ **Visual Feedback for Selections:** Checkboxes clearly indicate selected holdings.

## Potential Future Enhancements

*(Optional: You can include ideas for future improvements)*

* Implement sorting and filtering for the holdings table.
* Add more detailed information for each holding.
* Integrate with a real API for live data.

## Contact

[G Ashok Kumar Reddy/GitHub Profile link 
; https://github.com/ashokccbp]

---

How does this revised version look to you? Is there anything specific you'd like to change or add?


https://github.com/ashokccbp


