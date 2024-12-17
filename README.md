# ResQ_Nearby
git clone <repository_url>


cd "NEARBY AMBULANCES AND DOCTOR"


npm install


npm run dev

Usage
This project provides a RESTful API for managing doctors and ambulances. You can perform the following operations:

Create a new doctor or ambulance
Update an existing doctor or ambulance
Delete a doctor or ambulance
List all doctors or ambulances with pagination and filtering
API Endpoints
Doctors
POST /api/doctors
Create a new doctor.

GET /api/doctors?page=1&limit=10&location=
List all doctors with pagination and filtering by location. Parameters:

page: The page number (default: 1)
limit: The number of doctors per page (default: 10)
location: Filter by doctor location (optional).
PUT /api/doctors/:id
Update an existing doctor by ID.

DELETE /api/doctors/:id
Delete a doctor by ID.

Ambulances
POST /api/ambulances
Create a new ambulance.

GET /api/ambulances?page=1&limit=10&location=
List all ambulances with pagination and filtering by location. Parameters:

page: The page number (default: 1)
limit: The number of ambulances per page (default: 10)
location: Filter by ambulance location (optional).
PUT /api/ambulances/:id
Update an existing ambulance by ID.

DELETE /api/ambulances/:id
Delete an ambulance by ID.

Location
GET /api/location/:type
Get the location data for either doctors or ambulances. Replace :type with either doctor or ambulance.
