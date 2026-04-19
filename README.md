# 🌐 Personal Portfolio Website (DevOps Project)

## 📌 Project Overview

This project is a **Personal Portfolio Website** developed using HTML and CSS and integrated with DevOps tools like **Maven, GitHub, and Jenkins**.

The website showcases personal details such as profile, skills, resume, and contact information.

---

## 🚀 Technologies Used

* HTML5
* CSS3
* Apache Maven (Build Tool)
* Git & GitHub (Version Control)
* Jenkins (Continuous Integration)

---

## 📁 Project Structure

```
my-portfolio/
 ├── pom.xml
 ├── src/
 │   └── main/
 │       └── webapp/
 │           ├── index.html
 │           ├── style.css
 │           ├── resume.pdf
 │           └── images/
 │               └── myphoto.jpg
```

---

## ⚙️ Features

* Responsive and clean UI
* Navigation bar with sections
* Profile image display
* Skills section
* Downloadable resume
* Contact information
* Modern professional design

---

## 🔄 DevOps Workflow

1. Developed website using HTML & CSS
2. Converted into Maven web application
3. Uploaded project to GitHub repository
4. Configured Jenkins job to pull code from GitHub
5. Jenkins builds the project using Maven
6. Generated `.war` file for deployment

---

## 🛠️ Build Process (Maven)

To build the project:

```
mvn clean package
```

Output:

```
target/my-portfolio.war
```

---

## 🔁 Continuous Integration (Jenkins)

* Jenkins fetches code from GitHub
* Executes Maven build
* Generates deployable artifact automatically

---

