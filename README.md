
📚 StudyNotion – An EdTech Platform
StudyNotion is a full-stack edtech web application that provides an online platform for students to learn from various courses. It supports both students and instructors with features like authentication, course management, payment integration, and more.

🚀 Features
👨‍🏫 Instructor Dashboard to create and manage courses

🧑‍🎓 Student Dashboard to enroll and learn

📚 Upload video lectures, add quizzes, and descriptions

💳 Secure payments with Razorpay integration

📩 Email verification via OTP (nodemailer)

🌙 Dark & light mode toggle

🔐 JWT-based Authentication

🖼️ Dynamic course thumbnails and preview

🎯 Progress tracking for enrolled users

🛠️ Tech Stack
Frontend:

React.js

Tailwind CSS

Redux Toolkit

React Router DOM

Backend:

Node.js

Express.js

MongoDB

Mongoose

Cloudinary (for media)

Razorpay

Nodemailer

🔧 Installation
bash
Copy
Edit
# Clone the repository
git clone https://github.com/shloksps/Study-notion.git

# Move into the project folder
cd Study-notion

# Install server dependencies
cd backend
npm install

# Install client dependencies
cd ../frontend
npm install

# Start backend
npm run dev

# Start frontend
npm start
📝 .env Setup
Create .env files in both backend/ and frontend/ directories.

Backend .env
ini
Copy
Edit
PORT=4000
MONGODB_URL=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
RAZORPAY_KEY=your_key
RAZORPAY_SECRET=your_secret
MAIL_HOST=smtp_service
MAIL_USER=email@example.com
MAIL_PASS=email_password
Frontend .env
ini
Copy
Edit
REACT_APP_BASE_URL=http://localhost:4000

This is a starter pack for creating React projects with Tailwind CSS configured. It uses React version **18.2** and Tailwind CSS version **3.2**.

## Usage

This starter pack includes a basic setup for using **Tailwind CSS with React**. To start building your own components and styles, follow these steps:

1. Clone the repository to your local machine.
    ```sh
    git clone https://github.com/thepranaygupta/react-tailwind-css-starter-pack.git
    ```

1. Install the required packages.
    ```sh
    cd react-tailwind-css-starter-pack
    npm install
    ```

1. Start the development server.
    ```sh
    npm start
    ```
1. Open the project in your browser at [`http://localhost:3000`](http://localhost:3000) to view your project.
1. Create your React components and add your styles using Tailwind classes. You can also create new CSS files and import them into your components.

The project is set up to use `postcss-cli` to process your CSS files. You can add your own `tailwind.config.js` file to customize your Tailwind setup.

## Contributing

Contributions are welcome! If you have any suggestions or find any issues, please feel free to open an issue or a pull request.
