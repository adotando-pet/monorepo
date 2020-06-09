# This Repository is for start api and frontend 

```
git clone https://github.com/adotando-pet/monorepo
cd monorepo

git clone --recursive https://github.com/adotando-pet/frontend.git
git clone --recursive https://github.com/adotando-pet/backend.git

cd backend
git checkout dev

cd ../frontend
git checkout dev

cd ..

```

### Create database 
- Access `localhost:5050`
user: `admin@admin.com`
password: `admin`

- Create a server
name: `pet`
host: `postgres`
user: `postgres`
password: `postgres`
port: `5432`

- Create databse `pet-db`

### Run containsers with docker-compose

```
docker-compose up
```
