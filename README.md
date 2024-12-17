# Nearby Ambulances and Doctors
This project provides a RESTful API for managing doctors and ambulances. It includes basic CRUD (Create, Read, Update, Delete) operations, as well as pagination and filtering functionality.

# Features

1. Role-Based Access Control:

   .Admins can perform Add, Edit, and Delete operations.
   .Users have a restricted view-only mode.


2. Dynamic Filtering:

    . Filter data using the Location Selector Dropdown.


3. CRUD Operations:

     . Admins can perform Create, Read, Update, and Delete operations.


4. Responsive UI:

    . The layout is optimized for desktop and mobile screens.


5. Session Management:

    . Admin permissions persist during the session until logout.



# Technologies Used

# Frontend:

. React
. TypeScript
. Vite
. Tailwind CSS


# Backend:

Node.js
Express.js
MongoDB
Mongoose



# Frontend (to execute frontend code )
Available Scripts

# Install dependencies:
  1. npm install


# Start the development server:
1. npm run dev

# To access the application on the server, use the IP address: 52.11.158.58

# Folder Structure
Copysrc/
├── assets/     # Static assets like images or styles
├── components/ # Reusable React components
├── hooks/      # Custom React hooks
├── pages/      # Page components
├── customUi/   # Custom UI components
├── services/   # Services components
├── utils/      # Helper functions or utilities
├── App.tsx     # Root component
├── main.tsx    # Entry point
└── vite-env.d.ts # Vite environment types


# Backend (to execute backend code)
# Install dependencies
  1. npm install
# Start the development server
 1. npm run dev


# API Endpoints 
# Doctors

1. POST /api/doctors: Create a new doctor.
2. GET /api/doctors?page=1&limit=10&location=: List all doctors with pagination and filtering by location.
3. PUT /api/doctors/:id: Update an existing doctor by ID.
4. DELETE /api/doctors/:id: Delete a doctor by ID.

# Ambulances

1. POST /api/ambulances: Create a new ambulance.
2. GET /api/ambulances?page=1&limit=10&location=: List all ambulances with pagination and filtering by location.
3. PUT /api/ambulances/:id: Update an existing ambulance by ID.
4. DELETE /api/ambulances/:id: Delete an ambulance by ID.

# Locations
1.GET /api/location/:type: Get the location data for either doctors or ambulances. Replace :type with either doctor or ambulance.
e.g /api/location/ambulance
e.g /api/location/doctor
