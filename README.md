# Jira Clone - ClearA

A fullstack **Jira Clone**, providing an end-to-end project management solution with workspaces, epics, tasks, kanban boards, calendars, role-based access control, analytics, authentication, and more!

## Features

### Project & Task Management

- 🏢 **Workspaces** – Organize teams and projects efficiently.
- 📊 **Projects / Epics** – Structure work at a high level.
- ✅ **Tasks** – Create, assign, edit, and track progress.
- 📋 **Kanban Board View** – Drag-and-drop task management.
- 🗃️ **Data Table View** – Structured, list-based view for easy access.
- 📅 **Calendar View** – Manage deadlines with a visual calendar.

### Collaboration & Permissions

- ✉️ **Invite System** – Easily invite team members.
- ⚙️ **Workspace & Project Settings** – Full control over configurations.
- 👥 **User Roles & Permissions** – Role-based access control for security.

### Technical Stack

- 🔌 **Appwrite SDK Integration** – Backend as a service for authentication, databases, and file storage.
- ⚛️ **Next.js 14 Framework** – A React-based framework for server-side rendering and performance.
- 🎨 **Shadcn UI & TailwindCSS** – Aesthetic and responsive UI design.
- 🔍 **Advanced Search & Filtering** – Quickly find tasks, projects, and users.
- 📈 **Analytics Dashboard** – Track key project and team metrics.
- 🔒 **Authentication** – Secure login via OAuth and Email.
- 📱 **Responsive Design** – Fully functional across mobile and desktop.
- 🚀 **API using Hono.js** – Fast and lightweight API handling.

## Screenshots

![Homepage](/assets/Screenshot1.png)
![MyTasks](/assets/Screenshot2.png)
![MyTasks2](/assets/Screenshot3.png)
![MyTask3](/assets/Screenshot4.png)
![UpdateNamespace](/assets/Screenshot5.png)
![MemberList](/assets/Screenshot6.png)
![MyProjects](/assets/Screenshot7.png)
![CreateTask](/assets/Screenshot8.png)
![CreateWorspace](/assets/Screenshot9.png)
![ChangeRole](/assets/Screenshot10.png)
![AppwriteDatabase](/assets/Screenshot11.png)

Example:

## Installation & Setup

### Prerequisites

Ensure you have the following installed:

- **Node.js (v18 or later)**
- **Yarn or npm**
- **Appwrite Cloud or Self-hosted Appwrite instance**

### Clone the Repository

```bash
git clone https://github.com/jadzeino/jira-clone.git
cd jira-clone
```

### Install Dependencies

```bash
yarn install
# or
npm install
```

## Environment Variables

Before starting, create a .env.local file in the root directory and add your own environment variables:

```bash
NEXT_PUBLIC_APP_URL=http://localhost:3000  NEXT_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1  NEXT_PUBLIC_APPWRITE_PROJECT=670d....  NEXT_PUBLIC_APPWRITE_DATABASE_ID=670e....  NEXT_PUBLIC_APPWRITE_WORKSPACES_ID=670e....  NEXT_PUBLIC_APPWRITE_MEMBERS_ID=670e....  NEXT_PUBLIC_APPWRITE_PROJECTS_ID=6718....  NEXT_PUBLIC_APPWRITE_TASKS_ID=671a....  NEXT_PUBLIC_APPWRITE_IMAGES_BUCKET_ID=670e....  NEXT_APPWRITE_KEY=standard_....
```

## Running the Project Locally

```bash
yarn dev
# or
npm run dev
```

The app will be accessible at [http://localhost:3000](http://localhost:3000).

## Deployment

### App is deployed on Vercel

you can test it on this link
