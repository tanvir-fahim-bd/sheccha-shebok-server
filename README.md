# Sheccha Shebok – Volunteer & Social Welfare Platform

**Sheccha Shebok** is a volunteer management and social welfare platform that connects people with volunteering opportunities and charitable events. Users can explore events, contribute donations, register as volunteers, and manage their activities through personalized dashboards.

The platform also provides an administrative dashboard for managing events, volunteers, notices, and platform activities.

## 🌐 Live Project

- **Live Website:** https://sheccha-shebok.netlify.app/
- **Live API:** https://sheccha-shebok-server.onrender.com/
- **Client Repository:** https://github.com/TanvirFahimBD/sheccha-shebok-client

---

## 📸 Project Screenshots

<!-- Add your project screenshots here -->

| Home Page | Dashboard |
|:---:|:---:|
| ![Home Page](./screenshots/home.png) | ![Dashboard](./screenshots/dashboard.png) |

| Events | Event Details |
|:---:|:---:|
| ![Events](./screenshots/events.png) | ![Event Details](./screenshots/event-details.png) |

---

## ✨ Key Features

### 👤 User Features
- Browse and search available volunteering events.
- Donate to support social welfare activities.
- Access a personalized dashboard.
- View and update personal profile information.

### 🤝 Volunteer Features
- Browse and search volunteering opportunities.
- Register for available events.
- View and manage registered events.
- Receive important event notices.
- Add and view personal reviews.
- Update personal profile information.

### 🛡️ Admin Features
- Create and publish new events.
- Update and delete existing events.
- Create and manage event notices.
- Assign volunteer roles.
- Remove volunteers.
- Assign new admin roles.
- Manage personal profile information.

### 🔒 Additional Features
- Firebase Authentication.
- Role-based access for users, volunteers, and admins.
- Protected dashboard routes.
- Custom 404 page for invalid routes.
- Additional features and improvements are ongoing.

---

## 🛠️ Technologies Used

### Frontend
- React.js – Building reusable UI components and interactive interfaces.
- React Router – Client-side routing and navigation.
- Firebase Authentication – User authentication and account management.

### Backend
- Node.js – Server-side JavaScript runtime.
- Express.js – REST API development and backend routing.
- MongoDB – Storing and managing application data.

### Deployment & Hosting
- Netlify – Frontend deployment and hosting.
- Render – Backend API hosting.
- Railway – Used as a deployment platform during development (verify its exact role in the final project).

---

## 📦 Dependencies

### Main Dependencies

**Frontend**
- react
- react-dom
- react-router-dom
- firebase

**Backend**
- express
- mongodb
- cors
- dotenv

> Note: This is a preliminary dependency list based on the technologies and architecture described. Check the client and server `package.json` files and update this section with the exact dependencies and versions used in the project.

---

## ⚙️ Run Locally

Follow these steps to run the project on your local machine.

### Prerequisites

Make sure you have installed:

- Node.js (LTS recommended)
- npm
- MongoDB account or local MongoDB server
- Firebase project with Authentication configured
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/TanvirFahimBD/sheccha-shebok-client.git

cd sheccha-shebok-client
```

### 2. Install Frontend Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the frontend root directory.

```env
VITE_API_URL=http://localhost:5000

VITE_apiKey=your_firebase_api_key
VITE_authDomain=your_firebase_auth_domain
VITE_projectId=your_firebase_project_id
VITE_storageBucket=your_firebase_storage_bucket
VITE_messagingSenderId=your_firebase_sender_id
VITE_appId=your_firebase_app_id
```

Adjust variable names according to your actual Firebase configuration and API implementation.

### 4. Start the Frontend

```bash
npm run dev
```

The frontend should now be available at:

```text
http://localhost:5173
```

### 5. Set Up the Backend

Clone your server repository into a separate directory.

```bash
git clone YOUR_SERVER_REPOSITORY_URL

cd YOUR_SERVER_DIRECTORY
```

Install backend dependencies:

```bash
npm install
```

Create a `.env` file in the backend root directory.

```env
PORT=5000
DB_USER=your_mongodb_username
DB_PASS=your_mongodb_password
```

Add any other environment variables required by your backend implementation.

### 6. Start the Backend

```bash
npm start
```

If your backend uses a different development script, use the corresponding command from its `package.json`.

Backend API:

```text
http://localhost:5000
```

---

## 🧠 Technology Choices & Why I Used Them

| Technology | Reason for Choosing |
|---|---|
| React.js | Component-based architecture and reusable UI |
| React Router | Efficient client-side navigation |
| Firebase Authentication | Secure and convenient user authentication |
| Node.js | JavaScript-based backend development |
| Express.js | Lightweight REST API development |
| MongoDB | Flexible document-oriented data storage |
| Netlify | Simple frontend deployment |
| Render | Backend API hosting |

---

## 🚧 Challenges Faced During Development

Some important engineering areas addressed while developing this platform:

- **Role-Based Access Management:** Designing different dashboard experiences and permissions for users, volunteers, and admins.
- **Authentication & Authorization:** Integrating Firebase Authentication with protected application routes and role-based access.
- **Event Management:** Implementing event creation, updating, deletion, and volunteer registration workflows.
- **Data Management:** Managing user information, event registrations, reviews, donations, and notices.
- **Frontend & Backend Integration:** Connecting React components with Express REST APIs and handling asynchronous requests.
- **Deployment:** Configuring frontend and backend environments to communicate with each other in production.

---

## 💡 Problems Solved

- Simplified the process of discovering volunteering opportunities.
- Provided a centralized platform for volunteer event registration.
- Made it easier for administrators to manage events and volunteer roles.
- Enabled users to manage their own profiles and activities.
- Improved communication through event notices.
- Created a structured way for volunteers to share feedback through reviews.

---

## 🔮 Future Improvements

- Online payment gateway integration for donations.
- Advanced event filtering and searching.
- Email and real-time notifications.
- Improved analytics and reporting for administrators.
- More volunteer engagement and management features.
- Additional security and performance optimizations.

---

## 👨‍💻 Developer

**Tanvir Hossain Fahim**  
Software Engineer | Full-Stack Developer

- **GitHub:** https://github.com/TanvirFahimBD
- **LinkedIn:** https://www.linkedin.com/in/tanvir-fahim/
- **Portfolio:** https://tanvir-fahim-bd.netlify.app/

---

⭐ If you find this project interesting, consider giving it a star!

**Built with ❤️ to encourage volunteering and social welfare.**
