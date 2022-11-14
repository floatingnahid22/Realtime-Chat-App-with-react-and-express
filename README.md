# Realtime-Chat-App-with-react-and-express

## Installation and How to run:

Create an empty folder, with any name. Inside that folder create two more folders for backend and frontend, separately.

<h4>Server Side:</h4>

```js
    cd backend
```

```js
    npm init -y
```

```js
    npm install bcrypt cors crypto dotenv express getstream nodemon stream-chat twilio
```

```js
    npm run dev
```

For process.env's file you have to create stream and twilio account and from there you have to put <b> accountSid, authToken, messagingServiceSid, api_key, api_secret, app_id and apiKey </b> value inside your application.

<h4>Client Side:</h4>

```js
    cd frontend
```

```js
    npx create-react-app ./
```

```js
    npm install axios stream-chat universal-cookie stream-chat-react@9.5.2
```

```js
    npm start
```

## Description of this application:

<p>Here, I have built a realtime chat application using react, express, stream-chat and twilio sms service. In this application user can do sign up/sign in and they can comunicate with each other. They can create channels for group chat or for direct message. They can send emojis, files, gif or any other attachments. They can reply or react each others messages etc. </p>

<p>I am attaching some pictures below for ease of understanding</p>

<p>Sign Up:</p>

![Capture7.png](https://i.postimg.cc/NjPJZsmP/Capture7.png)

<p>Sign In:</p>

![Capture8.png](https://i.postimg.cc/VkNZ7rrC/Capture8.png)

<p>Backend-team channel and here is one user named nahidhossain:</p>

![Capture1.png](https://i.postimg.cc/QCkYzcJp/Capture1.png)

<p>Frontend-team channel and here is two users named nahidhossain and amir:</p>

![Capture2.png](https://i.postimg.cc/XNwPX06p/Capture2.png)

<p>Direct messaging between two users:</p>

![Capture3.png](https://i.postimg.cc/C5V6Jckh/Capture3.png)

<p>React and Reply on each others messages: </p>

![Capture2.png](https://i.postimg.cc/XNwPX06p/Capture2.png)

<p>Emoji sent:</p>

![Capture5.png](https://i.postimg.cc/4NsS9FXw/Capture5.png)

<p>File or attachment sent:</p>

![Capture6.png](https://i.postimg.cc/wT2bccvz/Capture6.png)

Description Link: https://github.com/floatingnahid22/Realtime-Chat-App-with-react-and-express#realtime-chat-app-with-react-and-express
