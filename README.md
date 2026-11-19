# Full Stack Application Development Capstone Project

Repository name: xrwvm-fullstack_developer_capstone
Project name: Full Stack Application Development Capstone Project

IBM Full Stack Software Developer Professional Certificate capstone. The app is a car dealership portal: customers can browse dealerships, filter them by state, read reviews and post their own review.

## What is in this repo

- Django project (server/djangoproj, server/djangoapp): user login, logout and register, car makes and models, proxy views to the back end services
- React front end (server/frontend): Dealers page, Dealer detail with reviews, Post Review form, Register page
- Static pages: About Us and Contact Us (server/frontend/static)
- Express and MongoDB back end for dealers and reviews (server/database)
- Sentiment analyzer microservice (Code Engine)
- GitHub Actions workflow that lints Python and JavaScript (.github/workflows/main.yml)

## Run it locally

1. Start the database services: cd server/database && docker compose up
2. Start the Django server: cd server && python manage.py runserver
3. Open http://localhost:8000
