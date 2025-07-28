<h1 align="center">✈️ AirplaneTicketSeller</h1>

<p align="center"><i>
A final project for Introduction to Software Engineering - HCMUS 2025.  
This web application allows users to search and book airplane tickets through a simple and responsive interface.
</i></p>

<p align="center">
  <img src="image.png" alt="App Screenshot" width="600"/>
</p>

---

<h3>⚙️ Tech Stack</h3>

<p>
  <img src="https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=white&style=flat"/>
  <img src="https://img.shields.io/badge/-Vite-646CFF?logo=vite&logoColor=white&style=flat"/>
  <img src="https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black&style=flat"/>
  <img src="https://img.shields.io/badge/-Node.js-339933?logo=nodedotjs&logoColor=white&style=flat"/>
</p>
<p>
  <img src="https://img.shields.io/badge/-Express-000000?logo=express&logoColor=white&style=flat"/>
  <img src="https://img.shields.io/badge/-MongoDB-47A248?logo=mongodb&logoColor=white&style=flat"/>
  <img src="https://img.shields.io/badge/-JWT-black?logo=jsonwebtokens&logoColor=white&style=flat"/>
</p>

---

<h3>Project Structure</h3>

/frontend --> React + Vite app
/backend --> Node.js server, API logic, MongoDB connection

---
<h3>How to Build</h3>

To build this website, go to <b>Command Prompt</b> or <b>Powershell</b> and run:

```bash
echo Build the website UI
cd frontend
npm init -y
npm install
npm run build

echo Move the built website to backend folder
move dist ../backend
cd ../backend
ren dist client

echo Launch the server
npm install
node ./src/server.js 
