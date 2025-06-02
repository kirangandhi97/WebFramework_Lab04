This is a Next.js project using TypeScript, Tailwind CSS, PostgreSQL, and NextAuth for authentication.

📦 Requirements
Node.js (v18 or higher recommended)

npm (v9 or higher)

PostgreSQL database

🚀 Getting Started
1. Clone the repository and navigate into the folder
bash
Copy
Edit
git clone <your-repo-url>
cd LAB03-WEB
2. Install dependencies
bash
Copy
Edit
npm install
3. Configure environment variables
Copy the example environment file and update it with your database and authentication credentials:

bash
Copy
Edit
cp .env.example .env
Edit .env with the required values.

4. Run the development server
bash
Copy
Edit
npm run dev
The app should now be running at http://localhost:3000

5. Build for production
bash
Copy
Edit
npm run build
npm start
🛠️ Scripts
npm run dev – Runs the app in development mode using Turbopack

npm run build – Compiles the app for production

npm start – Starts the production server

🧩 Tech Stack
Next.js

TypeScript

Tailwind CSS

PostgreSQL

NextAuth.js

bcrypt (for password hashing)

zod (for schema validation)

