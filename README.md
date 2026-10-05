# 🐰 Bunny's Pocket of Wishes

A cozy, storybook-style single-page website where a tiny bunny gives you a new wish.

## 📁 Project Structure

```text
.
├── Dockerfile
├── index.html
└── README.md
```

## 🚀 Build and Run

Build the Docker image:

```bash
docker build -t bunny-wishes:v1 .
```

Run the container:

```bash
docker run -d --name bunny-wishes -p 8080:80 bunny-wishes:v1
```

Open in your browser:

```text
http://localhost:8080
```
