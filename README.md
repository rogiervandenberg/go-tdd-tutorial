# go-tdd-tutorial

Followed from: <https://itnext.io/go-tutorial-tdd-with-go-and-postgresql-part-ii-489c929f02c9>

## How to run:


### Run Postgres

```shell
docker run -d -p 5432:5432 --name my-postgres -e POSTGRES_PASSWORD=12345 postgres

docker exec -it my-postgres bash
psql -U postgres
```

### Set env vars

`. ./setenv.sh`

