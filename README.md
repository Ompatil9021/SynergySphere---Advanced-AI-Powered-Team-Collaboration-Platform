# ✨ SynergySphere - Advanced AI-Powered Team Collaboration Platform

*An intelligent project management platform that works proactively to catch potential issues, streamline collaboration, and help teams make smarter decisions.*

![Python](https://img.shields.io/badge/Python-3.11+-blue.svg?style=for-the-badge&logo=python)
![Flask](https://img.shields.io/badge/Flask-2.3-black.svg?style=for-the-badge&logo=flask)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow.svg?style=for-the-badge&logo=javascript)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3-purple.svg?style=for-the-badge&logo=bootstrap)
![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)

---

## 🚀 Project Vision

SynergySphere is built on a simple idea: teams do their best work when their tools truly support how they think and collaborate. This platform goes beyond traditional project management by becoming an intelligent backbone for teams. It acts as a central nervous system for collaboration, not only streamlining tasks and communication but also working proactively to catch potential issues early, helping teams stay ahead rather than constantly reacting.

## 🎯 Problem Statement

Modern teams, regardless of their domain, face persistent pain points that hinder productivity and create friction. SynergySphere is designed to solve these common headaches:

* **Scattered Information:** Important files, chats, and decisions are spread across too many applications, making it difficult to maintain a single source of truth.
* **Unclear Progress:** A lack of visibility into task status makes it tough to know how far along a project really is or what's holding it up.
* **Resource Confusion:** Team members can become overworked or underutilized due to messy assignment processes.
* **Deadline Surprises:** Critical issues are often noticed only when it's too late. A proactive system is needed to surface potential problems before they escalate.
* **Communication Gaps:** Key updates get missed, conversations are buried in email, and context is lost across scattered chat threads.

## 💡 Our Solution

SynergySphere addresses these pain points by creating an integrated, intelligent, and proactive environment. It doesn't just organize work; it orchestrates collaboration by providing a centralized hub for tasks and discussions, enriched with a layer of AI-powered analysis. The platform helps teams operate at their best by identifying risks, balancing workloads, and prioritizing tasks automatically, allowing teams to work smarter, not just harder.

## 📋 Key Features

SynergySphere is a full-stack web application with a rich, responsive user interface and a powerful backend.

#### Core Project & Task Management
* **Project Workspaces:** Create projects with detailed descriptions, deadlines, priorities, and tags.
* **Kanban Board:** A four-column board (**Backlog, To Do, In Progress, Done**) to intuitively visualize task progress.
* **Task Management:** Create tasks with detailed descriptions, assignees, and due dates.
* **Automated Backlog:** An intelligent system automatically moves overdue "To Do" tasks to the "Backlog" column on every page load, ensuring teams address delays.
* **Personalized Views:**
    * **Dashboard:** A central view of all projects a user is a member of.
    * **My Tasks Page:** A dedicated screen for a user to see all tasks assigned specifically to them, sorted by the upcoming due date.

#### Team Collaboration & Communication
* **Role-Based Users:** Users register with specific roles (e.g., Backend Developer, Designer), which informs the AI's analysis.
* **Team Invites:** Seamlessly invite other registered users to projects from the project board.
* **Task Detail View:** Every task is clickable, opening a dedicated page.
* **Threaded Discussions:** A complete commenting system on each task detail page allows for focused, project-specific conversations.
* **User Profiles:** A simple page for users to see their own account information.

#### ✨ Unique AI-Powered Intelligence
* 🤖 **AI Synergy Analysis:** A feature on the main project board that provides an instant, AI-generated report on the project's health. It analyzes:
    * **Workload Balance:** Detects if team members are over or under-utilized.
    * **Skill Mismatch:** Warns if a task is assigned to a user whose role is not appropriate for it.
    * **Potential Bottlenecks:** Identifies tasks that may be blocking other parts of the project.
* 🚀 **AI Priority View:** A unique project view that organizes tasks by team member. It features a "Calculate AI Priority" button that:
    * Asks the AI to analyze every task based on dependencies, descriptions, and user roles.
    * Assigns a numerical priority score (1-100) to each task.
    * Automatically re-orders the tasks on the page, providing an instant, intelligent action plan.

## 🛠️ Tech Stack

| Category         | Technology                                                 |
| :--------------- | :--------------------------------------------------------- |
| **Backend** | Python, Flask, Flask-SQLAlchemy, Flask-Login, Flask-Bcrypt |
| **Database** | SQLite                                                     |
| **AI Integration**| Google Gemini API                                          |
| **Frontend** | HTML, CSS, JavaScript, Bootstrap 5                         |
| **Styling** | Custom "Glassmorphism" Dark Theme                          |

## ⚙️ Local Installation & Setup Guide

To run this project on your local machine, please follow these steps:

#### Prerequisites
* Python 3.10 or higher
* `pip` package manager
* Git

#### Step-by-Step Instructions

1.  **Clone the Repository**
    Open your command prompt or terminal and run the following command to download the project:
    ```bash
    git clone [https://github.com/Ompatil9021/SynergySphere---Advanced-AI-Powered-Team-Collaboration-Platform](https://github.com/Ompatil9021/SynergySphere---Advanced-AI-Powered-Team-Collaboration-Platform)
    ```

2.  **Navigate into the Directory**
    ```bash
    cd SynergySphere---Advanced-AI-Powered-Team-Collaboration-Platform
    ```

3.  **Create a Virtual Environment**
    It's highly recommended to use a virtual environment to manage project dependencies.
    ```bash
    # For Windows
    python -m venv venv
    ```

4.  **Activate the Virtual Environment**
    ```bash
    # For Windows
    .\venv\Scripts\activate
    ```

5.  **Install Dependencies**
    Install all the required Python packages from the `requirements.txt` file.
    ```bash
    pip install -r requirements.txt
    ```

6.  **Set Up Environment Variables**
    The application requires an API key for the Google Gemini API.
    * Create a file named `.env` in the root of the project directory.
    * Add your API key to this file as follows:
        ```
        GEMINI_API_KEY='Your_API_Key_Here'
        ```

7.  **Run the Application**
    Once the setup is complete, you can run the Flask development server.
    ```bash
    python app.py
    ```
    The application will start, and the `site.db` database file will be created automatically on the first run. Open your web browser and navigate to `http://127.0.0.1:5000`.

## 🕹️ How to Use

To experience the full power of SynergySphere:
1.  **Register two users** with different roles (e.g., one "Backend Developer", one "Designer").
2.  **Log in** as the first user and create a new project from the dashboard.
3.  **Open the project** and use the "Team Members" panel to **invite the second user**.
4.  **Create several tasks**, assigning them to both users. For a great test, create one task with a **due date in the past**.
5.  **Refresh the page** to see the overdue task automatically move to the **Backlog**.
6.  Click the **"Get AI Synergy"** button to get a qualitative analysis of your project.
7.  Navigate to the **"AI Priority View"** tab and click **"Calculate AI Priority"** to watch the tasks re-order themselves based on the AI's logic.
8.  Click on any task title to visit its **detail page** and have a conversation using the **commenting system**.
