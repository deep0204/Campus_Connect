# 🎓 CampusConnect

Your personalized gateway to discovering the perfect college 🎯  
Built for students. Backed by AI. Driven by real data. 💡

---

## 🚀 What is CampusConnect?

**CampusConnect** is a full-stack web platform (think Shiksha.com meets AI 🤖) that helps students explore and choose the best-fit colleges based on their profiles, interests, and career goals. Whether you're confused by cutoffs, searching for mentors, or looking for genuine content—CampusConnect has your back.

---

## 🧠 Key Features


### 1. 🎯 College Explorer
> A form-based and filter-rich UI where users input their academic preferences and receive AI-generated college suggestions.

### 2. 🧑‍🏫 Mentor Connect
> A booking interface that allows users to view mentor profiles, check availability, and book live guidance sessions.

### 3. 🎥 Career Videos
> A carousel or grid layout embedded with YouTube API integration to recommend career-related videos based on user interests.

### 4. 🤖 AI Career Coach
> An interactive chatbot widget integrated throughout the site to offer real-time career guidance and answer questions.

### 5. 🏅 XP & Leaderboard System
> A gamified UI with badges, points tracker, and a leaderboard section to view top users and drive engagement.

### 6. 🎓 Scholarships Hub
> A scrollable, searchable feed showing timely scholarship updates with "Apply" or "Save" buttons for each entry.

### 7. 🧑‍💻 Personalized Dashboard
> Track saved colleges, booked sessions, video recommendations, and XP — all in one place.

---

## 🧱 Tech Stack

| Layer        | Technology                     |
|--------------|---------------------------------|
| 💻 Frontend   | React.js, TypeScript, Tailwind CSS |
| 🔌 Backend    | Supabase (Auth, DB, API)        |
| 🤖 AI/ML      | Gemini API (Prompt-based answers) |
| 📹 API        | YouTube Data API               |
| ☁️ Hosting    | Vercel / Netlify (planned)     |
| 🔧 Versioning | GitHub                         |

---



## 🛠️ Installation & Setup

Wanna run it locally? Easy peasy! 🍋

```bash
# 1. Clone the repo
git clone https://github.com/deep0204/Campus_Connect/edit/main/CampusConnect.git
cd CampusConnect

# 2. Install frontend dependencies
cd frontend
npm install

# 3. Start the frontend
npm run dev

# 4. (In another terminal) Setup Supabase backend
# Already connected if using Supabase hosted services

# 5. Set up environment variables
# .env file example:
SUPABASE_URL=your_url
SUPABASE_ANON_KEY=your_key
GEMINI_API_KEY=your_key
YOUTUBE_API_KEY=your_key
```

