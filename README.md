# Yarrow-Mullein Bank — Module 5 Part 3

Name: Harshdeep Singh
Course: COMP-4001

This project contains:

- A static student portfolio
- A Python/Flask banking backend
- MongoDB for users and balances
- A JavaScript transactions service
- An NGINX gateway

Only NGINX publishes a host port.

Routes:

- / goes to the portfolio.
- /api/ goes to the banking backend.
- /api/transactions/USER_ID goes to the JavaScript report service.

Start:

docker compose up --build -d

Open:

http://localhost/

Stop:

docker compose down

MongoDB uses a named volume to preserve data.

GitHub Actions runs the backend tests and builds the application images.
The workflow does not automatically deploy the project.