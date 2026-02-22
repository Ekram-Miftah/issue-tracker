# 🛠️ Issue Tracker | Collaborative Task Management Tool

[![Live Demo](https://img.shields.io)](https://issue-tracker-kappa-eosin.vercel.app)

A modern, responsive application designed for tracking and managing project tasks, simulating a professional **Agile workflow**.
This tool streamlines team collaboration by providing a centralized hub for bug reporting and feature tracking.

---

## 📸 Visual Preview


| Task Board View | Issue Details |
<img width="1361" height="598" alt="6" src="https://github.com/user-attachments/assets/97217331-f5df-40f2-856e-9140c5cf354d" />
<img width="1361" height="611" alt="7" src="https://github.com/user-attachments/assets/cec9822b-e118-4b97-b53c-0700729a7a14" />
<img width="870" height="643" alt="8" src="https://github.com/user-attachments/assets/3db01623-0c5c-4dfc-988f-378ab17aefeb" />
<img width="1334" height="600" alt="image" src="https://github.com/user-attachments/assets/a6a75ded-78ec-4409-94f3-ffdbab48506c" />


## 🚀 Key Features

### 📋 Task Management
- **Full CRUD Operations**: Users can **Create, Read, Update, and Delete** issues with ease.
- **Dynamic Filtering**: Implemented complex logic to sort and filter tasks by status, priority, or assignee.
- **Real-time Updates**: Optimized state management to ensure a seamless experience when transitioning between task views.

### 💻 User Experience
- **Responsive Design**: Built with a mobile-first approach to work perfectly on all screen sizes.
- **Agile Workflow**: Designed the UI to mimic professional project management tools used in the tech industry.

---

## 🛠️ Technical Tech Stack

- **Framework**: **Next.js** (App Router)
- **Frontend**: **React** with **Tailwind CSS** for modern styling
- **Data Fetching**: Efficient **API Route** handling for server-side operations
- **Deployment**: **Vercel**

---

## 🏗️ Architecture & Challenges
- **The Challenge**: Managing complex filtering and sorting logic without sacrificing application performance.
- **The Solution**: Leveraged **Next.js server components** and efficient state management to handle data processing, resulting in a fast and responsive interface.

---

---

## ⚡ How to Run Locally

1. **Clone the repo:**
   `git clone https://github.com`

2. **Install Dependencies:**
   `npm install`

3. **Set up Environment Variables:**
   Create a file named `.env` in the root directory and add the following:
   ```env
   DATABASE_URL="your_database_url_here"
   NEXTAUTH_URL="http://localhost:3000"
   NEXTAUTH_SECRET="your_secret_key"
   GOOGLE_CLIENT_ID="your_google_id"
   GOOGLE_CLIENT_SECRET="your_google_secret"
