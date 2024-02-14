# Docker installation
- Pull this repo
```shell
git clone https://github.com/KimmyXYC/quotly.git
```

- Copy `.env` file
```shell
cp .env.example .env
```

- Edit `.env` file

- Place the font files in the `assets/fonts` folder

- Creat network
```shell
docker network create quotly
```

- Starting with Docker Compose
```shell
docker compose up -d
```
