This is BE template project with Golang 

- Run the server: `air`
- DB migrate (PostgreSQL): `migrate -database 'postgres://postgres:password_here@localhost:5432/db_name_here?sslmode=disable' -path internal/db/migrations down` or `up` (`https://github.com/golang-migrate/migrate` required)
- Swagger included.
