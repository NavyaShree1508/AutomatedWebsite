Automated Website

A simple website built using HTML and Docker.

Project Files

- "index.html" — Website page
- "Dockerfile" — Docker configuration

Build

Build the Docker image using:

docker build -t automated-website .

Run

Start the website container using:

docker run -p 8080:80 automated-website

Open "http://localhost:8080" in your browser.
