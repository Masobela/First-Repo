# First-Repo
A professional Full-Stack Weather Dashboard using OpenWeatherMap API. Features real-time data fetching, 5-day forecasts, and persistent search history. Built to demonstrate API integration and responsive UI/UX.
# ☁️ SkyCast: Full-Stack Weather Dashboard

**SkyCast** is a modern, responsive weather application that provides real-time hyperlocal forecasts. This project was built to demonstrate proficiency in handling asynchronous API operations, state management, and professional documentation.

## 🚀 Live Demo
[Insert your Vercel/Netlify link here]

## ✨ Key Features
- **Real-time Data:** Fetches current temperature, humidity, and wind speed using OpenWeatherMap API.
- **5-Day Forecast:** Dynamic rendering of upcoming weather trends.
- **Persistent Search:** Saves your recent cities using LocalStorage (or Database).
- **Responsive Design:** Fully optimized for Mobile, Tablet, and Desktop.
- **Smart UI:** Background colors change dynamically based on weather conditions (Sunny/Rainy/Cloudy).

## 🛠 Tech Stack
- **Frontend:** React 19, TypeScript, Tailwind CSS
- **Backend:** Node.js (for API Key masking)
- **API:** [OpenWeatherMap API](https://openweathermap.org)
- **Deployment:** Vercel

## ⚙️ Local Setup
1. **Clone the repo:**
   ```bash
   git clone https://github.com
Use code with caution.

Install dependencies:
bash
npm install
Use code with caution.

Environment Variables:
Create a .env file and add your API key:
env
VITE_WEATHER_API_KEY=your_actual_key_here
Use code with caution.

Start Developing:
bash
npm run dev
Use code with caution.

🧠 Engineering Highlights
Error Handling: Implemented "City Not Found" fallbacks to prevent app crashes.
Performance: Used Debouncing on the search input to limit unnecessary API calls.
Security: Managed API keys through environment variables to prevent exposure in the frontend.
👤 Author: [Your Name]
📅 Updated: January 2026

---

### 3. The `.gitignore` File
**CRITICAL:** You must include this file so you don't accidentally leak your private API key to the public. 
*Create a file named `.gitignore` and paste this:*

```text
# Logs
logs
*.log
npm-debug.log*

# Dependency directories
node_modules/

# Environment variables (Crucial for Security!)
.env
.env.local
.env.development.local
.env.test.local
.env.production.local

# Build output
dist/
build/

# IDE files
.vscode/
.idea/
.DS_Store
🚀 Next Steps to Finish:
Get your API Key: Go to the OpenWeatherMap API Portal and sign up for the "Current Weather Data" subscription (it's free).
Code it: Use VS Code or Cursor to build the logic.
Push to GitHub:
bash
git add .
git commit -m "Initial commit: Weather Dashboard with README"
git push origin main
Use code with caution.





