<p align="center">
  <img src="./img.png" alt="Project Banner" width="100%">
</p>

# [Project Name] 🎯

## Basic Details

### Team Name:  Codex

### Team Members
- Member 1: Ankitha S - Tkm college of Engineering,Kollam
- Member 2: Salabha Krishnan - Tkm college of Engineering,Kollam

### Hosted Project Link
[mention your project hosted link here]

### Project Description
Quick Travel is a real-time traffic disruption reporting platform where users can report accidents, roadblocks, railway crossings, or events. These reports are displayed live on a map so nearby users can avoid delays and plan smarter routes.

The system combines crowdsourced data + live visualization to improve urban travel decisions.

### The Problem statement
Urban commuters face unexpected delays due to:

Accidents

Roadblocks

Railway crossings

Public events

Current map apps show traffic density but don’t allow users to report local disruptions quickly.

### The Solution
Quick Travel allows users to:

Report disruptions instantly

View live reports on a map

Filter disruptions by location

Clear outdated reports automatically

This creates a community-powered real-time traffic awareness system.

---

## Technical Details

### Technologies/Components Used

**For Software:**
Languages used: JavaScript

Frameworks used: React, Express.js

Libraries used: Leaflet, React-Leaflet, Axios

Database: MongoDB

Tools used: Git, VS Code, Postman, npm, Verce

**For Hardware:**
Not applicable (Web-based project)

---

## Features

Live map showing disruption markers

Report submission form with instant update

Search disruptions by location

Auto-expiry of old reports

Backend API storing reports in database

Clean responsive UI for hackathon demo

## Implementation

### For Software:

#### Installation
# Frontend
cd frontend
npm install

# Backend
cd backend
npm install


#### Run
```bash
# Run backend
cd backend
npm start

# Run frontend
cd frontend
npm start

Frontend runs on:http://localhost:3000
Backend runs on:http://localhost:5000
---

## Project Documentation

### For Software:

#### Screenshots (Add at least 3)

<img width="1912" height="956" alt="image" src="https://github.com/user-attachments/assets/10b7024d-f595-4b4b-9b81-46adbc3e0a26" />
Home page initially

<img width="1917" height="788" alt="image" src="https://github.com/user-attachments/assets/b3617c9d-9b98-4751-9209-206089313105" />
reporting the traffic

<img width="1057" height="890" alt="image" src="https://github.com/user-attachments/assets/0b6749cb-121d-447b-a5c6-3698443d8e7a" />
You can see reported places and also for multiple search. You can use maps to find them.


#### Diagrams

**System Architecture:**

![Architecture Diagram](docs/architecture.png)
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/43115e33-1292-41e6-9374-a6511321240a" />
The system follows a client–server architecture. The frontend handles user interaction, the backend processes requests and communicates with the database. APIs are used to exchange data between components.

**Application Workflow:**

![Workflow](docs/workflow.png)
*Add caption explaining your workflow*

---

### For Hardware:

#### Schematic & Circuit

![Circuit](Add your circuit diagram here)
*Add caption explaining connections*

![Schematic](Add your schematic diagram here)
*Add caption explaining the schematic*

#### Build Photos

![Team](Add photo of your team here)

![Components](Add photo of your components here)
*List out all components shown*

![Build](Add photos of build process here)
*Explain the build steps*

![Final](Add photo of final product here)
*Explain the final build*

---

## Additional Documentation

### For Web Projects with Backend:

#### API Documentation

**Base URL:**  http://localhost:5000/api

##### Endpoints

**GET /api/endpoint**
- **Description:** Fetch all disruption reports
[
  {
    "_id": "123",
    "type": "Accident",
    "location": "Chennai",
    "description": "Minor collision",
    "lat": 13.08,
    "lng": 80.27
  }
]

**POST /api/endpoint**

{
  "type": "Roadblock",
  "location": "Kollam",
  "description": "Construction work",
  "lat": 8.893,
  "lng": 76.614
}
### Response Example

```json
{
  "message": "Report saved successfully"
}
```
---



## Project Demo

### Video
https://drive.google.com/file/d/1PMyV5LofJ_F4QIWY9Yviv83lKg2x8Tsp/view?usp=sharing

### Demo Video Explanation

The demo video showcases the working of the Quick Travel traffic monitoring platform.

It demonstrates how users can report real-time disruptions such as accidents, railway crossings, roadblocks, and public events through the reporting form. Once submitted, the disruption appears instantly on the live map, allowing other users to view and track traffic issues in their area.

The video highlights:
- Real-time disruption reporting
- Interactive map visualization of incidents
- Search and filtering of disruptions by location
- Backend API communication for storing reports
- MongoDB database integration for persistent storage

Overall, the video demonstrates the complete workflow from user input to data storage and visualization, showcasing both frontend interactivity and backend data handling.

### Database Used: MongoDB

MongoDB is a NoSQL document-based database used to store traffic disruption reports in this project.

Instead of storing data in tables like traditional SQL databases, MongoDB stores data as JSON-like documents. This makes it highly flexible and suitable for dynamic applications where data structures may evolve over time.

In the Quick Travel system, MongoDB is used to:
- Store reported disruptions with location, type, and description
- Maintain timestamps for each report
- Allow quick retrieval of reports for map visualization
- Enable scalable storage for large amounts of real-time data

MongoDB’s speed, flexibility, and ease of integration with Node.js made it an ideal choice for this real-time traffic monitoring application.


## AI Tools Used (Optional - For Transparency Bonus)

If you used AI tools during development, document them here for transparency:

**Tool Used:**  GitHub Copilot,ChatGPT

**Purpose:**
Assisted in development and debugging of the project
- Generated boilerplate React components
- Helped debug API integration issues
- Assisted with backend route structure
- Suggested UI improvements and styling ideas
- Helped create documentation and diagrams

**Key Prompts Used:**
- "Create a backend API endpoint to save traffic disruption reports"
- "Debug why my React frontend fetch request is failing"
- "Improve UI design for report submission page"
- "Create system architecture diagram for a MERN stack project"

**Percentage of AI-generated code:** ~20–30%

**Human Contributions:**
- Overall project idea and architecture design
- Map integration and report logic
- Frontend layout and feature implementation
- Backend API creation and testing
- Deployment setup and configuration

## Team Contributions

- Ankitha: Frontend development, map integration, UI styling, deployment setup
- Salabha: Backend API development and database handling
- Ankitha and Salabha: Testing, debugging, documentation, and diagrams

---

## License


This project is licensed under the MIT License - see the LICENSE file for details.

**Common License Options:**
MIT License

Copyright (c) 2026 [Your Name or Team Name]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.


Made with ❤️ at TinkerHub
