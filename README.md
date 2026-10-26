SkillSwap — Skill Sharing Platform

SkillSwap is a full-stack web application built with Laravel that connects people who want to teach skills with people who want to learn them. Users can share their knowledge, discover new skills, book learning sessions, and communicate with other users.

🚀 Features

- User Authentication — User registration, login, and logout.
- Skill Management — Browse and add skills.
- Teach & Learn — Manage skills users can teach or want to learn.
- Booking System — Create booking requests and manage booking statuses.
- Messaging System — Send and receive messages between users.
- Message Management — Edit sent messages and delete messages for yourself or everyone.
- User Profiles — View other users' profiles.
- Reviews & Ratings — Submit reviews for completed learning sessions.
- Unread Message Tracking — Track unread messages.

Note: Some features may still be under development or testing.

🛠️ Tech Stack

- Backend: PHP, Laravel
- Database: MySQL
- Frontend: HTML, CSS, JavaScript, Blade Templates
- Development Tools: Visual Studio Code, Composer, Git, MySQL Workbench

⚙️ Installation & Setup

Prerequisites

Make sure you have installed:

- PHP
- Composer
- MySQL
- Node.js and npm
- Git

1. Clone the repository

git clone https://github.com/YOUR-USERNAME/skillswap.git
cd skillswap

2. Install dependencies

composer install
npm install

3. Configure the environment

Copy the example environment file:

copy .env.example .env

Generate the application key:

php artisan key:generate

4. Configure the database

Create a MySQL database named "skillswap".

Update the database settings in your ".env" file:

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=skillswap
DB_USERNAME=your_database_username
DB_PASSWORD=your_database_password

Use your own local database credentials. Never upload your ".env" file or passwords to GitHub.

5. Run database migrations

php artisan migrate

6. Start the development server

php artisan serve

Open the application at:

http://127.0.0.1:8000

If frontend assets are required, start the Vite development server in another terminal:

npm run dev

📂 Project Structure

skillswap/
├── app/
│ ├── Http/Controllers/
│ └── Models/
├── database/
│ └── migrations/
├── resources/
│ └── views/
│ ├── auth/
│ ├── bookings/
│ ├── messages/
│ ├── profiles/
│ └── skills/
├── routes/
│ └── web.php
├── public/
├── .env.example
└── README.md

🔐 Security

- Authentication-protected routes.
- Server-side validation for user input.
- Authorization checks for message editing and deletion.
- Environment variables for local configuration and credentials.

🧪 Project Status

Status: In Development

SkillSwap is an ongoing learning project. Features are being implemented and tested incrementally. The README and setup instructions may change as development progresses.

🎯 Future Improvements

- Improve the responsive user interface.
- Add enhanced messaging and notifications.
- Improve booking workflows.
- Add automated tests.
- Deploy the application online.

👩‍💻 Author

Tanishka Patil

B.Sc. Computer Science and Technology Graduate

GitHub: "YOUR-GITHUB-USERNAME" (https://github.com/YOUR-GITHUB-USERNAME)

---

⭐ If you find this project interesting, feel free to explore the code and follow its development.
