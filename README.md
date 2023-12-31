<h1 align="center">CHATEX - ChatGPT AI App</h1>

# Table of Contents
- Table of Contents
- Demo
- Tech Stack
- Web App Features
- Features and Functionality
- How to get started

# Basic Overview :
* With ChatGPT and other AI apps taking all over the world, this project is an attempt to build a Web App similar to that.
* The queries are answered using OpenAI's famous model **text-davinci 003**.

# :film_projector: Demo :
https://github.com/Aasneh/Chatex/assets/96459729/ed41cccb-7cf1-4c0c-ae26-f656fd5262b0


# :abacus: Tech Stack :
<p>
<img src="https://github.com/get-icon/geticon/raw/master/icons/javascript.svg" alt="JavaScript" width="50px" height="50px">
<img src="https://github.com/get-icon/geticon/raw/master/icons/css-3.svg" alt="CSS3" width="50px" height="50px">
<img src="https://github.com/get-icon/geticon/raw/master/icons/html-5.svg" alt="HTML5" width="50px" height="50px">
<img src="https://github.com/get-icon/geticon/raw/master/icons/nodejs-icon.svg" alt="Node.js" width="50px" height="50px">
<img src="https://github.com/get-icon/geticon/raw/master/icons/express.svg" alt="Express" width="50px" height="50px">
</p>

# Web App Features:
* Classy UI : Designed using **CSS**.
  <br>
 ![imgonline-com-ua-twotoone-zXJHpqrTPdp2LvL6](https://github.com/Aasneh/Chatex/assets/96459729/e9f9d7ab-9a31-4500-a51a-b0560b9d50c1)<br>

* Queries Answered.
 ![Screenshot (91)](https://github.com/Aasneh/Chatex/assets/96459729/25bc11b0-9316-4b2d-9e68-f0f76650bae3)<br>
* Problems Solved
![Screenshot (92)](https://github.com/Aasneh/Chatex/assets/96459729/42751ee0-894d-44e6-93c2-5ae22e6911a1)<br>
![Screenshot (93)](https://github.com/Aasneh/Chatex/assets/96459729/51d6aed0-5b4c-479c-b29f-be56992bde5f)<br>

* Sentiment analysis.

 ![Screenshot (94)](https://github.com/Aasneh/Chatex/assets/96459729/283d9efa-8c95-42a5-92b8-18d4ca429759)<br>


# Features and Functionality:
### FRONTEND:
* Frontend has been designed using **HTML, CSS, JAVASCRIPT**.
* **HTML** has been used to handle the structure of the website, it's contents and it's display.
* **CSS** has been used to create attractive and responsive layout to create an eye-catchy User-Interface.
* **JavaScript** has been used to handle the various events associated with WebApp. <br>
* Implemented Functionality such as:<br>
&ensp; 1) Loading dots while we get the answer to the user's query. <br>
&ensp; 2) Type sequentially each character one by one. <br>
&ensp; 3) Proper icon and background rendered depending on whether the current writer is user or ChatAI. <br>
### BACKEND:
* The server side of the project is handled using **Node.js**.
* **Express.js, dotenv, cors** have been used to create a simple route for requests made by the client(frontend) to reach the server.
* OpenAI's famous model **text-davinci 003** has been used to answer the questions of the client:<br>
&ensp; 1) Temperature set to 0 to ensure no randomness in output. <br>
&ensp; 2) The number of tokens to be displayed in output is set to a maximum of **3000** . <br>
&ensp; 3) Frequency penalty set to 0 to ensure same output for same queries/problems asked by the client. <br>

### How to get started:
* First `git clone` this repository and go to appropriate directory on your local machine.
* Go to directory where this repository is cloned and `cd client` to go to client folder.
* now `npm install` to install all the necessary libraries.
* now `npm run dev` to open the application in local host.
* now go to a new command prompt and `cd server` to go to server folder.
* now `npm install` to install all the necessary libraries.
* now `npm run server` to host the server.
That's It!. Now you are ready to ask your problems and queries to ChatEx!
