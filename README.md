### 0. firstly make src dir from current user:
`mkdir -p src`

### 1. then copy laravel via composer:
`docker compose run create-project`

### 2. then mysql db setup and artisan migrate:
`docker compose run db-init`

### 3. finnaly run server:
`docker compose up nginx -d`

## So u can open laravel clear project on:
http://localhost:8000/