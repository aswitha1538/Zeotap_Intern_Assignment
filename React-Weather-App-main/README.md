Build a weather dashboard that provides current weather information and forecasts for different cities. The application should allow users to search for cities and display the current weather and a 7-day forecast. Use React+Vite for the front-end, and a weather API  OpenWeatherMap for data.
# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

<hr>

<h1>Installation Instructions</h1>

## Project Structure
 
- 'public/' ('vite.svg'): Contains static assets like images, used by the app (e.g., Vite logo).
- 'src/' ('main.jsx', 'index.css', 'App.jsx'): Holds source code ('main.jsx' initializes the app, 'App.jsx' defines the main component, 'index.css' contains global styles).
- 'index.html': The HTML template where React injects the app content.
- 'package.json': Lists project dependencies and scripts for development and build processes.
- 'vite.config.js': Vite configuration file for customizing build and development behavior.
- 'node_modules/': Directory where npm installs all the project dependencies.
- '.gitignore': Specifies files and directories (like 'node_modules/') to be ignored by Git.


<h2>1. Clone the Repository</h2>

<p>To get a local copy of the project, clone the repository</p>

    git clone https://github.com/aswitha1538/Zeotap_Intern_Assignment.git
    cd React-Weather-App
<h2>2. Install Dependencies</h2>

<p>Navigate to the project root and install the necessary dependencies</p>

    npm install

<h2>3. Set Up Environment Variables</h2>

<p>Create an .env file in the root directory to store your API key</p>

    REACT_APP_WEATHER_API_KEY=your_openweather_api_key

<h2>4. Run the Application</h2>

<p>To start the application in development mode</p>

    npm run dev

The app will be available at http://localhost:3000.



