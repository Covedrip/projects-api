WHAT THE API DOES
The API saves projects to the db based on user types (0, 1) as well as viewing


INSTALL DEPENDENCIES
npm install

Protected information for the database, admin and jwt token are in the .env

Set up database and admin
npx sequelize db:migrate
npx sequelize db:seed:all

API Routes

Auth Routes (/api/auth)
POST /signup - Register a new user
POST /login - Authenticate and get a JWT token

User Routes (/api/users)
GET / - Get all users


Project Routes (/api/projects)
POST / - Create a new projects
GET / - Get all projects
PATCH /:id - Update a project
DELETE /:id - Delete a project