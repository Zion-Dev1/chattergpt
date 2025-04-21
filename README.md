## ✨ ChatterGPT ✨
This is a full-stack application which is essentially a clone of ChatGPT. I wanted to gain some experience using the OpenAI API and thought this was a good project to do so.

![image](https://github.com/user-attachments/assets/5c14f548-4b66-464f-a4b5-8fb93671d7bd)

## Table of Contents

- [Tech Stack](#tech-stack)
- [Setup](#setup)
- [Running the project](#running-the-project)

<br>

## Tech Stack 💻

- **Frontend:** 
  - React with Typescript
  - ChakraUI for CSS and styling
  - Zustand for state management

- **Backend:** 
  - Node.js with Express (TypeScript)
  - Mongoose for accessing the data
  - OpenAI API to answer the user's queries

- **Database:** MongoDB

<br>

## Setup ⚙️

If you wish to try out my project for yourself, follow these steps.

1. Clone the repository:

   ```bash
   git clone https://github.com/Zion-Dev1/chattergpt.git
   cd chattergpt
   ```

2. Setup the client folder.

   ```bash
   cd client
   npm install
   ```

3. Setup the server folder
   ```bash
   cd ../server
   npm install
   ```
   Then create a `.env` file in this folder and paste this:

   ```bash
   PORT=3000
   ```

   You will have to create your own MongoDB database and OpenAI API key as I cannot share mine. Once you have done that, paste them in the `.env` like so:

   ```bash
   DB_CONNECT=[your mongodb connection url]
   OPENAI_API_KEY=[your api key]
   ```

<br>

## Running the project 👟

Create 2 new command terminals, and make sure they are in the root directory (chattergpt). Then run `npm run client` and `npm run server` in a terminal respectively.

Then, navigate to http://localhost:5173 to view the website.

Type in a query, hit ENTER and watch the OpenAI model answer your question 🤖
