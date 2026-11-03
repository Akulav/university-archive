# Cloud Service

A small distributed system made of C# microservices that communicate over TCP and run in Docker containers.

## Services

| Service | Port | Role |
| --- | --- | --- |
| `Gateway` | 130 | Entry point that routes client requests to the other services |
| `LoginService` | 13004 | User authentication |
| `DataService` | 1303 | Stores and serves user data (encrypted) |
| `Cache` | 70 | Caches frequent responses |
| `DB1` | 15002 | Database node |
| `ClientBETA` | – | WinForms desktop client with login and main menu |

## Running

1. Build a Docker image for each service from its folder, tagged to match `docker-compose.yml`:

   ```bash
   docker build -t gateway Gateway/Gateway
   docker build -t login LoginService/LoginService
   docker build -t data DataService/DataService
   docker build -t cache Cache/Cache
   docker build -t db1 DB1/DB1
   ```

2. Start everything:

   ```bash
   docker compose up
   ```

3. Open `ClientBETA/ClientBETA.sln` in Visual Studio and run the client.
