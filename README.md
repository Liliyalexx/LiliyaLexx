# Liliya Fedyurina <img src="https://github.com/user-attachments/assets/1018e86d-3abc-4e3b-ab3c-31fa623211c4" alt="profile" width="45" height="45"/>


📍 Lynnwood, US 98036  
📧 liliya.fedyurina@gmail.com  
📞 734-623-3211  

## Professional Summary

Full-stack software Engineer with an economics background, specializing in JavaScript, Java, and AI-integrated applications. Combines technical expertise with business analytics skills to deliver data-driven solutions. Certified in both software development and project management.

🔗 [LinkedIn](https://linkedin.com/in/liliya-fed) | [GitHub](https://github.com/Liliyalexx)

## 🛠 Technical Skills 

<h2>💻 Languages & Frameworks</h2>

<p align="center">
  <img src="https://img.shields.io/badge/-Java-007396?logo=java&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-SQL-4479A1?logo=postgresql&logoColor=white&style=for-the-badge" />
</p>

<h2>📦 Frameworks & Libraries</h2>

<p align="center">
  <img src="https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=black&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-Node.js-339933?logo=node.js&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-Express-000000?logo=express&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-Django-092E20?logo=django&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-EJS-8e44ad?logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-Sass-CC6699?logo=sass&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-Spring%20Boot-6DB33F?logo=spring-boot&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-WebLogic-2C2255?logo=oracle&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-Drools-EE0000?logo=redhat&logoColor=white&style=for-the-badge" />
</p>

<h2>🛢️ Databases & Tools</h2>

<p align="center">
  <img src="https://img.shields.io/badge/-MongoDB-47A248?logo=mongodb&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-PostgreSQL-4169E1?logo=postgresql&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-AWS-232F3E?logo=amazon-aws&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-Git-F05032?logo=git&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-Postman-FF6C37?logo=postman&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-Heroku-430098?logo=heroku&logoColor=white&style=for-the-badge" />
</p>

<h2>🤖 AI / Machine Learning</h2>
<p align="center">
  <img src="https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white&style=for-the-badge" />
  <img src="https://img.shields.io/badge/DeepAI-000000?logo=deepai&logoColor=white&style=for-the-badge" />
</p>


# Adobe Colorblind Analyzer 🌈
**An internal tool for web developers & UX/UI designers to create accessible content for colorblind users**
[Video](https://youtu.be/Sh8fya9IHlE)
[Colorblind Analyze](https://colorblind-analyzer-a495ff639427.herokuapp.com/)
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7b/Adobe_Systems_logo_and_wordmark.svg/60px-Adobe_Systems_logo_and_wordmark.svg.png" width="30" alt="Adobe Logo">
---
## 🎯 Why This Matters for me
"As someone who is 80% deaf and cannot hear high-frequency sounds like children’s or women’s voices, I understand what it’s like to miss important information others take for granted. Colorblind users experience a similar kind of ‘invisible barrier’ — they can’t perceive certain colors that designers often rely on. This tool helps bridge that perceptual gap and ensures no one is left out of the experience."

## 🛠 Technical Implementation

def simulate_colorblindness(color, colorblind_type):
    r, g, b = [x / 255.0 for x in color]
    
    if colorblind_type == 'protanopia':
        new_r = 0.567 * g + 0.433 * b
        new_g = 0.558 * g + 0.442 * b
        new_b = 0.242 * g + 0.758 * b
    elif colorblind_type == 'deuteranopia':
        new_r = 0.625 * r + 0.375 * b
        new_g = 0.7 * r + 0.3 * b
        new_b = 0.3 * r + 0.7 * b
    elif colorblind_type == 'tritanopia':
        new_r = 0.95 * r + 0.05 * g
        new_g = 0.433 * r + 0.567 * g
        new_b = g
    else:
        gray = 0.299 * r + 0.587 * g + 0.114 * b
        new_r = new_g = new_b = gray
    
    return (int(new_r * 255), int(new_g * 255), int(new_b * 255))

## 🖥 Tech Stack
Frontend: Django Templates, Bootstrap 5

Backend: Python, Django

Vision: Selenium, PIL (via Pillow), Colorsys

Deployment: Heroku with Selenium buildpacks
## 🌐💬 *Visuality* Social Media with AI-generated content + Weather API integration

[![Live Demo](https://img.shields.io/badge/Live_Demo-Heroku-430098?style=flat-square)](https://social-media-visuality-6b16f66b0b08.herokuapp.com/)

### Tech Highlights:
- **Architecture**: MVC with Mongoose schemas
- **Innovation**: DeepAI image generation engine
- **Security**: Passport.js authentication
- **UI**: Tailwind CSS responsive design
## 🥗 Mindful Meals is a full-stack application designed to help users find restaurants that cater to specific dietary needs.
[![Live Demo](https://img.shields.io/badge/Live_Demo-Netlify-00C7B7?style=flat-square)](https://mindful-meals.netlify.app/sign-in)
[Backend](https://github.com/Liliyalexx/Mindful-Meals-Backend)
[Frontend](https://github.com/Liliyalexx/Mindful-Meals)
Features
- **Dietary-Specific Search**: Find restaurants based on dietary preferences (gluten-free, vegan, vegetarian, etc.)
- **User Authentication**: Secure sign-up, login, and logout functionality
- **Favorites System**: Save your favorite restaurants for quick access
- **Interactive Map**: Visualize restaurant locations on a map
- **Review Filtering**: See reviews that specifically mention your dietary preference
- **Responsive Design**: Works across desktop and mobile devices*

## 🎮❓🏆 Quiz Game with AI-generated questions
[![Live Demo](https://img.shields.io/badge/Live_Demo-Quiz_Game-FFA500?style=flat-square)](https://liliyalexx.github.io/quiz_Game/)
*Quiz application that uses AI to generate questions based on user-selected topics. The game includes a timer, character selection for the time, background music, and sound effects to enhance the user experience.*

- **Topic Selection** Users can input a topic (e.g., "AI", "History", "Science").
The application maps the topic to a category and fetches relevant questions.
- **Character Selection**
Users can choose a character (e.g., 🐶, 🐱) to represent timer during the quiz.
- **AI-Generated Questions** Questions are generated dynamically using the OpenAI API.
Each question includes 4 options with one correct answer and 2 options with true or false answers.
- **Timer** A 20-second timer is displayed for each question. If the user doesn't answer in time, the question is marked as incorrect.
- **Sound Effects** Correct answers trigger a "ding" sound. Incorrect answers or timeouts trigger a "wrong" sound.
- **Score Tracking** The user's score is displayed at the end of the quiz.
- **Responsive Design** The application is designed to work on both desktop and mobile devices.

## 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=LiliyaLexx&show_icons=true&theme=radical" alt="GitHub Stats" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=LiliyaLexx&layout=compact&theme=radical" alt="Top Languages" />
</p>

## Professional Experience
### **SWE Apprentice** @ Adobe *(Feb-May 2025)*  
- Built AI quiz application with OpenAI integration 
- Built AI Social Media application with image-generating  OpenAI integration  
- Mindful Meals project is built using the MERN stack (MongoDB, Express.js, React, Node.js) and leverages the Yelp Fusion API to provide real-time restaurant data and Leaflet – Interactive maps.
  
### **Software Engineer** @ Anthem Blue Cross Blue Shield  
*(Infosys Project | Aug 2022-Aug 2023)*  
- Developed 25+ healthcare portal features using Java/Spring Boot/DRL  
- Streamlined workflows by 30% through JIRA optimization  

### **Software Engineer** @ Toyota Motors  
*(Infosys Project | Mar-Sep 2022)*  
- Enhanced Toyota.com components with jQuery/Spring Boot  
- Implemented Oracle DB solutions for inventory management  

## Education

🎓 **General Assembly**  
Full-Stack JavaScript & Python (Django) | Feb-May 2025  

🎓 **Per Scholas**  
Software Engineering (Valedictorian) | Apr-Aug 2024  

🎓 **California Institute of Technology (Caltech)**  
PGP Full Stack Development | Dec 2020-Jan 2022  

🎓 **State University of Economics**  
B.A. Economics/Marketing  
*Thesis: Economics/Marketing*  

## Certifications
✅ Google Project Management (2025)  
✅ Meta Backend Professional (2024)  
