# Family Travel Tracker App

## Overview
The Family Travel Tracker App is a web application designed to help families keep track of the countries they have visited. Users can add new countries they've visited, view their total count of visited countries, and switch between different family members to see their individual travel records. 

## Features
1. **Add Visited Countries**: Users can add countries they have visited by entering the country name.
2. **View Visited Countries**: Users can view the list of countries they have visited along with the total count.
3. **Switch Users**: Users can switch between different family members to view their individual travel records.
4. **Add New Family Member**: Users can add new family members to track their travel records.

## Technologies Used
- **Express**: Used for building the web server and routing.
- **Body-parser**: Middleware for parsing incoming request bodies.
- **pg**: PostgreSQL client for Node.js.
- **EJS**: Embedded JavaScript templates for rendering HTML pages.
- **HTML/CSS**: Frontend design and styling.
- **PostgreSQL**: Database management system used for storing user data and visited countries.

## Installation
1. Clone the repository:
```bash
git clone
```
2. Install Node.js and npm if not already installed.
3. Install PostgreSQL and set up a database named 'world'.
4. Install dependencies:
```bash
npm install
```

## Setup Instructions
1. Start the server:
```bash
npm start
```
2. Access the application through your web browser at `http://localhost:3000`.

## Database Setup
1. Ensure PostgreSQL is installed and running.
2. Connect to PostgreSQL and create a database named 'world'.
3. Run the SQL script provided in the repository to create the necessary tables (`schema.sql`).

## Usage
1. Upon accessing the application, you will see the list of visited countries for the current user along with the total count.
2. You can switch between different family members using the dropdown menu.
3. To add a new visited country, enter the country name in the input field and click 'Add'.
4. To add a new family member, click on the 'Add New Member' button, enter the name and select a color, then click 'Submit'.




