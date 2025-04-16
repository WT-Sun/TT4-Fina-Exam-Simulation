# TT4 Final Exam Simulation

## ✍️ Part I – Multiple Choice Questions (20 questions)

Each question is worth 0.5 points. Total: 10 points  
**Your selected answers are marked in bold.**

### 🐳 Docker

1. What is Docker?  
   - A) A relational database  
   - B) A web server  
   -**C) A container platform for creating and managing environments**  
   - D) A frontend framework  

2. Which command builds a Docker image from a Dockerfile?  
   - A) docker pull  
    -**B) docker build**  
   - C) docker start  
   - D) docker run  

3. What is docker-compose used for?  
   - A) Compressing files  
   - B) Creating multiple Docker images  
     -**C) Orchestrating multiple containers**  
   - D) Backing up volumes  

4. What does the command docker ps do?  
   - A) Create containers  
   - B) List images  
     -**C) Show running containers**  
   - D) Stop all containers  

### 🌿 Git / GitHub

5. What does git clone do?  
   - A) Create a new repository  
     -**B) Download a copy of a remote repository**  
   - C) Delete a local repo  
   - D) Update a remote repo  

6. What is a “commit” in Git?  
   - A) Send files to GitHub  
   - B) Merge two branches  
     -**C) Save changes locally in Git**  
   - D) Delete modified files  

7. Which command pushes changes to GitHub?  
     -**A) git push**  
   - B) git pull  
   - C) git add  
   - D) git commit  

8. What is the purpose of a .gitignore file?  
   - A) Ignore repositories  
     -**B) Ignore files/folders from being committed**  
   - C) Protect branches  
   - D) Manage GitHub access  

### ⚙️ .NET Core

9. Which command creates a new Web API project in .NET Core?  
   - A) dotnet build api  
     -**B) dotnet new webapi**  
   - C) dotnet run api  
   - D) dotnet create api  

10. Which file configures services and middleware in .NET Core?  
     -**A) Startup.cs**  
   - B) Program.cs  
   - C) App.cs  
   - D) Main.cs  

11. Which package enables CORS in a .NET API?  
   - A) Microsoft.AspNetCore.Routing  
     -**B) Microsoft.AspNetCore.Cors**  
   - C) Microsoft.AspNetCore.Mvc.NewtonsoftJson  
   - D) System.Net.Http  

12. What does the [HttpGet] attribute do in a Controller?  
   - A) Send data  
   - B) Update a resource  
     -**C) Handle a GET request**  
   - D) Delete data  

### ⚛️ Frontend Frameworks

13. In Angular, what is a component?  
   - A) An external module  
   - B) A backend service  
     -**C) A part of the UI**  
   - D) A build script  

14. In React, what is useState?  
   - A) A type of component  
     -**B) A hook to manage state**  
   - C) A hook for API requests  
   - D) A type of props  

15. What does VueJS use to loop through items?  
   - A) *each  
     -**B) v-for**  
   - C) loop  
   - D) ng-for  

16. In Svelte, how do you declare a reactive variable?  
   - A) @reactive  
   - B) this.reactive  
     -**C) $:**  
   - D) var:  

### 💡 General Concepts

17. What is CRUD?  
   - A) A type of database  
   - B) A security pattern  
     -**C) Create, Read, Update, Delete**  
   - D) A REST API format  

18. How do you install dependencies in Angular?  
   - A) ng add  
   - B) ng install  
     -**C) npm install**  
   - D) ng dependencies  

19. What is the purpose of package.json?  
   - A) Save logs  
   - B) Configure production builds  
     -**C) Manage project dependencies**  
   - D) Create containers  

20. How do you start services using Docker Compose?  
   - A) docker-compose run  
   - B) docker-compose build  
   - C) docker-compose start  
     -**D) docker-compose up**  


---

## 💻 Part II – Final Project (Task Manager)

### ✅ Project Features

- Fullstack Task Manager App
- ASP.NET Core Web API backend
- React frontend with Axios
- Docker Compose orchestration

### 📦 Backend – ASP.NET Core API

- Entity: `TaskItem { Id, Title, Description, Completed }`
- Frameworks: ASP.NET Core + EF Core + SQLite
- Exposed at `http://localhost:5000/api/tasks`
- Supports CRUD operations

### 🌐 Frontend – React

- Fetches tasks from API
- Add, delete tasks
- Simple form UI




📝 *Submitted by: Sun WenTao*  
📆 *Exam Simulation for TT4 - 2025*
