docker run -d -p 5432:5432 -e POSTGRES_PASSWORD=1234 postgres

## URL
jdbc:postgresql://localhost:5432/postgres

## Listado
HOST=localhost
PORT=5432
USER=postgres
PASSWORD=1234

## Persistir Dados
docker run -p 5432:5432 -v /tmp/database:/var/lib/postgresql/data -e POSTGRES_PASSWORD=1234 -d postgres