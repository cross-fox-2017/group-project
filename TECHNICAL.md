# [App Name] Technical Documentation

> [Short tagline or description.]

--------------------------------------------------------------------------------

## Development

Open `server` and `client` directory separately.

### Server

```sh
npm install
npm run dev
```

### Client

```sh
bower install
live-server
```

--------------------------------------------------------------------------------

## Data Models

### Model A

```js
{
  "name": String
  "point": Number
  "active": Boolean
}
```

### Model B

```js
{
  "name": String
  "point": Number
  "active": Boolean
}
```

--------------------------------------------------------------------------------

## API Endpoints

Root URL: `http://localhost:3000/api`

### Resource A

| Endpoint         | HTTP | Description |
|------------------|------|-------------|
| `api/things`     | GET  | Get all things
| `api/things`     | DEL  | Delete all things
| `api/things`     | POST | Post a new thing
| `api/things/:id` | GET  | Get thing by id
| `api/things/:id` | DEL  | Delete thing by id
| `api/things/:id` | PUT  | Update thing by id

### Resource B

| Endpoint        | HTTP | Description |
|-----------------|------|-------------|
| `auth/signup`   | POST | Sign up for a new user
| `auth/sigin`    | POST | Sign in with existed user
| `api/users`     | GET  | Get all users
| `api/users`     | DEL  | Delete all users
| `api/users/:id` | GET  | Get one user profile by id
| `api/users/:id` | DEL  | Delete one user profile by id
| `api/users/:id` | PUT  | Update one user profile by id

--------------------------------------------------------------------------------

## License

[Selected License]
