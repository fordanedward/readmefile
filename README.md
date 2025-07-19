# GC Capture / Gordon College CTF

Welcome to **GC Capture**, a platform where you can train, compete, and build your cybersecurity skills through fun and realistic CTF (Capture The Flag) challenges.

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

   Access the app at: [http://localhost:5173](http://localhost:5173)

---

## How to Use the Application

### 1. Login

- Navigate to `/login`
- Enter your credentials as a user or admin

### 2. User Features
#### Home Page (`/` or `/hero`)
- Overview of the platform and its purpose
- Welcome message and branding
- **Start a Challenge** button: Quick access to login or challenges

#### Profile Page (`/profile`)
- View and update profile details (username, email, etc.)
- **Upload Profile Picture:** Change your avatar
- **Change Password:** Update your account password
- **Tabs:**
  - **Demographic Data:** View and edit demographic info
  - **Groups:** View, create, join, or leave groups; manage group invitations
  - **User Statistics:** Shortcut to your statistics page

#### User Statistics (`/user-statistics`)
- View your progress and performance data
- Visualizations: Pie, bar, and line charts for solved challenges, categories, and activity
- **Edit Profile:** Quick link back to profile page

#### Challenges (`/challenges`)
- Browse all available CTF challenges by category
- **Search Challenges:** Find challenges by keyword
- **Filter by Category/Difficulty:** Narrow down challenge list
- **View Challenge Details:** See description, hints, and points
- **Submit Flag:** Enter your solution to solve a challenge

#### Events (`/event`)
- Browse upcoming, active, and featured events
- **Search Events:** Filter by name or category
- **View Event Details:** See event info, rules, and schedule
- **Join Event:** Register for an event (individual or group)
- **Cancel Registration:** Withdraw from an event
- **Switch View:** Toggle between grid and list views

#### Join Event Modal
- **Choose Participation Type:** Individual or group
- **Enter Access Code:** For restricted events
- **Create Group:** Start a new group for group events
- **Join as Group Member:** Join an existing group

#### Event Challenges (`/event-challenges/:eventId`)
- **Enter/Change Access Code:** Access event challenges
- **View Event Challenges:** List of event-specific challenges
- **Filter/Search:** By category, difficulty, or keyword
- **View Challenge Details:** Description, hints, and points
- **Submit Flag:** Solve event challenges

#### Event Leaderboard (`/event-challenges/:eventId/leaderboard`)
- View rankings for individuals and groups in the event

#### Leaderboards (`/leaderboards`)
- View overall platform rankings and top performers

#### Solved Challenges (`/solved_challenges`)
- Review challenges you have already solved

#### Navigation Bar
- Quick links to Home, Profile, Events, Leaderboards
- **Logout:** Sign out of your account

---

### 3. Admin Features

Admins see only what they are permitted to access.

#### Admin Dashboard (`/admin/dashboard`)
- Overview of platform statistics (users, challenges, solves, etc.)
- **Metric Cards:** View total users, new users, active users, total challenges, solves, and more
- **Category Breakdown:** See challenge distribution by category
- **Quick Actions:** Shortcuts to create challenges, view statistics, manage users, and monitor security

#### Challenges Management (`/admin/challenges`)
- **View All Challenges:** List and search all CTF challenges
- **Add New Challenge:** Create a new challenge (title, description, category, difficulty, etc.)
- **Edit Challenge:** Update challenge details
- **Delete Challenge:** Remove a challenge from the platform
- **Upload Challenge Files:** Attach files to challenges
- **View Challenge Statistics:** See solve rates and attempts per challenge

#### Specific Challenge Page (`/admin/challenges/:challengeId`)
- **Edit Challenge Details:** Update all challenge info
- **View Submissions:** See who solved the challenge and their attempts

#### Events Management (`/admin/events`)
- **View All Events:** List, search, and filter events by status or category
- **Add New Event:** Create a new event (name, description, schedule, etc.)
- **Edit Event:** Update event details
- **Delete Event:** Remove an event from the platform
- **Publish Event:** Make an event visible and open for registration
- **Cancel Event:** Cancel an event and notify participants
- **Manage Applicants:** View and manage pending applicants for upcoming/registration-open events
- **Switch View:** Toggle between grid and table views
- **Pagination:** Navigate through multiple pages of events

#### Event Lobby (`/admin/events/:eventId/lobby`)
- **View Event Info:** See event name, description, and settings
- **Manage Event Challenges:** Add, edit, or remove challenges for the event
- **Upload Challenge File:** Attach files to event challenges
- **View Attempts Graph:** Visualize challenge attempts (group or individual)
- **Back to Events:** Return to the main events list

#### Event Leaderboard (`/admin/events/:eventId/leaderboard`)
- **Switch Leaderboard Tab:** Toggle between individual, group, or combined leaderboards

#### Event Attempts Graph (`/admin/events/:eventId/attempts`)
- **View Attempts Data:** See graphical data of challenge attempts for the event

#### Overall Challenges Dashboard (`/admin/overall_challenges`)
- **View Challenge Analytics:** See most popular, hardest, and category-based challenge stats
- **Navigate to Events:** Quick link to overall events dashboard

#### Overall Events Dashboard (`/admin/overall_events`)
- **View Event Analytics:** See most popular, hardest, and category-based event stats
- **Navigate to Challenges:** Quick link to overall challenges dashboard

#### Statistics Dashboard (`/admin/statistics`)
- **View Platform Analytics:** Detailed statistics for all challenges and user activity
- **Time Range Selection:** Filter analytics by time period (24h, 7d, 30d, etc.)
- **Real-Time Activity:** Monitor live activity and suspicious actions

#### Students Management (`/admin/students`)
- **View All Students:** List and search all student accounts
- **Archive/Restore Students:** Manage student access and status
- **View Student Details:** See individual student info and activity

#### Admin Navigation/Sidebar
- Quick links to all admin pages: Dashboard, Challenges, Events, Students, Statistics
- Use **Refresh** buttons when needed
- **Logout:** Sign out of the admin account
 
---

## Tips for New Users

- Start with easier challenges
- Check your progress on `/user-statistics`
- Don’t hesitate to skip and come back
- Keep your profile updated

---

## Contributing

1. Fork the repo
2. Create a new branch
3. Implement changes
4. Commit with meaningful messages
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

