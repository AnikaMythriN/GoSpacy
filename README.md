# Mini Brand Tracker Web App

The Mini Brand Tracker is a full-stack web application built using ReactJS, NodeJS, and MongoDB.  
It allows users to manage brands and their campaigns efficiently by tracking performance metrics such as spend, impressions, and clicks.  
The system automatically calculates CTR (%) for each campaign and provides a visual representation of campaign spending through charts.  
This project helps marketing teams analyze brand performance and optimize advertising strategies.

##  Features
- Add and manage brand details with name, category, and image.
- Create campaigns with brand name, platform, spend, impressions, and clicks.
- Automatically calculates **CTR (Click-Through Rate)** for every campaign.
- Displays all campaign data in a summary table.
- Generates **spend analysis graphs** for better performance insights.
- Stores all data securely in MongoDB.
- Responsive and user-friendly ReactJS interface.

##  CTR Calculation
CTR (Click-Through Rate) measures how often people click on an ad after seeing it.  
It is calculated using the formula:
CTR (%) = (Clicks / Impressions) × 100
The web app computes this automatically for every campaign and displays it in the campaign summary.

##  Graph Representation
- The application displays a **Spend Chart** that visually represents the total spend per campaign or brand.  
- Helps users quickly identify which campaigns have higher investments and how they perform.
- Built using chart libraries like **Recharts** or **Chart.js** for interactive and dynamic visualization.

##  Tech Stack
- **Frontend:** ReactJS  
- **Backend:** NodeJS + ExpressJS  
- **Database:** MongoDB  
- **Other Tools:** Postman, MongoDB Compass, Recharts / Chart.js
