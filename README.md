# 🧮 Average Calculator HTTP Microservice

This project is an HTTP microservice that calculates the moving average of numbers received from a third-party API. It includes:

- A backend built with *Node.js + Express*
- A frontend built with *React + Tailwind CSS*
- APIs to support number types: Prime (p), Fibonacci (f), Even (e), and Random (r)

---

## 🔧 Features

- Fetches numbers from test server based on type
- Stores up to 10 unique recent values (sliding window)
- Ignores duplicates and API responses taking longer than 500ms
- Calculates and returns the average with window history
- Includes a React UI to visualize the average and states

---

## 🛠 Tech Stack

- Backend: Node.js, Express, Axios
- Frontend: React, Tailwind CSS, ShadCN UI
- Deployment Ready: Docker, GitHub

---

## 📦 API Endpoint (Backend)
