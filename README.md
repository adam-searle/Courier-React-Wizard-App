# Courier-React-Wizard-App - Magic Transactional Emails with Courier

Welcome to the Magic Transaction Emails app! This project allows users to send magical, transactional emails using [Courier](https://www.courier.com/), a powerful platform for building and sending notifications.

This app presents a spellbook interface where each spell corresponds to a different type of transactional email that can be sent.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Before you begin, you will need to have the following installed:

- [Node.js](https://nodejs.org/en/download/)
- [npm](https://www.npmjs.com/get-npm)
- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

### Installation

1. Clone the repo: git clone [https://github.com/username/repo-name.git](https://github.com/adam-searle/Courier-React-Wizard-App.git)

2. Install NPM packages in both the `courier-email-client` and `courier-email-server` directories. In your terminal, navigate to each directory and run: npm install


### Configuration

After installing the project, you need to provide your Courier Auth Token, your email, and your email templates.

#### Setting up Courier

In `courier-email-server`, open `server.js` and replace `YOUR_AUTH_TOKEN` with your Courier Auth Token. 

#### Configuring the Spellbook

In `courier-email-client`, go to `Spellbook.js` and replace all instances of `YOUR_EMAIL` and `YOUR_TEMPLATE_ID` with the email you want to send to and the email templates you want to use.

### Running the Application

After completing the setup, you can run both parts of the app:

- In the `courier-email-server` directory, start the server: `node server.js`

- In the `courier-email-client` directory, start the client: `npm start`

Open [http://localhost:3000](http://localhost:3000) to view the client in the browser if it doesn't open automatically

---


