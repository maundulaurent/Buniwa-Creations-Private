COCO Technology eCommerce

COCO Technology is a Next.js and Node.js full-stack e-commerce platform with a fully functional admin panel. This open-source application is responsive and manually tested, making it an ideal template or boilerplate for your next project. Download it for free and customize it to meet your needs.

Key Features
Fully Functional Admin Panel
Responsive Design
Open-Source
SEO-Friendly
Scalable and Performant
Why Next.js for eCommerce?
Next.js is an excellent choice for developing custom eCommerce solutions due to its performance, SEO-friendliness, ease of development and deployment, superior developer experience, and scalability.

Instructions for Running the Application
Prerequisites
Install Node.js and npm: Ensure you have Node.js and npm installed on your computer.
Install MySQL: You need MySQL for database management.
Optional: Install HeidiSQL, a beginner-friendly database management tool.
Setup Steps
Download and Extract the Project

Download the COCO Technology project and extract the files.
Configure Environment Variables

Create a .env file in the root directory and the server directory with the following content:
plaintext
Copy code
DATABASE_URL="mysql://<username>:<password>@localhost:3306/coco_technology"
NEXTAUTH_SECRET=12D16C923BA17672F89B18C1DB22A
NEXTAUTH_URL=http://localhost:3000
Install Dependencies

Open your terminal in the root project folder and run:
bash
Copy code
npm install
Set Up the Backend

Navigate to the server folder and install backend dependencies:
bash
Copy code
cd server
npm install
Run Prisma Migration

In the server folder, execute the migration:
bash
Copy code
npx prisma migrate dev
Insert Demo Data

Navigate to the server/utils folder and run the script:
bash
Copy code
cd utils
node insertDemoData.js
Start the Backend Server

Go back to the server folder and start the backend:
bash
Copy code
cd ..
node app.js
Start the Frontend

Open another terminal, navigate to the root project folder, and run:
bash
Copy code
npm run dev
View the Application

Open your browser and visit: http://localhost:3000
Screenshots
(Add screenshots here)