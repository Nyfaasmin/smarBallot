# 🗳️ Smart Ballot - Online Voting System App

**Smart Ballot** is a secure and efficient mobile application designed to allow **remote voting** for individuals who cannot vote in person. Built using **Android Studio** with **SQLite** for local data storage, this app was developed during a 24-hour Appathon, where it proudly won the **3rd Prize**, led by **Pathan Nyfa Asmin**.

---

## 🚀 Features

- 🔐 Secure login & voter authentication  
- 🧑‍💼 Admin panel to manage elections and candidates  
- 🗳️ One-time vote casting per verified user    
- 🧾 Voter verification using local records  
- 📱 Simple and intuitive user interface  

---

## 📖 How the App Works

1. **User Registration / Login**  
   - Users register with their name, phone number, and voter ID.  
   - Existing users log in using saved credentials stored in SQLite.  

2. **Voter Verification**  
   - Admin verifies voters based on preloaded voter ID list in the local database.  

3. **Election Dashboard**  
   - Users can view active elections and candidate details.  
   - A countdown timer is shown for ongoing elections.  

4. **Casting a Vote**  
   - Voters select a candidate and cast their vote.  
   - Votes are recorded securely in the SQLite database.  
   - Users cannot vote again once submitted.  

5. **Admin Panel**  
   - Admin can:  
     - Add/edit/delete candidates and elections  
     - View and manage voter list  
     - Monitor vote counts  
     - Start or stop elections  

6. **Logout & Session Management**  
   - App maintains session data locally and logs out users after inactivity.  

---

## 🛠️ Tech Stack

- **Frontend:** Android Studio (Java)  
- **Backend / DB:** SQLite (local database)  
- **UI Design:** XML (Material Design Components)  

---

## 📸 Screen Recording

> https://github.com/user-attachments/assets/f3ba0ffd-a6b2-4b2c-aa76-fe67b4ff0252

---

## 🏆 Achievements

- 🥉 **3rd Prize** winner in a 24-hour Appathon  
- 👩‍💻 Led by **Pathan Nyfa Asmin**  
- ⚡ Completed in a single day with full functionality  

---

## 👥 Team Members

This project was built with dedication and teamwork by the following members:

- 👩‍💻 **Pathan Nyfa Asmin** – Team Leader, Android Developer, Logic & Database Handling 
- 👩‍💻 **[Tanuja Polamuri]** – UI/UX Designer  
- 👨‍💻 **[Hasini Thathapudi]** – Testing & Documentation

---
## 📦 Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/smart-ballot.git
2. Open the project in Android Studio.
3. Build and run the app on an emulator or physical device.
4. The database initializes automatically on first launch.


🔮 Future Enhancements:
  🌐 Integration with online servers for large-scale deployment
  🔐 Biometric authentication for voters
  🧠 Fraud detection system using AI
  📤 Export vote results to CSV or PDF


👩‍💻 Developer Info:
    Pathan Nyfa Asmin, B.Tech in Computer Science Engineering
    📧 Email: nyfa.pathan@gmail.com
    🔗 LinkedIn: http://www.linkedin.com/in/nyfa-asmin-713838255
    🌐 Portfolio: https://legendary-semifreddo-4127d0.netlify.app/



