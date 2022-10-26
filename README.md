# meetogram

<p align="center"><strong>Communication made easy.</strong></p>

**Meetogram**❤️ offers free, hassle-free communication. Just give the link to a friend, relative or colleague and chat. Nowadays, to communicate you need to register on social networks, Meetogram only needs a name from you to simply show it next to your video.

- Free and opensource. Forever.
- Securely. Service doesn't collect any data about you and your videocall. All code is open source here, in Github.
- Easy to use. You don't have to register, just send invitation link.

# 🐳 Deploy
You can host your meetogram instance on your servers. You just need `docker-compose.yml` to start docker container. That's all.

## Use production env file
Use production `env` file to build a docker-container. To use it simply just write next command in terminal:

```bash
npm run env:prod
```

## Build `docker-compose.yml`

...

# 🧱 Tech stack
Server stack is simple:
- **Firebase** to sync data between users
- **Express** to use it for API
- **Joi** for check POST request fields
- **Jest** for unit-testing
- **Typescript** for type-definitions
- **Redis** (*Optional*) for managing data between calls instead of using Firebase

Client stack is also simple like a piece of cake:
- **Vue** for building UI
- **Typescript** for typing-definition
- **Vite** for fast build

All workspace is bootstraped via [Turbo](https://turbo.build/)🚀

