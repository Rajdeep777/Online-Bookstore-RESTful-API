# Node.js Express & MongoDB: CRUD Rest APIs
First, we start with an Express web server. Next, we add configuration for MongoDB database, create Tutorial model with Mongoose, write the controller. Then we define routes for handling all CRUD operations (including custom finder).

## Project setup
```
npm install
```

### Run
```
node server.js
```
## Endpoints:
### Users

```sh
GET    /api/users
GET    /api/users:id
POST   /api/users/:id
PUT    /api/users/:id
DELETE /api/users/:id
```

### Authors

```sh
GET    /api/authors
GET    /api/authors:id
POST   /api/authors/:id
PUT    /api/authors/:id
DELETE /api/authors/:id
```
### Books

```sh
GET    /api/books
GET    /api/books:id
POST   /api/books/:id
PUT    /api/books/:id
DELETE /api/books/:id
```