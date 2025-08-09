# 🚘 AutoDealer Platform — Django + Express + MongoDB

This project is a full-stack web application for car dealership review and management. It includes:

- A Django frontend for user interaction (login, sign-up, view dealers, post reviews).
- An Express.js + MongoDB backend API for dealer data and reviews.

---

## 📦 Project Structure

/client → Django project (Frontend)
|-- dealership → Django app
/server → Express + MongoDB (Backend API)

yaml
Copy
Edit

---

## 🌐 Live Application URLs

- 🚀 **Deployed Frontend:** `https://your-django-deploy-url.com`
- 🧠 **Sentiment API:** `https://your-backend-api-url.com/api/analyze`
- 📦 **GitHub Repo:** `https://github.com/your-username/autodealer-platform`

---

## 🔧 Technologies Used

- **Frontend:** Django, HTML/CSS, Bootstrap
- **Backend:** Node.js, Express, MongoDB, Mongoose
- **Authentication:** Django auth
- **DevOps:** GitHub CI/CD, Deployment via Render/Heroku

---

## 🚀 Features

### 🧭 Django Frontend:
- About Us / Contact Us pages
- User Registration / Login / Logout
- View dealers by state
- View dealer details + reviews
- Add new reviews (with Sentiment Analysis)

### 🔗 Express + Mongo Backend:
- View all dealers (`/api/dealers`)
- View dealer by ID (`/api/dealers/:id`)
- View reviews for a dealer (`/api/reviews/:dealerId`)
- Filter dealers by state (`/api/dealers/state/:state`)
- Basic Sentiment Analysis endpoint

