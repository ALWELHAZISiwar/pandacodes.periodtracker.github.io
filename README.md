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


# 🌸 Period Tracker App

## Overview
The Period Tracker App is designed to help users track their menstrual cycles, symptoms, and moods while providing valuable insights and advice, especially for those with PCOS. 

## 🌟 Functionalities and Features

### 1. 👤 User Registration & Login
- 🔐 **Sign up, Log in, Log out**
- 🛠️ Password reset and recovery
- 🌐 Optional social login (Google/Facebook)
- ⚙️ Profile settings (update name, email, etc.)

### 2. 🩸 Menstrual Cycle Tracking
- 🗓️ Track period **start and end dates**
- 📅 **Predict** the next period and fertile window
- 🟢 **Cycle Status Indicators:**
  - **Normal**: Consistent cycle length
  - **Late**: Missed period by a few days
  - **Irregular**: Large fluctuations across cycles

### 3. 🌈 Symptom & Mood Logging
- 📊 Daily mood tracking (happy, sad, moody, etc.)
- 🩹 Symptom tracking (cramps, bloating, headaches, etc.)
- 📈 Intensity levels for each symptom
- 🗓️ Insights and history of symptoms over time

### 4. 🥗 Health & Wellness Recommendations
- 💡 Tips for managing PMS and cramps
- 🍏 Dietary suggestions based on cycle phases
- 🧘‍♀️ Exercises or relaxation routines
- 🌼 **PCOS Section:**
  - Lifestyle advice for users with PCOS
  - Symptom management (e.g., managing insulin resistance, stress, etc.)

### 5. 📈 Statistics & Cycle Analytics
- 📅 Average cycle length and period duration
- 📉 Comparison with a typical cycle (28 days)
- 🔍 Analysis of cycle trends (Is it getting longer or shorter?)
- 🟢 **Cycle Type:**
  - **Normal**: Regular patterns within a small range
  - **Late**: Noticeable delays in periods
  - **Irregular**: Highly unpredictable cycles
- 📝 **Advice and Recommendations:**
  - Tips on regulating the cycle
  - Health alerts for abnormal patterns (e.g., consult a doctor if needed)
  - Nutrition and exercise tips based on analytics
- 📊 Visual insights: Graphs and charts for easy interpretation

### 6. 📅 Calendar View
- 📅 Visual calendar to mark cycle days
- 🌟 Highlight predicted periods and ovulation days
- 🔄 Option to view monthly or yearly insights

### 7. 💕 PCOS Support Section
- 🗒️ Track PCOS-specific symptoms like mood swings, cravings, etc.
- 📈 Insights tailored for PCOS management
- 📋 Progress reports (e.g., symptom trends)
- 🌱 Wellness tips like managing stress and improving sleep quality

### 8. 📊 Data Analytics & Reports
- 📄 Export cycle data to PDF or CSV
- 📊 Detailed PCOS insights for users who opt in

### 9. 🔔 Notifications & Alerts
- ⏰ Custom alerts for irregular or missed periods
- 🔔 Notifications for tracking PCOS-specific symptoms
- 📅 Reminders to log symptoms or moods

### 10. 🔒 Privacy & Security
- 🔐 Data encryption for sensitive information
- 🗑️ Option to delete user data
- 📜 Clear privacy policy explaining data usage

## 🚀 Getting Started
1. Clone the repository.
2. Install the necessary dependencies.
3. Configure your environment.
4. Run the application.

## 📝 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

