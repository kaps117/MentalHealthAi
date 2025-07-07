# MindMate  
## Elevating Mental Health with AI

---

## Introducing MindMate

**MindMate** is an AI-powered mental health chat assistant designed to guide, support, and empower users on their journey to better mental well-being. With a user-friendly interface, MindMate offers personalized guidance, insightful analysis, and curated resources—all in one secure, accessible platform.

---

## Why Choose MindMate?

- **AI-Powered Chat Assistant:** Get immediate, empathetic support for your mental health questions.
- **Longitudinal Mental Health Analysis:** Track your well-being over time with detailed reporting.
- **Graphical Insights:** Visualize your mental health status and progress.
- **Curated Articles:** Access editor-compiled resources to learn about mental health topics.
- **Personalized Email Suggestions:** Receive regular, actionable tips to improve your mental health.

---

## Recognition

**🏆 Recognized at H2AI Georgetown University Hackathon**

---

## Experience MindMate

- **Live Deployment:** [https://mind-mate-wellness.vercel.app](https://mind-mate-wellness.vercel.app)
- **Watch the Demo:** [YouTube Explanation](https://www.youtube.com/watch?v=fUD5HcZhtQI)

---

## Technology

### System Architecture

MindMate leverages a robust, multi-server architecture for performance, scalability, and security:

- **Frontend Server**
- **Backend Server**
- **WebSocket Server**
- **Email Server**
![des](https://github.com/algovengers/MindMate/assets/126336384/bc6c71c9-017f-49c9-9770-ee10164fe88b)


---

### Tech Stack

| Component      | Technologies & Tools                |
|----------------|-------------------------------------|
| **Frontend**   | React JS, Tailwind CSS              |
| **Backend**    | Node.js, Express.js, Gemini (Gen AI), WebSockets, NodeMailer |
| **Tools**      | Vercel, Render, MongoDB Atlas, Firebase |

---

## Local Setup Guide

### 1. Firebase Configuration

1. **Create a new Firebase project.**
2. **Add a Web App.**
3. **Enable Authentication:**  
   - Email/Password  
   - Google (Gmail)
4. **Retrieve `firebaseConfig`:**  
   - Go to Project Settings > Web App.
5. **Set up `.env` in Frontend:**  
   - Copy `firebaseConfig` as per `.env.sample`.
6. **Generate a Private Key:**  
   - In Service Accounts, generate a new private key (JSON).
7. **Set up `.env` in Backend:**  
   - Add the private key as per `.env.sample`.
8. **Complete remaining `.env` variables.**

---

### 2. Gemini API Key

- **Obtain your Gemini API key** from [ai.google.dev](https://ai.google.dev).
- **Add to Backend `.env`** as per `.env.sample`.

---

### 3. MongoDB Atlas

- **Create a MongoDB Atlas account.**
- **Get your connection URI.**
- **Add to Backend `.env`** as per `.env.sample`.

---

### 4. Server Connections

- **WebSocket Server URL:** Add to Backend `.env` (e.g., `WEBSOCKET_SERVER=ws://localhost:8802`).
- **Backend & WebSocket URLs:** Add to Frontend `.env` (e.g., `REACT_APP_API_LINK=http://localhost:8800`, `REACT_APP_WS_LINK=ws://localhost:8802`).

---

### 5. Installation & Launch

1. **Ensure Node.js is installed.**
2. **Run `npm install` in each folder:**  
   - Backend  
   - Frontend  
   - WebSocket Server
3. **Launch Servers:**  
   - Backend: `npm run dev` or `npm start`
   - Frontend: `npm start`
   - WebSocket Server: `node index.js`

---

## Website Preview

#### HomePage 
![83dae728-5f7f-48c7-b2f4-0dccaacfec55](https://github.com/algovengers/MindMate/assets/126336384/c7810ff6-73e2-4b17-bbd3-1f5c3761febf)
#### Login
![5e8cb463-c116-4eff-bc96-7a52eb0a1a72](https://github.com/algovengers/MindMate/assets/126336384/e3413eee-e202-4462-b0e1-2b9243924944)
#### Analysis
![a6145724-1519-4073-9b43-17f308494b68](https://github.com/algovengers/MindMate/assets/126336384/c92c881f-7c9d-453b-8121-706f6c926ec4)
![cbdb3501-5a2c-4c2e-ae05-bf25973aa334](https://github.com/algovengers/MindMate/assets/126336384/92cd5ece-79e3-4245-b91e-4d87defaa397)
#### AI Chat
![1538b7b1-41b3-4734-b74b-0092750f47df](https://github.com/algovengers/MindMate/assets/126336384/a2653f47-045b-41ce-951e-da36286240fc)


---

## Ready to Make a Difference

**MindMate** stands out for its seamless integration of AI, user-centric design, and comprehensive mental health support. Whether you’re a user seeking guidance or a developer looking to contribute, MindMate offers a powerful, accessible solution for mental well-being.

> *All setup steps and tech stack details are presented for clarity and ease of use, with security and best practices in mind.*
  
    



