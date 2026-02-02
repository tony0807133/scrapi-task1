Task 1 – Strapi Local Setup & Exploration
📌 Overview

This repository contains Task 1 of the onboarding assignment.
The goal of this task is to set up Strapi locally, explore its structure, access the Admin Panel, and create a sample content type.

🛠️ Tech Stack

Node.js (v20.x – v24.x)

npm

Strapi (Headless CMS)

Git & GitHub

Linux (Hyprland / Arch Linux)

📥 Task Requirements

Clone the official Strapi repository

Run Strapi locally

Explore project folder structure

Start the Admin Panel

Create a sample content type

Push setup to GitHub

Document all steps in README.md

Record a Loom video

🔗 Official Strapi Repository

👉 https://github.com/strapi/strapi

⚙️ Local Setup Steps
1️⃣ Clone the Strapi Repository
git clone https://github.com/strapi/strapi.git

2️⃣ Create Strapi Application
npx create-strapi-app task1-app-strapi --quickstart
cd task1-app-strapi


⚠️ Important Note
Strapi supports Node.js >=20.0.0 and <=24.x.x
Make sure the correct Node version is installed before running the command.

3️⃣ Start Strapi Development Server
npm run develop


Strapi will start on:

http://localhost:1337

🔐 Admin Panel

Access the admin panel using:

http://localhost:1337/admin


Steps:

Create admin user

Login to the dashboard

Explore available features

🧱 Project Folder Structure

Main folders explored inside task1-app-strapi:

task1-app-strapi/
├── config/        # Application configuration
├── src/           # APIs, content-types, controllers
├── database/      # Database files
├── public/        # Public assets
├── package.json   # Project dependencies

🧩 Sample Content Type Creation

Steps followed:

Open Admin Panel

Navigate to Content-Type Builder

Create a new Collection Type (Example: Article)

Add fields:

Title (Text)

Description (Rich Text)

Published Date (Date)

Save and build

✔ Sample content type created successfully

📂 Git & GitHub Workflow
Initialize Git Repository
git init
git add .
git commit -m "Task-1: Strapi local setup and admin panel exploration"

Push to GitHub
git branch -M main
git remote add origin https://github.com/<your-username>/<repository-name>.git
git push -u origin main


✅ Task Status

Task 1 completed successfully ✅

All required objectives were achieved:

Strapi running locally

Admin panel accessed

Content type created

Code pushed to GitHub

Documentation completed

