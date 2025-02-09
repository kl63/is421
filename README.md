# FitVision AI - AI-Powered Personalized Workout Plans

FitVision AI is a modern web application that leverages artificial intelligence to deliver personalized workout plans and intelligent fitness recommendations. By analyzing user data with advanced AI techniques, the application creates custom workout programs that help users achieve their fitness goals efficiently.

---

# Project Overview

## Branches
- **Main:** Production (live site)  
  [http://prod.sportify2024.me/](http://prod.sportify2024.me/)
- **Development:** Working branch  
  [http://dev.sportify2024.me/](http://dev.sportify2024.me/)
- **QA:** Testing branch  
  [http://qa.sportify2024.me/](http://qa.sportify2024.me/)

## Project Structure
- **github/** (GitHub Actions)
  - **workflows/**
    - `deploy2.yml`
- **.vscode/**
- **public/** (All our code)
  - **images/** (All our images and files)
- `about.html` – About page code
- `about.style.css` – CSS for the about page
- `index.html` – Homepage code
- `index.style.css` – CSS for the homepage
- `package-lock.json`
- `package.json`
- `README.md`

---

# Setting Up the Project (Use Terminal!)

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/kl63/is421.git

2. **Navigate to the Project Directory:**
   ```bash
   cd is421
   
3. **Pull the Latest Changes:**
   ```bash
   git pull origin [branch-name]

**_Always do this before making changes to avoid merge conflicts._**

4. **Modify the Code as Needed.**

5. **Commit Your Changes:**
   ```bash
   git status
   git add .
   git commit -m "Your commit message"
   git push origin [branch-name]
   
6. **Create a Merge Request on GitHub:**

- After pushing, you should see a prompt to "Compare & pull request."
- Only merge to **Main** if the code passes tests and is fully functional.
  _Do not push broken code to Main._
  
7. **Check the Live Site:**
- Ensure the live site is updated with the new content.

# Tech Roadmap

The following roadmap outlines our development priorities—starting with the hardest, most valuable challenges and progressing to additional features. This ensures that we address the core components that will have the highest impact on FitVision AI from start to finish.

## Phase 1: Core AI Engine & Data Pipeline (High Value & High Complexity)
- **AI Model Integration:**  
  - Develop and integrate the AI engine to generate personalized workout plans.
  - Train models using diverse fitness data and user profiles.
- **Data Ingestion & Processing:**  
  - Build robust pipelines for collecting, cleaning, and processing user fitness data.
  - Ensure data privacy and security throughout the process.
- **Algorithm Optimization:**  
  - Fine-tune AI algorithms to deliver accurate and personalized workout recommendations.

## Phase 2: User Interface & Experience (Moderate Complexity & High Value)
- **Frontend Development:**  
  - Create an interactive, responsive UI using HTML, CSS, and potentially Next.js.
  - Design intuitive dashboards for users to view and interact with their workout plans.
- **User Feedback Integration:**  
  - Implement feedback mechanisms so users can share their experiences.
  - Use feedback data to continuously optimize the AI engine.

## Phase 3: Integration & Deployment (Moderate Complexity)
- **API & Third-Party Integrations:**  
  - Connect with external fitness trackers and health apps to enrich user data.
- **CI/CD Pipeline:**  
  - Set up automated testing, continuous integration, and deployment pipelines to streamline updates and ensure code quality.

## Phase 4: Advanced Features & Community Engagement (Lower Complexity, Future Enhancements)
- **Social & Community Features:**  
  - Add functionality for users to share progress, tips, and support with one another.
- **Gamification & Progress Tracking:**  
  - Introduce elements such as achievement badges, leaderboards, or progress charts to enhance user engagement.
- **Enhanced Personalization:**  
  - Explore advanced personalization features based on long-term user data trends and behavior.

