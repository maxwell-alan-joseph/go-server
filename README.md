# Go Server

A simple HTTP server written in Go, capable of handling different routes and serving static files. This project demonstrates basic Go web development concepts.

## Features

- Serves static HTML files.
- Handles dynamic POST requests with form data.
- Includes endpoints for:
  - `/`: Serves static files from the `static` directory.
  - `/hello`: Returns a simple "Hello!" response.
  - `/form`: Processes form submissions.

## Prerequisites

- [Go](https://golang.org/dl/) (version 1.19 or higher)
- Git installed on your system.

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/go-server.git
   cd go-server
2. Initialize Go Modules (if not already intialized):
   ```bash
   go mod init go-server
   go mod tidy
3. Start the server:
   ```bash
   go run main.go
4. Open your browser and visit:
   
    http://localhost:8080 to view the static files.
  
    http://localhost:8080/hello for the /hello endpoint.
  
    http://localhost:8080/form for the form submission.




