# Oracle-APEX-Smart-Employee-Performance-Management-System
## Project Background

This project was developed during my training at the Digital Transformation Agency.

The project focuses on applying artificial intelligence concepts to improve business processes by creating a smart employee task assignment system that helps organizations select the most suitable employee for each task based on skills, experience, workload, and performance.

The project demonstrates the practical application of:
- Artificial Intelligence
- Data Analysis
- Digital Transformation Solutions
- Business Process Optimization
- Web Application Development

---

## Overview

AI Employee Task Assignment System is a smart web application that helps managers assign tasks to the most suitable employees automatically.

The system analyzes employee skills, experience, workload, and performance to recommend the best candidate for each task using an AI-based scoring algorithm.

---

## Features 🚀

### AI Task Recommendation

- Enter any task name
- Select task priority
- Analyze all employees automatically
- Recommend the best employee
- Display match score and recommendation reasons

### Employee Management

- Generate 100 realistic employee records
- Employee profiles
- Skills and certifications
- Experience tracking
- Workload monitoring
- Availability status

### Dashboard Analytics

- Total employees count
- Available employees
- Busy employees
- Average completion rate
- Department statistics
- Performance charts

### Search and Filtering

Employees can be filtered by:

- Department
- Skills
- Experience
- Availability status

### Performance Ranking

Includes:

- Top performing employees
- Highest completion rate
- Most experienced employees

### Task History

Stores:

- Task name
- Assigned employee
- Assignment date
- Priority
- Completion status

### Notifications

Provides alerts for:

- Task assigned successfully
- Employee workload is high
- No suitable employee found

---

# AI Recommendation Algorithm 🧠

The system calculates the employee match score based on:

| Criteria | Weight |
|----------|--------|
| Skill Matching | 50% |
| Years of Experience | 20% |
| Current Workload | 20% |
| Performance Rate | 10% |

Formula:

```
Match Score =
(Skill Match × 50%)
+
(Experience × 20%)
+
(Workload × 20%)
+
(Performance × 10%)
```

The employee with the highest score is selected automatically.

---

# Technologies Used 💻

- React
- TypeScript
- JavaScript
- Tailwind CSS
- Modern UI Components
- Charts and Data Visualization
- Local Sample Database

---

# Application Pages 📱

## Dashboard

Displays:

- Total employees
- Available employees
- Busy employees
- Average completion rate
- Department statistics
- Performance charts

---

## Task Assignment

Allows managers to:

- Enter task name
- Select priority
- Get AI employee recommendation

---

## Employees Page

Features:

- View all employees
- Search employees
- Filter by department
- Filter by skills
- Filter by experience
- Filter by availability

---

## Employee Profile Page

Displays:

- Employee ID
- Full Name
- Department
- Job Title
- Skills
- Experience
- Certifications
- Current Tasks
- Completed Tasks
- Performance Score
- Workload Status

---

## Ranking Page

Shows:

- Top performing employees
- Highest completion rate
- Most experienced employees

---

## Task History Page

Displays previous recommendations:

- Task name
- Assigned employee
- Date
- Priority
- Completion status

---

# Example Recommendation

**Task:**

Develop Oracle APEX Page

**Recommended Employee:**

Ahmed Ali

**Department:**

Software Development

**Match Score:**

96%

**Reasons:**

✓ Skill match  
✓ High experience  
✓ Low workload  
✓ Excellent completion rate  

---

# Future Improvements 🔮

- Connect with real databases
- Add machine learning models
- Real employee data integration
- User authentication
- Automatic task classification
- Advanced AI prediction

---

# Installation

Clone the repository:

```bash
git clone YOUR_REPOSITORY_URL
```

Install dependencies:

```bash
npm install
```

Run the project:

```bash
npm run dev
```

---

# License

This project is created for demonstration and educational purposes.
