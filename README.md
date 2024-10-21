# 📅 Period Tracker Web App

A simple web application to help users track their menstrual cycles, identify patterns, and provide insights into cycle health.  
It includes a statistics feature for tracking regularity, detects abnormalities like late or irregular periods, and offers personalized advice for users with PCOS.
## 🌟 Features

- **Cycle Tracking:** Log and monitor menstrual cycle dates.  
- **Statistics Overview:** Calculate average cycle length and indicate if it's normal, late, or irregular.  
- **PCOS Support:** Dedicated section with tips and resources for users managing PCOS.  
- **Personalized Insights:** Provides recommendations based on tracked data.  
- **User-Friendly Interface:** Simple and accessible design for easy use.
## 🛠️ Technologies Used

- **Frontend:** HTML, CSS, JavaScript, React.js  
- **Backend:** Node.js, Express  
- **Database:** MongoDB  
- **Version Control:** Git, GitHub  
- **Deployment:** Heroku, Netlify
## 📝 Functionality Description

The Period Tracker Web App allows users to:

- **Log Menstrual Cycles:** Users can easily input the start and end dates of their periods.
- **View Cycle History:** Access a calendar view to see past cycles and predict future ones.
- **Track Symptoms:** Users can record symptoms experienced during their cycles to identify patterns.
- **Receive Notifications:** Set reminders for upcoming periods and ovulation.
- **Generate Reports:** View cycle statistics and generate reports on cycle health and regularity.
## 🏗️ Project Architecture

The application follows a standard MVC (Model-View-Controller) architecture:

- **Model:**  
  Represents the data structure, including user profiles, menstrual cycle logs, and PCOS-related information.

- **View:**  
  The user interface built with React.js, providing a responsive design for seamless interaction.

- **Controller:**  
  Handles user input and updates the model, including API requests and data processing.

### Folder Structure

/period-tracker │ ├── /client # Frontend files │ ├── /public # Static files │ ├── /src # React components and assets │ └── App.js # Main application file │ ├── /server # Backend files │ ├── /models # Database models │ ├── /routes # API routes │ └── server.js # Entry point for the backend │ └── README.md # Project documentation
## 🚀 Usage

1. **Register/Login:** Users can create an account or log in to access their cycle tracking features.
2. **Dashboard:** After logging in, users will be directed to their dashboard, where they can view their cycle history and upcoming cycle predictions.
3. **Log a New Cycle:** Navigate to the "Log Cycle" page to enter the start and end dates of the menstrual cycle and any associated symptoms.
4. **View Statistics:** Access the "Statistics" section to view cycle length averages and regularity assessments.
5. **PCOS Resources:** Users with PCOS can visit the dedicated section for tailored advice and support.
