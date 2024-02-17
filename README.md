**Steps for Testing:**

**Step 1: Install Dependencies**
   - Navigate to the project directory and run `npm install` to install all required dependencies.

**Step 2: Start the Server:**
   - Run `npm start` or `nodemon app.js` in the project directory to start the server.

**Step 3: Open Postman:**
   - Launch the Postman application.

**Step 4: Test Endpoints:**

   - **Login:**
     - Method: POST
     - URL: `http://localhost:3000/auth/login`
     - Body (JSON): `{"username": "sushanth", "password": "test1"}`

   - **Register:**
     - Method: POST
     - URL: `http://localhost:3000/auth/register`
     - Body (JSON): `{"username": "sushanths", "password": "hi"}`

   - **Create a New Blog:**
     - Method: POST
     - URL: `http://localhost:3000/blogs`
     - Body (JSON): `{"authorId":1,"title": "New Blog", "content": "Lorem ipsum..."}`

   - **Retrieve All Blogs:**
     - Method: GET
     - URL: `http://localhost:3000/blogs`

   - **Retrieve Blog by Author ID:**
     - Method: GET
     - URL: `http://localhost:3000/blogs/{authorId}`