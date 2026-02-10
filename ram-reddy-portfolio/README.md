# Ram Reddy Portfolio - AI & Gen AI Expert

This is a modern, responsive portfolio website built with HTML5, CSS3, and Vanilla JavaScript, designed to showcase expertise in Artificial Intelligence and Generative AI.

## Features
- **Neural Network Background**: Interactive canvas animation simulating neural connections.
- **Custom Cursor**: sleek, futuristic cursor with trailing effect.
- **Glassmorphism UI**: Modern frosted glass effect for cards and navigation.
- **Responsive Design**: Fully optimized for desktop, tablet, and mobile.
- **Dockerized**: Easy deployment with Docker.

## How to Run

### Prerequisite
Ensure Docker Desktop is installed and running.

### 1. Build the Image
```bash
docker build -t ram-reddy-portfolio .
```

### 2. Run the Container
```bash
docker run -d -p 80:80 --name ram-portfolio ram-reddy-portfolio
```

Now open your browser and go to `http://localhost`.

## Using a Custom Domain (Localhost)
If you want to access the site via a custom domain like `ramreddy.ai` locally:

1. Open Notepad as Administrator.
2. Open the file `C:\Windows\System32\drivers\etc\hosts`.
3. Add the following line at the bottom:
   ```
   127.0.0.1 ramreddy.ai
   ```
4. Save the file.
5. Access the site at `http://ramreddy.ai`.
