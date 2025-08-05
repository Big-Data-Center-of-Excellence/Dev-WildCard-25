# 🚀 WildCard Round – Problem Statements

This repository contains curated problem statements for different domains aimed at testing creativity, technical skills, and problem-solving ability across Web, App, ML, UI/UX, and Frontend development.

### Problem Statement Doc:
Kindly Download this document to understand the problem statements and other details about the project. 
[Download Problem Statement](https://docs.google.com/document/d/1bxygzAaQT-xenNA0nEpcB9XVZWP0FXdHa1c5gzPx1fo/edit?usp=sharing)
---

## 🎨 UI/UX Design Task

### 🟡 Problem Statement:
Recreate the core UI of a **food delivery app**, inspired by Blinkit, or design your own concept specifically for **college students or hostel residents**.

### 📱 What to Design:
- **Home Screen**: Categories, banners, nav bar
- **Search Page**: Search input, results layout
- **Product Listing (optional)**: Product cards with "Add" button
- **Cart Page**: List, total price, checkout button

### 🎯 Focus:
Clean visual hierarchy, intuitive navigation, and mobile-first approach.

---

## 🤖 Machine Learning

### 📌 Problem Statement: **Loan Approval Prediction**

Build a ML model to predict **loan approvals** based on applicant details.

### 🗂️ Dataset:
Provided in CSV format.  
[Download Dataset](https://drive.google.com/file/d/1mKKXUdLILPwOYuB_6IrBmDJBfiluf5ab/view?usp=sharing)

### ✅ Tasks:
- Data cleaning & preprocessing
- EDA with matplotlib
- Train at least **2 models**
- Evaluate accuracy and insights
- (Optional) Create a Streamlit web app

---

## 🌐 Web Development

### 📌 Backend – Task 1: **Notes App**

Build a secure Notes app with:
- **User Auth (JWT or sessions)**
- **Private/Public notes**
- **Full CRUD operations**
- **Access control per user**

#### Key Models:
- User (username, email, password)
- Note (title, content, isPublic, timestamps, owner)

#### API Endpoints:
- `/auth/signup`, `/auth/login`
- `/notes` (GET, POST)
- `/notes/public`, `/notes/:id`, etc.

---

### 📌 Backend – Task 2: **Expense Tracker App**

A personal expense tracker backend with:
- User authentication
- CRUD operations on expenses
- **Filters by date & category**

#### Key Models:
- User
- Expense (title, amount, category, date, notes)

#### API Endpoints:
- `/auth/register`, `/auth/login`
- `/expenses` (GET, POST, PUT, DELETE)
- `/expenses?category=Food`, etc.

---

## 🎯 Frontend Development

### 📝 Task 1: **Self-Rent Vehicle Business Website**

Create a promotional website for a **white-label self-rent car solution**.

#### Sections to Include:
- Hero Section: Common rental business issues
- Solution Highlights: App features
- Pricing: ₹45,000/year or ₹3,750/month
- CTA Buttons: Contact, Request Demo
- Footer: Basic contact info

---

### 🚀 Task 2: **Crypto Tracker – React Project**

Build a React app to **search, filter, and sort** real-time cryptocurrency data.

#### 🔧 Features:
- Search by coin name
- Filter by:
  - Market Cap Rank (e.g., Top 10, Top 50)
  - Price change (positive/negative)
  - Price range (e.g., < ₹100, ₹100–₹10,000, > ₹10,000)
- Sort by:
  - Price (High → Low or Low → High)
  - Market Cap
  - 24h Change %
- Display coin cards with:
  - Name
  - Symbol
  - Logo
  - Current Price
  - 24h Price Change
  - Market Cap

#### 🔌 API Info – CoinGecko API:
Use this public endpoint to fetch coin market data:

```
https://api.coingecko.com/api/v3/coins/markets?vs_currency=inr
```


---

## 📱 App Development

### 📌 Problem Statement: **Weather App using Flutter**

Create a **minimal weather app** using Flutter + OpenWeatherMap API.

#### Features:
- Input field for city name
- "Get Weather" button
- Display:
  - City Name
  - Temperature
  - Weather Description
  - Humidity

#### 🔧 Requirements:
- Use HTTP client (`http` package)
- Handle loading + error states

---

## 📎 Notes

- All projects are beginner-friendly unless stated otherwise.
- You’re encouraged to build a working UI + logic and make minor improvements.
- Submit your project folders or GitHub links as per instructions.

---

Happy building! 🚀
