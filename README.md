# ⚖️ Law Awareness Platform

**Law Awareness** is a web platform designed to educate users about their legal rights through informative content, interactive quizzes, and engaging visuals. This platform simplifies complex legal topics and encourages users to be informed, responsible citizens.

---

## 🧠 Key Features

- 📘 **23+ Legal Topics**  
  Comprehensive explanations of laws including:
  - Criminal, Civil, Corporate, Cyber, Labor, Family, Property, RTI, and more.
  - Dual pages for some topics with detailed legal descriptions and scenarios.

- 🧠 **Legal Quizzes**  
  Interactive quizzes for users to test and retain their legal knowledge.

- 📝 **Blog Section**  
  Users can read blogs related to legal awareness and societal issues.

- 👤 **User Authentication**  
  - Login and Registration system
  - Password Reset functionality
  - Score tracking via servlet-based backend

- 🌐 **User-Friendly Design**  
  - Clean UI with icons, images, and animations
  - Well-organized `.html` pages for every law

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Java (Servlets)
- **Server**: Apache Tomcat
- **Database**: MySQL (used in score tracking & login)
- **Tools**: Eclipse IDE / IntelliJ IDEA

---

## 📁 Project Structure

legal/

├── *.html # Individual law pages (civil, criminal, cyber, etc.)

├── *.jpg / *.png # Visual elements and icons

├── style.css, script.js # UI styling and interactivity

│
├── login.html, reset.html # Auth pages

├── blog.html # Blog section

│

├── WEB-INF/

│ ├── web.xml # Servlet configuration

│ └── classes/

│ ├── loginJava.java / .class

│ ├── registerJava.java / .class

│ ├── blogJava.java / .class

│ ├── ResetServlet.java / .class

│ ├── SaveScoreServlet.java / .class

│ └── UserDataServlet.java / .class

│

└── .vscode/ # VS Code settings (optional)



---

## ⚙️ How to Run the Project

1. **Import into IDE**
   - Open Eclipse or IntelliJ
   - Import the project as a **Dynamic Web Project**

2. **Configure Server**
   - Add Apache Tomcat v9 or v10
   - Deploy the project and start the server

3. **Run on Browser**
   - Visit [http://localhost:8080/legal/home.html](http://localhost:8080/legal/home.html)

4. **Database Setup**
   - Create MySQL database (if used)
   - Connect using JDBC in servlet classes
   - Required for login/registration and quiz score tracking

---

## 🔮 Future Enhancements

- 📤 Add file upload for users to share experiences
- 📊 Admin dashboard to moderate blogs and users
- 🌍 Multilingual support (Hindi, Telugu, etc.)
- 📧 Newsletter subscription for latest laws
- 📲 Android App integration

---

