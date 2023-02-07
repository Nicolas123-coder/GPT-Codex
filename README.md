# GPT-Codex

![status](https://img.shields.io/website?up_message=up%20%F0%9F%9A%80&url=https%3A%2F%2Fgpt-codex-six.vercel.app%2F)

> Project Link : https://gpt-codex-six.vercel.app/

## A Brief Explanation

Codex GPT is a simple project built for me to learn about the OpenAi API and how to use it inside of real applications.

- The project uses : 

![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

- Client Folder 📂 :
Client folder is where my Fornt end lives, I created somes components that handles the state of the application using the HTML function *query selector*, and also 
this script.js file send POST requests to the back-end, that handles the OpenAI API. 

- Server Folder 📂 : 
In the server folder, I created 2 routes, the GET route for the health info of the application, and the POST route to receive data from the front end, send to the
OpenAI API and give the response data.

## How to run (Client 💻)
```cd client```
```npm i```
```npm run dev```

## How to run (Server ⚙️)
```cd server```
```npm i```
```npm run server```

> more scripts in the package.json file

## Deploy Info 🚀
About the deploy, I use Render to the back-end and Vercel to the front-end.
