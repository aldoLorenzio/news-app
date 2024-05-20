# News App

A modern news application build using React and Vite, which fetches news articles from a public API called News API.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)

## Overview
This project is a news application that allows users to view the latest news articles from various sources. The app fetches data from a public news API

![News App Screenshot](./public/newsAppScreenshot.png)

## Features

- Fetches news articles from a public API
- Displays articles with title, description, and images
- Categories to filter news by type

## Installation

1. **Clone the repository:**

```bash
git clone https://github.com/aldoLorenzio/news-app.git
cd news-app
```

2. **Install dependencies:**

 ```bash
npm install
 ```

3. **Set up environment variables:**
 Create a `.env` file in the root directory and add the following variable:
```env
 VITE_NEWS_API_KEY= your_public_api_key
 ```
get your API key from `https://newsapi.org/` 

4. **Run the app:**

```bash
npm run dev
```

5. Open your browser and navigate to `http://localhost:3000` to see the app in action.

## Usage

- View the latest news articles on the homepage.
- Filter news by categories using the category tabs.

## Technologies

- **React:** A JavaScript library for building user interfaces
- **Vite:** A build tool that provides a faster and leaner development experience for modern web projects
- **CSS (Bootstrap):** For styling the application

---

Thank you for checking out my News App! Stay informed with the latest news!