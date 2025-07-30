

````markdown
### 💻 Laptop Price Prediction System (Dockerized 🐳)

This is a practice project combining **Machine Learning** and **Docker**. It predicts laptop prices using a pre-trained regression model and is containerized using Docker for ease of deployment.

The main goal is to demonstrate:
- ML model packaging and deployment using Docker
- Creating a reusable Docker image
- Running a Streamlit-based ML app in a container

---

## 📦 Features

- Predict laptop prices using system specs
- Pre-trained ML model (Linear Regression)
- Simple and interactive Streamlit UI
- Fully containerized Docker application
- Public Docker Hub image available

---

## 🐋 Run the App Using Docker (Pull from Docker Hub)

No need to install dependencies or clone the project manually. Just pull and run the Docker image using the command below.

### ✅ Prerequisite

- Docker must be installed  
  👉 [Install Docker](https://docs.docker.com/get-docker/)

### 🔧 Pull and Run the Docker Image

```bash
docker run -p 8501:8501 bishal521/laptopprice
````

Then, open the app in your browser at:

```
http://localhost:8501
```

✅ That’s it! You’re running the Laptop Price Prediction app inside Docker.

---

## 🔨 Run Locally by Building the Image (Optional)

If you want to build the Docker image yourself:

```bash
git clone https://github.com/your-username/laptop-price-prediction-ml-docker.git
cd laptop-price-prediction-ml-docker
docker build -t laptopprice .
docker run -p 8501:8501 laptopprice
```

---


---


## 🔗 Docker Hub Repository

The Docker image is hosted publicly and can be accessed here:
👉 [Docker Hub – bishal521/laptopprice](https://hub.docker.com/repository/docker/bishal521/laptopprice)

---

## 🌱 Purpose of This Project

This project is built **for learning and practicing**:

* Docker containerization
* Building and deploying ML apps
* Streamlit integration with Docker
* Docker Hub usage

---





