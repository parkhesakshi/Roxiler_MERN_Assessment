# MERN Stack Dashboard

This project is a dynamic UI dashboard built using the MERN stack (MongoDB, Express, React, Node.js) and Tailwind CSS. It includes functionalities for viewing transactions, statistics, and visualizing data with charts.

## Project Overview

The dashboard provides:
- **Transaction List**: A paginated and searchable list of transactions.
- **Statistics**: Total sales, number of sold items, and unsold items for a selected month.
- **Bar Chart**: Visualization of transaction price ranges.
- **Pie Chart**: Distribution of items across different categories.

## Features

- **Backend**:
  - Initialize database with seed data.
  - Fetch transactions with search and pagination.
  - Retrieve monthly statistics.
  - Generate bar and pie chart data.
  - Combine and serve data from multiple APIs.

- **Frontend**:
  - Dynamic UI dashboard with Tailwind CSS.
  - Components for transactions, statistics, bar chart, and pie chart.
  - Navigation to switch between different views.

## Prerequisites

- Node.js and npm
- MongoDB
- Vite (for frontend setup)

## Setup

### Backend

1. **Clone the repository:**
    ```bash
    git clone https://github.com/parkhesakshi/Roxiler_MERN_Assessment.git
    cd mern-dashboard/backend
    ```

2. **Install dependencies:**
    ```bash
    npm install
    ```

3. **Create a `.env` file** in the `backend` directory and add the following:
    ```env
    DATA_URL=YOUR_API
    MONGO_URI=YPUR_DATABASE_URL
    PORT=PORT
    ```

4. **Start the backend server:**
    ```bash
    npm start
    ```

### Frontend

1. **Navigate to the frontend directory:**
    ```bash
    cd ../frontend
    ```

2. **Install dependencies:**
    ```bash
    npm install
    ```

3. **Start the frontend development server:**
    ```bash
    npm run dev
    ```

## Deployment

To deploy the project, build the frontend and deploy both backend and frontend to a cloud service like Heroku, Netlify, or Vercel.

1. **Build the frontend:**
    ```bash
    npm run build
    ```

2. **Deploy the backend** and **frontend** to your chosen platform.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## Contact

For any questions or feedback, please contact [sakshiparkhe56@gmail.com](mailto:sakshiparkhe56@gmail.com).

---

Enjoy building and using your dynamic MERN stack dashboard!
