# CuRSe — Course Recommendation System

3rd Year Engineering Software Engineering Project

## Quick Start — UI Demo
1. Extract the `CuRSe_Course_Recommendation_System` folder.
2. Open the folder.
3. Double-click `index.html`.
4. The website opens in your browser.
5. Try Register → Preferences → Recommendations or open Courses.

The frontend demo works without Node.js or MySQL.

## Full-stack setup
Install Node.js and MySQL/XAMPP.

### Database
1. Start MySQL from XAMPP.
2. Open phpMyAdmin.
3. Import `database/curse_db.sql`.
4. It creates database `curse_db`.

### Backend
Open a terminal inside `backend`:
`npm install`
then:
`node server.js`

API:
`http://localhost:5000/api/health`
`http://localhost:5000/api/courses`

If your MySQL root account has a password, edit the password in `backend/server.js`.

## Project modules
Student: registration, login, profile, preferences, search, filtering, recommendations, wishlist and enrollment.
Admin: dashboard, course/user/category management structure.
Recommendation score: Interest 30% + Skill 30% + Career Goal 20% + Rating 10% + Difficulty 5% + Preference 5%.

## Software Engineering
The project is organized for SRS, UML, DFD, ER, testing, LOC estimation and the Waterfall model.

## Approximate LOC target
About 4,050 LOC is the academic project target. Do not add meaningless lines only to force an exact count.
