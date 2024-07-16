# MERN Stack Dashboard

This project is a MERN stack application dashboard that provides various charts and visualizations using `react-chartjs-2` and `chart.js`. It leverages Chakra UI for styling and layout.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Dependencies](#dependencies)
- [Features](#features)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## Installation

### Prerequisites

Ensure you have the following installed:
- Node.js
- npm or yarn
- MongoDB

### Frontend Setup

1. Navigate to the `client` directory:
   ```sh
   cd client
   ```

2. Install the dependencies:
   ```sh
   npm install
   ```

3. Start the development server:
   ```sh
   npm start
   ```

### Backend Setup

1. Navigate to the server directory:
   ```sh
   cd server
   ```

2. Install the dependencies:
   ```sh
   npm install
   ```

3. Update the MongoDB URI in the `.env` file:
   ```env
   MONGO_URI=your_mongo_uri_here
   ```

4. Start the server:
   ```sh
   node src/app.js
   ```

## Configuration

Make sure to update the `.env` file in the server directory with your MongoDB URI and any other necessary environment variables.

## Dependencies

The main dependencies used in this project are:

- `@chakra-ui/icons`: ^2.1.0
- `@chakra-ui/react`: ^2.8.0
- `@emotion/react`: ^11.11.1
- `@emotion/styled`: ^11.11.0
- `@testing-library/jest-dom`: ^5.17.0
- `@testing-library/react`: ^13.4.0
- `@testing-library/user-event`: ^13.5.0
- `axios`: ^1.4.0
- `chart.js`: ^4.3.3
- `chartjs-plugin-datalabels`: ^2.2.0
- `chartjs-plugin-gradient`: ^0.6.1
- `react`: ^18.2.0
- `react-chartjs-2`: ^5.2.0

## Features

- Interactive charts and graphs using Chart.js and react-chartjs-2
- Responsive design with Chakra UI
- Integration with MongoDB for data storage
- RESTful API for data fetching



## Contributing

Contributions are welcome! Please fork this repository and submit pull requests.

