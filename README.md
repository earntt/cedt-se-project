# Software Engineering Website Project

This repository contains the source code and documentation for a web application project developed as part of the **Software Engineering** course. The project showcases the application of software development principles and modern web technologies.

---

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup](#setup)

---

## Overview
The project is a web application designed to solve the problem of managing online job fair registrations by providing a platform for both companies and participants to register, browse, booking and manage job fair events efficiently.

---

## Features
- **User Authentication**: Secure login and registration.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Event Management**: Companies can create and manage job fair events. Participants can book and manage their own job fair sessions.
- **Participant Registration**: Easy registration process for attendees.

---

## Technologies Used
- **Frontend**: JavaScript, TypeScript, CSS (Tailwind, React, Next.js)
- **Backend**: JavaScript, Node.js
- **Database**: MongoDB
- **Testing**: Jest, Cypress

---

## Setup
### 1. Docker
1. Install [docker](https://www.docker.com/products/docker-desktop/) and [Docker Compose](https://docs.docker.com/compose/install/) if you don't have them yet.
2. Run docker compose (-d is for detach)
    ```sh
      docker compose up
    ```
  
3. (optional) if you want to **rebuild** it
    ```sh
      docker compose down
      docker compose up --build
    ```

### 2. NPM
   - **Frontend**
        1. Navigate to frontend directory
            ```sh
            cd Frontend
            ```
        2. Install depencies
            ```sh
            npm install
            ```

   - **Backend**
        1. Navigate to backend directory
            ```sh
            cd Backend 
            ```
        2. Install depencies
            ```sh
            npm install
            ```

## Usage
   - **Frontend**
        1. Start the frontend development server
            ```sh
              npm start
            ```
        2. Open your browser and visit http://localhost:3000

   - **Backend**
        1. Start the backend server
            ```sh
              npm start
            ```
        2. Open your browser and visit http://localhost:5000 and `document on`: http://localhost:5000/api-docs
