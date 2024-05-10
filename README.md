# GRAMPI 2.0

- If you don't have Ollama yet, use Docker Compose for easy installation. Run this command:

```bash
docker compose up -d --build
```

- **For Nvidia GPU Support:** Use an additional Docker Compose file:

```bash
docker compose -f docker-compose.yaml -f docker-compose.gpu.yaml up -d --build
```
