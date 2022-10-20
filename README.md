## nodejs, express, typescript

yarn install
yarn start

## Examples of requests

### add-todo

POST http://localhost:3000/todos/

Content-Type application/json

Body

{
    "text": "new todo"
}

### get-todos

GET http://localhost:3000/todos/

### update-todo

PATCH http://localhost:3000/todos/{id}

Content-Type application/json

Body

{
    "text": "updated todo"
}

### delete-todo

DELETE http://localhost:3000/todos/{id}
