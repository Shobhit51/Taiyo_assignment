# Contact Management App with Charts and Maps 📊🗺️

This is a contact management app built using ReactJS, TypeScript, TailwindCSS, React Router v6, and React Query from the TanstackQuery library. The app allows you to manage your contacts and also provides interactive charts and maps to visualize COVID-19 data.



## Objective: Page Contacts  👥
### Features
-➕ Add new contacts using the provided form.
- 📋 Display a list of all added contacts.
- 👁️ Each contact has a button to view their details.
- ✏️ Edit and delete contacts functionality.
- 🔗 Redux is used to store the contact data.

## Objective: Page Charts and Maps 📈🗺️
### Features
The app features a simple dashboard with the following components:
- **Line Graph**: A line graph displaying the fluctuations in COVID-19 cases over time.
- **React Leaflet Map**: An interactive map with markers that indicate country-specific COVID-19 data. The markers display the country name, total number of active, recovered cases, and deaths as a popup.

## Data Sources  📊
The COVID-19 data is fetched from the following APIs:

- World-wide COVID-19 cases: `https://disease.sh/v3/covid-19/all`
- Country-specific COVID-19 cases: `https://disease.sh/v3/covid-19/countries`
- Historical COVID-19 graph data: `https://disease.sh/v3/covid-19/historical/all?lastdays=all`

## Technologies Used 🛠️
- React: JavaScript library for building user interfaces.
- TypeScript: Adds static typing to JavaScript to improve code quality.
- TailwindCSS: Utility-first CSS framework for styling.
- React Router v6: Handles navigation and routing within the app.
- React Query (TanstackQuery): Manages API calls and data fetching.
- Redux: State management for contact data.
- React Leaflet: Integrates Leaflet maps into the React app.
- React ChartJS 2: Library for creating interactive and visually appealing charts.


