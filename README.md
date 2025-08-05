# 🌍✈️ Travel Tracker — Explore Your Journey Visually

**Track the countries you've visited. See them light up on a world map. Simple. Interactive. Beautiful.**

---

### 🧭 What is Travel Tracker?

A full-stack web app where users can:

✅ Add visited countries by typing the name  
🗺️ See countries light up on a stylish SVG world map  
📊 Track how many countries out of 195 you’ve visited  
⚠️ Get smart error feedback (duplicate or invalid input)

> Whether you're a globetrotter or planning your next escape, visualize your story in real time.

---

### 🛠 Tech Stack

| 💻 Tech       | 🔍 Purpose                          |
|--------------|--------------------------------------|
| Node.js + Express | Backend API and routing            |
| PostgreSQL        | Stores country and visit data     |
| EJS               | Renders dynamic content           |
| HTML + CSS        | Clean UI with glassmorphism vibes |
| SVG Map           | Interactive world visualization   |

---

### 🎮 How It Works

1. Type a country name (full or partial)
2. The app matches it to an official country code
3. If valid & new, it’s added to your "visited list"
4. Map updates — country highlighted!
5. See total visited countries at the bottom

---

### 🚀 Getting Started

```bash
git clone https://github.com/Ardhaya-Johari/Travel-Tracker.git
cd travel-tracker
npm install
```

### 🧩 Set Up the Database
```bash
sql
Copy
Edit
```
-- Create DB
```bash
CREATE DATABASE World;

-- Create tables
CREATE TABLE countries (
  country_code VARCHAR(2) PRIMARY KEY,
  country_name VARCHAR(100)
);

CREATE TABLE visited_countries (
  country_code VARCHAR(2) PRIMARY KEY REFERENCES countries(country_code)
);
```
## 👉 Make sure to populate countries with real-world country data.

## 📈 What You'll See
- A dark-themed world map 🗺️

- Smooth animations ✨

- A floating counter of countries visited 📊

- Helpful error messages 😇

- A simple, powerful UI experience

## 👨‍💻 Creator

**Ardhaya Johari**  
🔗 [GitHub](https://github.com/Ardhaya-Johari)  
📧 ardhayasaxena3897@gmail.com  
💼 [LinkedIn](https://www.linkedin.com/in/ardhaya-johari-819275321/)

Built with ❤️ by Ardhaya Johari