# Server Chatroom

This project is a chat app using **NodeJS/Express** and **[Socket.io](https://socket.io/fr/)** as websocket.  
This repo is the back side, the front side is **[HERE](https://github.com/AgathePons/react_09_chat-app_FRONT_socketio)**.

- install `yarn`
- start `yarn start` : http://localhost:3001

## Routes :

- **`POST http://localhost:3001/login`**

Provide an object with email and password:

```js
{
    email: 'bouclierman@herocorp.io',
    password: 'jennifer'
}
```

Logins/passwords:

> bouclierman@herocorp.io/jennifer  
> acidman@herocorp.io/fructis  
> captain.sportsextremes@herocorp.io/pingpong

- **`POST http://localhost:3001/forgot`**
- **`GET http://localhost:3001/theme/{email}`**
