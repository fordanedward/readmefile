# GC Capture / Gordon College CTF

Welcome to GC Capture, a platform where you can train, compete, and build your cybersecurity skills through fun and realistic CTF (Capture The Flag) challenges.

---

## Quick Start Guide

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/Project_Capture.git
   cd Project_Capture
   ```

2. **Install dependencies:**
   ```bash
   npm install
   npm install react-icons recharts tw-animate-css chart.js react-chartjs-2
   ```

3. **Start the app:**
   ```bash
   npm run dev
   ```
   The app will be accessible at: [http://localhost:5173](http://localhost:5173)

---

## How to Use the Application

### 1. Login

- Go to `/login`
- Enter your credentials to sign in as a user or admin

---

### 2. User Features

After logging in as a user, you can access the following:

- **Home Page** (`/`): Overview of the platform
- **Profile Page** (`/profile`): Update profile details, upload a profile picture, change password
- **User Statistics** (`/user-statistics`): View your progress and performance data
- **Challenges** (`/challenges`): Browse and solve CTF challenges by category

#### How to Solve a Challenge

1. Go to the Challenges page
2. Click a challenge to view its details
3. Read the description
4. Submit your solution (flag)
5. Receive immediate feedback and score update

---

### 3. Admin Features

If you're logged in as an admin, you can access the following (based on your assigned permissions):

| Feature                        | Route                        | Permission Required        |
|--------------------------------|------------------------------|----------------------------|
| Admin Dashboard                | `/admin/dashboard`           | Any admin                  |
| Manage Challenges              | `/admin/challenges`          | `canManageChallenges`      |
| Edit Specific Challenge        | `/admin/challenges/:id`      | `canManageChallenges`      |
| Events Management              | `/admin/events`              | `canManageEvents`          |
| View All Events                | `/admin/overall_events`      | Any admin                  |
| Student Management             | `/admin/students`            | `canManageUsers`           |
| View Statistics                | `/admin/statistics`          | Any admin                  |

> Note: Admins only see features they have permission to access. If you lack a required permission, you'll be redirected to an Unauthorized page.

#### How to Add a Challenge (for admins with `canManageChallenges`)

1. Go to `/admin/challenges`
2. Click the "Add Challenge" button
3. Fill in the challenge details (title, description, category, flag, etc.)
4. Click Save
5. The challenge will now be available to users in the Challenges section

---

## Navigating the App

- Use the sidebar or top navigation to move between pages
- All sections are clearly labeled (e.g., Dashboard, Profile, Challenges)
- Admins have additional menu options for managing content (based on permissions)
- Use "Refresh" buttons on dashboards to update data if needed

---

## Tips for New Users

- Start with easier challenges to build confidence
- Track your progress using the statistics page
- If you get stuck, try another challenge or review the description again
- Keep your profile updated for a better experience

---

## Contributing

Want to contribute to the project?

1. Fork this repository
2. Create a new branch
3. Make your changes
4. Commit with clear messages
5. Push and open a Pull Request

---

## 🛠️ Built With
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge\&logo=react\&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge\&logo=vite\&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge\&logo=tailwind-css\&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge\&logo=react-router\&logoColor=white)
![Chart.js](https://img.shields.io/badge/Chart.js-F5788D?style=for-the-badge\&logo=chartdotjs\&logoColor=white)
![Recharts](https://img.shields.io/badge/Recharts-FF6384?style=for-the-badge\&logo=recharts\&logoColor=white)
![Headless UI](https://img.shields.io/badge/HeadlessUI-000000?style=for-the-badge\&logo=tailwind-css\&logoColor=white)
![Lucide](https://img.shields.io/badge/Lucide-000000?style=for-the-badge\&logo=lucide\&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge\&logo=node.js\&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge\&logo=mongodb\&logoColor=white)

---

