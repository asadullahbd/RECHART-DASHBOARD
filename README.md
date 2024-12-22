DEMO: https://rechart-dashboard.vercel.app

Recharts Dashboard
This project is a React-based dashboard showcasing various chart types using the Recharts library. It also utilizes React-Bootstrap for layout and styling. The application demonstrates different chart types such as Line, Bar, Pie, Area, Composed, Scatter, Radar, and Radial Bar Charts.

Features
Recharts Integration: Implements various charts provided by the Recharts library.
Responsive Design: All charts are fully responsive.
React-Bootstrap UI: Clean and structured layout using React-Bootstrap components.
Easy to Customize: Modular components for each chart type.
Prerequisites
Before running the project, ensure you have the following installed:

Node.js (v16 or higher recommended)
npm or yarn (npm v7 or higher)
Installation
Clone the repository:
git clone https://github.com/asadullahbd/RECHART-DASHBOARD.git

Navigate to the project directory:
cd recharts-dashboard

Install dependencies:
npm install

Usage
Development Server
Run the development server:
npm run dev

The app will be available at http://localhost:5173.

Build for Production
Create a production build:
npm run build

Preview Production Build
Preview the production build locally:
npm run preview

Charts Included
Line Chart
Bar Chart
Pie Chart
Area Chart
Composed Chart
Scatter Chart
Radar Chart
Radial Bar Chart
Each chart is implemented as a reusable React component.

Technologies Used
React: Frontend framework for building the UI.
Recharts: Charting library for creating beautiful and responsive charts.
React-Bootstrap: Styling and layout components.
Vite: Development environment and bundler for fast builds.
How to Add New Charts
Create a new React component in the components directory.
Use Recharts components (e.g., LineChart, BarChart, etc.) to build the chart.
Import and use the component in the RechartsPage file within a Card.
Dependencies
Runtime Dependencies

react: ^18.3.1
react-dom: ^18.3.1
react-bootstrap: ^2.10.7
recharts: ^2.15.0
bootstrap: ^5.3.3
Development Dependencies

vite: ^6.0.3
eslint: ^9.17.0
Plugins for React and ESLint


Author
Created by Asad.