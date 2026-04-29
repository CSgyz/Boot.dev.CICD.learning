# learn-cicd-starter (Notely)

This repo contains the starter code for the "Notely" application for the "Learn CICD" course on Boot.dev.

This is CSgyz's version of Boot.dev's Notely app.

## Motivation

I created this project as part of the Boot.dev Learn CICD course to practice building, running, and eventually deploying a simple Go web application.

The goal of this repo is to provide a small and easy-to-understand starter application that can be used to learn CI/CD concepts step by step, including local development, automated testing, building, and deployment workflows.

At the current stage, the application runs in non-database mode and serves a simple webpage locally.

## Quick Start

Make sure you're using Go version 1.22+.

Clone the repo:

```bash
git clone https://github.com/<your-username>/learn-cicd-starter.git
cd learn-cicd-starter

Create a .env file in the root of the project:

PORT="8080"

Build and run the server:

go build -o notely && ./notely

Then open:

http://localhost:8080
Usage

This application currently runs as a simple local Go web server.

By default, it starts in non-database mode. You do not need to set up a database or add webpage interactivity yet. Those features will be introduced later in the course.

Useful local development commands:

go build -o notely
./notely

Or run both together:

go build -o notely && ./notely
Contributing

Contributions are welcome, especially improvements related to learning, documentation, local development, and CI/CD practice.

Clone the repo
git clone https://github.com/<your-username>/learn-cicd-starter.git
cd learn-cicd-starter
Create a new branch

Create a branch for your changes:

git checkout -b your-feature-name

Example:

git checkout -b improve-readme
Set up the local environment

Make sure you're using Go version 1.22+.

Create a .env file in the root of the project:

PORT="8080"
Build and run the app
go build -o notely && ./notely

Visit the app locally at:

http://localhost:8080
Make your changes

You can contribute by improving areas such as:

README documentation
Local development instructions
Go code structure
CI/CD workflow configuration
Tests and build scripts
Check your changes

Before opening a pull request, make sure the project still builds successfully:

go build -o notely
Commit your changes
git add .
git commit -m "Improve README documentation"
Push your branch
git push origin your-feature-name
Open a pull request

Open a pull request from your branch into the main branch of this repository.

Please include a short description of:

What you changed
Why you changed it
How you tested it locally
