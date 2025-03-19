
  Hotel Project
 
  Welcome to the **Hotel Project**, a modern web application for managing and browsing apartments for rent.
  This project is built using **React**, **Redux**, and **Node.js**, providing a seamless user experience for both advertisers and customers.
 
  ---
 
  ## Table of Contents
 
  1. Features
  2. Technologies Used
  3. Project Structure
  4. Installation
  5. Usage
  6. Available Scripts
  7. Screenshots
  8. Contributing
  9. License
 
  ---
 
  ## Features
 
  - **User Registration and Login**: Secure user authentication with form validation.
  - **Apartment Management**: Add, update, and delete apartments with detailed information.
  - **Filtering and Sorting**: Filter apartments by city, category, price, and number of beds.
  - **Advertiser Dashboard**: Manage cities, categories, and apartments.
  - **Responsive Design**: Fully responsive UI for desktop and mobile devices.
  - **Error Handling**: User-friendly error messages and alerts using SweetAlert.
 
  ---
 
  ## Technologies Used
 
  - **Frontend**:
    - React (v18.3.1)
    - Redux Toolkit
    - React Router DOM
    - Axios
    - SweetAlert
    - CSS Modules
 
  - **Backend**:
    - Node.js
    - Express.js
    - MongoDB (via Mongoose)
 
  - **Other Tools**:
    - Multer (for file uploads)
    - Buffer (for image handling)
    - Jest (for testing)
 
  ---
 
  ## Project Structure
 
  hotel-project/
  ├── public/                # Static assets
  ├── src/
  │   ├── hotels/            # Main application components
  │   │   ├── Redux/         # Redux store and actions
  │   │   ├── styles.css     # Global styles
  │   │   ├── api.js         # API calls
  │   │   ├── components/    # Reusable components
  │   │   ├── pages/         # Page components
  │   ├── App.js             # Main application entry point
  │   ├── index.js           # React DOM rendering
  ├── package.json           # Project dependencies and scripts
  ├── README.md              # Project documentation
 
  ---
 
  ## Installation
 
  To run this project locally, follow these steps:
 
  1. Clone the repository:
     git clone https://github.com/sari-Yona/ApartmentProject.client
     cd hotel-project
 
  2. Install dependencies:
     npm install
 
  3. Start the development server:
     npm start
 
  4. Open your browser and navigate to:
     http://localhost:3000
 
  ---
 
  ## Usage
 
  ### Advertisers
  - Register and log in to manage your apartments.
  - Add new apartments with details like name, description, city, category, price, and images.
  - Update or delete existing apartments.
 
  ### Customers
  - Browse available apartments.
  - Filter apartments by city, category, price range, or number of beds.
  - View detailed information about each apartment.
 
  ---
 
  ## Available Scripts
 
  In the project directory, you can run:
 
  ### npm start
  Runs the app in development mode. Open http://localhost:3000 to view it in your browser.
 
  ### npm test
  Launches the test runner in interactive watch mode.
 
  ### npm run build
  Builds the app for production to the build folder.
 
 ### npm run eject
  Ejects the app configuration. **Note: This is irreversible.**
 
  ---
 
  ## Screenshots
 
  ### Home Page
 ![Home Page](public/screenshots/home-page.png)
  ### Advertiser Dashboard
  ![Advertiser Dashboard](public/screenshots/advertiser-dashboard.png)
 
  ### Apartment Details
  ![Apartment Details](public/screenshots/apartment-details.png)
 
  ---
 
  ## Contributing
 
  We welcome contributions! To contribute:
 
  1. Fork the repository.
  2. Create a new branch (git checkout -b feature/your-feature).
  3. Commit your changes (git commit -m 'Add your feature').
  4. Push to the branch (git push origin feature/your-feature).
  5. Open a pull request.
 
  ---
 
  ## License
 
  This project is licensed under the MIT License. See the LICENSE file for details.
 
  ---
 
  ## Contact
 
  For any questions or feedback, feel free to reach out:
 
  - **Email**: your-email@example.com
  - **GitHub**: https://github.com/sari-Yona
 
  ---
