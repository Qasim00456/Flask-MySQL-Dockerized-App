Flask MySQL Dockerized App

A simple Python Flask application connected to a MySQL database, fully containerized using Docker Compose. This project demonstrates containerization, service-to-service networking, and reproducible deployments.

🚀 Features

Flask Application: Python-based web app displaying MySQL version.

MySQL Backend: Runs in a separate container for persistent storage.

Containerized Architecture: Each service runs in its own container.

Docker Networking: App communicates with MySQL via internal Docker DNS.

Reproducible Deployment: Run the entire stack with a single command.

🧰 Technologies Used

Python 3.x

Flask

MySQL / MariaDB

Docker & Docker Compose

📦 Getting Started
1. Clone the repository
git clone https://github.com/yourusername/flask-mysql-docker.git
cd flask-mysql-docker

2. Start the application stack
docker-compose up --build

3. Access the app

Open your browser at http://localhost:5002
 — it will display the MySQL version.

⚙️ Configuration

MySQL Host: mydb (as defined in docker-compose.yml)

MySQL Root Password: my-secret-pw (can be changed in the Compose file)

Flask App Port: 5002

💡 Key Takeaways

Demonstrates containerization best practices.

Shows service communication between containers using Docker networking.

Can be extended for cloud deployment (AWS ECS, Docker Swarm, Kubernetes).

📄 License

MIT License – feel free to reuse and modify.
