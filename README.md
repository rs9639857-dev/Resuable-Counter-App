## React Counter App using Custom Hook

## Overview

This project is a simple and reusable Counter Application built using **React** and **Custom Hooks**. The application demonstrates how to extract reusable logic from components by creating a custom hook called `useCounter`.

## Features

* Increment counter value
* Decrement counter value
* Reset counter value
* Reusable Counter component
* Multiple counters with different initial values
* Clean and responsive UI

## Tech Stack

* React
* Vite
* JavaScript (ES6+)
* CSS

## Project Structure

```text
counter-app/
├── src/
│   ├── components/
│   │   └── Counter.jsx
│   ├── hooks/
│   │   └── useCounter.js
│   ├── App.jsx
│   ├── App.css
│   ├── index.css
│   └── main.jsx
├── public/
├── README.md
├── .gitignore
├── package.json
```

## Custom Hook

The `useCounter` custom hook manages the counter state and provides reusable functions:

* `increment()`
* `decrement()`
* `reset()`

This avoids duplicating logic across multiple components.

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

### Navigate to the Project Folder

```bash
cd your-repository-name
```

### Install Dependencies

```bash
npm install
```

### Run the Application

```bash
npm run dev
```

Open your browser and visit:

```text
http://localhost:5173/
```



## Learning Outcomes

* Understanding React Hooks
* Creating and using Custom Hooks
* Building reusable React components
* Managing component state efficiently
* Structuring React applications

## Author

**Rahul Kumar Singh**

---

If you found this project useful, feel free to star the repository.
