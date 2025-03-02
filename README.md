# Let's Try Foods Chatbot

This project is a full-stack application created to showcase my skills in building and deploying a chatbot using Node.js, Express, and EJS, integrated with Google Generative AI. The chatbot is designed to provide information about Let's Try Foods, their products, mission, and other relevant details.

## Project Overview

### Features
- **Chatbot Integration**: Utilizes Google Generative AI to power the chatbot, providing detailed and accurate responses related to Let's Try Foods.
- **User Interaction**: The chatbot engages users by answering queries about the company's offerings, mission, and website.
- **EJS Templating**: The frontend is rendered using EJS, allowing for dynamic content based on user interactions.
- **Express Server**: The backend is built with Express, handling routing, API requests, and serving static files.
- **Website URL Handling**: The chatbot correctly responds with the official website URL when asked.

### Technologies Used
- **Node.js**: Backend runtime environment.
- **Express**: Web framework for Node.js.
- **EJS**: Embedded JavaScript templating.
- **Google Generative AI**: Provides the intelligence behind the chatbot.
- **Render**: Hosting platform for the deployed application.

## Project Structure
```
.
├── public
│   ├── assets
│   │   ├── behavior.js
│   │   ├── style.css
│   │   └── webpageStyle.css
│   └── views
│       ├── index.ejs
│       └── webpage.ejs
├── .env
├── .gitignore
├── imports-and-load-chatbot-model.js
├── index.js
├── package.json
├── post-request-for-chat-bot.js
└── README.md
```

## Installation and Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/lets-try-chatbot.git
   ```

2. **Install dependencies**:
   ```bash
   cd lets-try-chatbot
   npm install
   ```

3. **Set up environment variables**:
   - Create a `.env` file in the root directory.
   - Add your Google Generative AI API key:
     ```
     GEMINI_API_KEY=your_google_api_key_here
     ```

4. **Run the application**:
   ```bash
   npm start
   ```
   The application will run on `http://localhost:3000`.

5. **Access the chatbot**:
   - Visit `http://localhost:3000` to interact with the chatbot.

## Deployment

This project is deployed on Render and can be accessed at the following link:

[https://letstry.up.railway.app](https://letstry.up.railway.app)

## Purpose

This project was created to showcase my full-stack development skills and ability to integrate AI services into a dynamic web application. The chatbot effectively assists users in learning about Let's Try Foods and its range of products.
