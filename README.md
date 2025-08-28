<br><p align="center"><b>🐳📦🐍 A Realtime Docker Python App on AWS<b></p><br>
<hr>
A simple Flask-based web application containerized with Docker, using a PostgreSQL database, and deployed on AWS ECS with public access enabled via security groups and task definitions. 
<br>
<br> <br>


🚀 Features

- Lightweight Flask web app 


- 🐳 Docker Compose setup with:

  - Web server container

  - PostgreSQL container (with volume + secret support)
  

- 🛠️ Hot-reload during development (whenever there is a change in code, the app automatically reloads without doing it manually)

- ☁️ Deployed on AWS ECS with:

  - Custom Security Groups allowing HTTP traffic (port 8080)

  - ECS Clusters and Task Definitions

  - Public access via Fargate
  
- 🔐 Uses Docker secrets for sensitive environment values

<br>


🛠️ Tech Stack
- Python 3.10.2
- Flask
- PostgreSQL
- Docker / Docker Compose
- AWS ECS / IAM / Security Groups

<br>


🐳 My Docker Hub
https://hub.docker.com/u/vforvog


<br><p align="center"><b>Simulation</b></p><br>

![Lex Demo](SimulationVideo/gif.gif)
