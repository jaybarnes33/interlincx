# Example Server

This is an example of a basic HTTP API server.

Includes:

- [x] `standard` for code style
- [x] `productionize` for log formatting
- [x] `healthpoint` for health checks
- [x] `tape` for testing
- [x] `servertest` for endpoint testing
- [x] `nodemon` for auto-restart in development
- [x] `nyc` for code coverage
- [x] `dependency-check` to ensure no missing or extra dependencies
- [x] `http-hash-router` for routing
- [x] `send-data` for JSON response
- [x] `req-logger` for request logging
- [x] `dotenv`, `.env.example`, and `config.js` for env vars
- [x] example `db.js` and `model.js`
- [x] `body` for JSON POST body parsing
- [x] `pump` for stream piping
- [x] endpoint/route callback argument for error handling (with request id)
- [x] `corsify` for CORS
- [x] `authentic-service` and `authify.js` for authentication

# Git Challenge

There are two branches, `add-echo` and `add-reverse`. The goal of this challenge is to use `git rebase` to bring both commits onto master. When finished there should be no merge commits or branching. For example, `git log` on the `master` branch should look similar to this:

```
/challenge-git master
⚡ git log
61a2c67 feat: add reverse route (David Guttman, 7 minutes ago)
2c2c5d6 feat: add echo route (David Guttman, 10 minutes ago)
dcc4c0b docs: add more instructions (David Guttman, 11 minutes ago)
...
```

## Instructions

How to attempt this challenge:

1. Create a new repo in your account and note the git url
2. Clone this repo
3. Solve the challenge
4. Set your new repo as the origin: `git remote set-url origin ${your repo url}`
5. Push your solution to your repo
   You must follow these steps for your solution to be accepted -- forks or other methods will not be considered.
