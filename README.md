# Advanced API Analytics Dashboard

This project is a real-time analytics dashboard for tracking API usage, designed to provide in-depth insights into performance, trends, and user behavior. It leverages a modern tech stack to deliver a responsive and informative user experience.

## Features

-   **Real-Time Data:** The dashboard updates in real-time, displaying the latest API activity.
-   **Advanced Statistics:** Provides key metrics such as total requests, requests per minute, response time, success rate, and more.
-   **Interactive Charts:** Includes dynamic charts for visualizing request timelines, model usage, hourly patterns, and more.
-   **Customizable Filters:** Allows users to filter data by date range, model, and request type.
-   **Live Request Feed:** Displays a live feed of recent API requests.
-   **Responsive Design:** The dashboard is fully responsive and works well on various screen sizes.
-   **Glassmorphism UI:** Features a sleek, modern UI with a glassmorphism effect.

## Tech Stack

-   **HTML:** Structuring the dashboard layout.
-   **CSS (Tailwind CSS):** Styling the dashboard with a utility-first approach.
-   **JavaScript:** Implementing real-time updates and data handling.
-   **Chart.js:** Creating interactive and responsive charts.
-   **Luxon:** Handling date and time operations.
-   **D3.js:** For data manipulation.
-   **jQuery:**  For using the daterangepicker library.
-   **Moment.js:** Date handling for daterangepicker.
-   **Daterangepicker:** Selecting date ranges easily.
-   **EventSource API:**  Connecting to the backend for real-time updates.

## Setup

To get the dashboard running locally, follow these steps:

1.  **Clone the Repository:**
    ```bash
    git clone [repository-url]
    cd [repository-name]
    ```
2.  **Open `index.html`:** Open the `veLouOOacZkhPadsK.html` file (rename it to `index.html` or any name you want) directly in your web browser.

**Note:** This dashboard relies on an external EventSource feed for data. It may be necessary to configure this feed to point to your API backend. By default it connect to `https://text.pollinations.ai/feed` and uses `https://text-api.pollinations.ai/feed` as a fallback.

## Usage

### Data Customization
-   **Date Range Picker:** Use the date range picker to analyze data within a specific time frame.
-   **Model Filter:** Select a specific model to view usage patterns for that model or choose "All Models" to see all models
-   **Request Type Filter:** Select a specific request type (GET or POST) to filter the data, or "All Types" to display all data

### Exploring the Dashboard
-   **Advanced Stats:** View key performance indicators such as total requests, response times, and success rates.
-   **Charts:** Interact with the visualizations for a deeper understanding of your API's usage.
-   **Live Feed:** Monitor real-time API requests as they happen.

## How it Works

-   The dashboard fetches data from a real-time event stream using the EventSource API.
-   Data is processed in JavaScript and used to update the UI elements.
-   Chart.js is used to render interactive charts based on the processed data.
-   CSS is used to style the dashboard with a modern look using Tailwind CSS.

## Contributions

Contributions are welcome! If you have any ideas or find any bugs, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [License Name] License - see the [LICENSE.md](LICENSE.md) file for details.

## Contact
For any questions, feel free to reach out.
