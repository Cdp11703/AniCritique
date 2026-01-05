# AniCritique

**AniCritique** is a full-stack anime review web application originally developed and co-built in 2023. The project allows users to explore, review, and critique anime titles through a dynamic and interactive interface. It is built using **HTML / Handlebars (HBS)**, **CSS**, **JavaScript**, **Node.js**, **Express.js**, and **MongoDB**.
This repository contains the imported and organized source code, which was not originally hosted on GitHub.

---

## Installation & Setup

### Prerequisites

Make sure the following are installed on your system:

* **Node.js**
* **npm (Node Package Manager)**

You can download them from the official Node.js website.

---

### Project Setup

1. Clone the repository and navigate to the project directory:

```bash
cd anicritique
```

2. Install the required dependencies:

```bash
npm install
```

> ⚠️ **Note:** Running `npm init` is not required for setup, as the project already includes a `package.json` file.

---

### Running the Application

Start the server using:

```bash
node app.js
```

Once running, open your browser and navigate to:

```
http://localhost:3000
```

*(or the port specified in your `.env` file)*

---

## Environment Variables

Create a `.env` file in the root directory and configure the following variables:

```env
SERVER_PORT=3000
MONGODB_URI=your_mongodb_connection_string
```

A sample configuration is provided in `.env.example`.

---

## Technologies Used

* HTML / Handlebars (HBS)
* CSS
* JavaScript
* Node.js
* Express.js
* MongoDB

---
