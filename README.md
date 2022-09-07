# Server Chatroom

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
