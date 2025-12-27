# Deprecated!
Use https://github.com/jonaaix/mattermost-docker-arm instead. If you don't use ARM, you can just switch the binary download URL to AMD64.

# Mattermost Docker

A minimal Docker Compose setup to run [Mattermost](https://mattermost.com/).

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/your-org/mattermost-docker.git
   cd mattermost-docker
   ```

2. Copy the example files:
   ```bash
   cp .env.example .env
   cp docker-compose.example.yml docker-compose.yml
   ```

3. Configure your environment:
   Edit the `.env` file to set values such as the database password and site URL.

4. Start the services:
   ```bash
   docker compose up -d
   ```

5. Open Mattermost in your browser:
   [http://localhost:8065](http://localhost:8065)

---

For advanced configurations or production setup, refer to the [official Mattermost documentation](https://docs.mattermost.com/).
