# dock_wp

WordPress setup with Docker

## Usage

- `cp .env.example .env`
- Change values in `.env` as required
- `docker compose up -d`. `-d` flag is for running in detached mode(background). Optionally, you can add `-p <project-name>` to specify a project name.
- `docker compose down`. If you started with `-p <project-name>`, you will also need to specify the flag while closing.
