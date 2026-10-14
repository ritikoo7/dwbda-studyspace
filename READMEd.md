# 📊 DWBDA Studyspace

### A Student-Friendly Data Warehousing and Big Data Analytics Study Dashboard

DWBDA Studyspace is a browser-based study planner designed to help students organize their **Data Warehousing and Big Data Analytics (DWBDA)** exam preparation. It combines syllabus tracking, midterm priorities, revision notes, flashcards, a calendar, tasks, a focus timer, and a prompt-building Study Buddy in one responsive website.

The project is built with **HTML, CSS, and JavaScript**. It runs directly in a modern browser and does not require a backend, database server, package installation, or build tools.

---

## 📑 Table of Contents

- [Project Overview](#-project-overview)
- [Why This Project](#-why-this-project)
- [Features](#-features)
- [Syllabus Included](#-syllabus-included)
- [Technology Stack](#-technology-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Run Locally](#-run-locally)
- [Deploy with GitHub Pages](#-deploy-with-github-pages)
- [How It Works](#-how-it-works)
- [AI Study Buddy Note](#-ai-study-buddy-note)
- [Data, Storage, and Privacy](#-data-storage-and-privacy)
- [Limitations](#-limitations)
- [Future Improvements](#-future-improvements)
- [Learning Outcomes](#-learning-outcomes)
- [Contributing](#-contributing)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🎯 Project Overview

Exam preparation can become difficult when syllabus topics, deadlines, revision notes, and study sessions are spread across different places. DWBDA Studyspace brings these activities together in a single dashboard.

Students can use it to track their progress through the listed syllabus, mark midterm priorities, plan tasks and events, save revision notes, practise with starter flashcards, and run focused study sessions.

### Project Objectives

- Organize DWBDA topics in one place.
- Make syllabus progress visible.
- Separate overall syllabus progress from midterm revision progress.
- Help students plan study tasks, deadlines, and calendar events.
- Support quick revision through notes and flashcards.
- Demonstrate a useful, lightweight frontend project.

---

## ✨ Features

### 📊 Dashboard
- Shows overall syllabus progress.
- Displays midterm completion, open tasks, and saved-note counts.
- Shows progress for each module.
- Highlights upcoming tasks and provides quick navigation to common study tools.

### ☑️ Syllabus Tracker
- Organizes topics into five modules.
- Supports searching topics by name.
- Filters by module and completion status.
- Tracks completed topics and displays progress.

### 🎯 Midterm Priority
- Provides a separate checklist for midterm preparation.
- Allows midterm progress to be tracked independently from overall syllabus progress.

### 📅 Study Calendar
- Displays a monthly calendar.
- Allows study, exam, assignment, revision, and personal events to be added.
- Lists upcoming events and supports removing events.

### ✅ Tasks and Deadlines
- Create tasks with optional due dates and categories.
- Mark tasks as complete.
- Filter tasks by all, open, or completed.
- Delete tasks when they are no longer needed.

### 📝 Study Notes
- Save notes with a title, related topic, and note content.
- Review saved notes in the Notes section.
- Delete notes when needed.

### 🧠 Flashcards
- Includes a starter set of revision cards based on the syllabus.
- Flip between a question and its answer.
- Move forward and backward through the deck.

### ⏱️ Focus Timer
- Includes 15-minute, 25-minute, and 45-minute focus-session options.
- Start, pause, and reset the timer.
- Displays a completion message when a session ends.

### ✦ AI Study Buddy Prompt Builder
- Offers study modes such as simple explanation, exam answer, quiz, quick revision, and study plan.
- Includes starter prompt buttons.
- Builds a prompt that can be copied into a separate AI assistant.

**Important:** The AI Study Buddy is a prompt builder, not a connected AI chatbot. It does not call an AI model or generate answers by itself.

### 🌙 Light and Dark Themes
- Uses a clean, blue-accented interface.
- Includes a dark-mode toggle.

### 💾 Backup and Restore
- Export supported study data to a JSON backup file.
- Import a previously exported backup.
- Ask for confirmation before replacing the current browser's saved data.

### 📱 Responsive Layout
- Adapts its layout for smaller screens.
- Uses a mobile-friendly navigation layout and responsive cards.

---

## 📚 Syllabus Included

The current website organizes its 42 topics into these five modules.

### Module 1: Data Warehousing
- Introduction to Data Warehousing
- ETL Process
- Star Schema
- Snowflake Schema
- OLTP
- OLAP
- Normalization: Min-Max and Z-score
- Data Preprocessing and Cleaning
- Data Warehousing, Data Marts and Data Lake
- Types of Data

### Module 2: Data Mining and Similarity
- LZW Compression
- Sampling and its Methods
- MBA (as written in the source syllabus)
- Apriori Algorithm
- FP-Growth
- Bloom Filter
- Flajolet-Martin Algorithm
- Distance Measure
- Euclidean Distance
- Jaccard Distance
- Cosine Distance
- Edit Distance
- Hamming Distance

### Module 3: Big Data and Hadoop
- Introduction to Big Data
- Characteristics of Big Data
- Hadoop
- Hadoop Architecture
- HDFS
- YARN
- MapReduce
- SQL vs NoSQL
- CAP Theorem
- Shared Nothing Architecture

### Module 4: Streams and Processing
- Data Streams
- Kafka
- Stream Processor / Stream Processing
- Apache Spark

### Module 5: Applications and Ranking
- Recommendation System
- Filtering
- PageRank Algorithm

The syllabus labels are reproduced from the topic list currently present in the website. Check them against your instructor's official syllabus and update `index.html` if anything needs correction.

---

## 🧰 Technology Stack

| Technology | Role |
|---|---|
| HTML5 | Structure and content |
| CSS3 | Styling, layout, themes, and responsive design |
| JavaScript | Navigation, study tools, timer, filtering, and interactions |
| `localStorage` | Saves supported data in the browser |
| JSON | Export and import of study-data backups |
| Git and GitHub | Version control and project hosting |
| GitHub Pages | Optional static website deployment |

No framework, package manager, or backend is required for the current standalone version.

---

## 📂 Project Structure

```text
dwbda-studyspace/
├── index.html
└── README.md
```

- `index.html`: the complete website, including its HTML, CSS, and JavaScript.
- `README.md`: project documentation and setup instructions.

---

## 🚀 Getting Started

### Requirements
- A modern browser such as Google Chrome, Microsoft Edge, or Firefox.
- A GitHub account if you want to publish the project.
- An internet connection to access GitHub and the published site.

### Download the Project
1. Open the GitHub repository.
2. Click **Code**.
3. Select **Download ZIP**, or clone the repository using Git.
4. If you downloaded a ZIP, extract it.

---

## 💻 Run Locally

1. Download `index.html`.
2. Open it in your browser.
3. Explore the dashboard and syllabus tracker.
4. Add a task, calendar event, or study note.
5. Try the flashcards and focus timer.
6. Test **Export backup** and **Import** if you want to back up your study data.

No `npm install`, build command, or backend server is needed.

---

## 🌐 Deploy with GitHub Pages

GitHub Pages can host a static website from a GitHub repository, subject to GitHub's current policies and usage limits.

1. Create a repository named `dwbda-studyspace`.
2. Upload `index.html` and `README.md` to the repository root.
3. Commit the files to the `main` branch.
4. Open the repository's **Settings**.
5. Select **Pages** from the sidebar.
6. Under **Build and deployment**, select **Deploy from a branch**.
7. Choose branch `main` and folder `/(root)`.
8. Click **Save**.
9. Wait for the deployment to finish, then open the published site.

Your URL will generally look like this:

```text
https://YOUR-USERNAME.github.io/dwbda-studyspace/
```

Replace `YOUR-USERNAME` with your GitHub username. If you choose a different repository name, update the URL accordingly.

Official guide: [GitHub Pages documentation](https://docs.github.com/en/pages)

### Deployment Checklist
- Open the deployed website.
- Navigate through all sections.
- Add and complete a test task.
- Save a test note and calendar event.
- Test the timer.
- Test dark mode.
- Export a backup and confirm that a JSON file downloads.
- Test importing a backup with care, since importing replaces the current saved Studyspace data after confirmation.
- Check the layout on both desktop and mobile.

---

## ⚙️ How It Works

### Static Website
The browser loads the HTML, CSS, and JavaScript from one file. Most interactions happen directly in the browser.

### Local Data
The app saves its study data in browser `localStorage` under the key `dwbdaStudyspace`. The data is not sent to a server by this code.

### Backup File
The export tool creates a JSON file containing the current supported Studyspace state. The import tool reads a compatible JSON backup and, after confirmation, replaces the current saved state.

### Topic Search
The syllabus tracker filters the topics already included in the website. It does not search the internet or external documents.

---

## ✦ AI Study Buddy Note

The Study Buddy section is a **prompt generator**. It formats the student's request into a prompt for a separate AI assistant and provides a copy button.

It does **not** connect to ChatGPT, Gemini, Claude, or another model. To build a real AI tutor, a future version would need a secure backend and appropriate API integration. Secret API keys should never be placed directly in a public HTML file.

---

## 🔐 Data, Storage, and Privacy

- Tasks, events, notes, progress, and theme preferences are saved locally in the browser.
- Data is not automatically synchronized across devices or shared with other users.
- Clearing browser data may delete saved Studyspace information.
- Private/incognito sessions may not preserve data after the session ends.
- Use the export feature regularly if you want a backup.
- Do not store passwords, financial details, or sensitive personal information in study notes.

---

## ⚠️ Limitations

- The website is a standalone frontend application, not a full-stack service.
- There is no account login, server database, or automatic cloud sync.
- The Study Buddy only prepares prompts; it does not generate AI answers.
- The starter flashcards are a small revision set, not a complete question bank.
- Syllabus wording may need to be checked against the latest official course outline.
- Browser storage can be removed by the user or browser.
- Test all features after editing the code or publishing a new version.

---

## 🛠️ Future Improvements

Ideas for future versions:
- Add module-wise PDFs, lecture notes, and reference materials.
- Add topic-wise MCQs and timed practice tests.
- Add exam countdowns and a weekly study planner.
- Add progress charts and revision streaks.
- Add search across saved notes.
- Allow students to create and edit their own flashcards.
- Improve keyboard navigation and accessibility.
- Add more detailed analytics for focus sessions.
- Add optional cloud synchronization in a future full-stack version.
- Integrate a real AI tutor through a secure backend.

These are future ideas, not features that are already included in the current version.

---

## 🎓 Learning Outcomes

This project can help students practise:
- Structuring a complete webpage with HTML.
- Styling responsive layouts with CSS.
- Writing JavaScript for user interactions.
- Updating interface content dynamically.
- Using browser storage to persist application state.
- Exporting and importing structured JSON data.
- Organizing and documenting a project with GitHub.
- Deploying a static site using GitHub Pages.
- Thinking about usability, accessibility, and data privacy.

---

## 🤝 Contributing

Contributions and student suggestions are welcome.

1. Fork the repository.
2. Create a branch for your change.
3. Make the change and test it locally.
4. Commit with a clear message.
5. Open a pull request describing what you changed and why.

Please test navigation, data saving, backup and restore, the focus timer, and mobile layout before submitting a change.

---

## 📢 Disclaimer

DWBDA Studyspace is an independent student learning project. It is not an official university website and does not replace the official syllabus, lectures, textbooks, or instructor guidance. Verify course information with your institution.

---

## 📜 License

No license is specified by default. If you want other people to reuse, modify, or distribute this project, choose and add an appropriate open-source license after reviewing its terms.

---

## 🏷️ Suggested GitHub Topics

Add these topics in the repository's **About** settings:

`dwbda` `big-data-analytics` `data-warehousing` `study-planner` `student-dashboard` `html` `css` `javascript` `github-pages` `exam-preparation`

---

**Built to make DWBDA exam preparation more organized, one topic at a time. 📊**
