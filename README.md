# Assignment: Flask Application for CRUD operations on MongoDB
A Flask user resource API.
## Setting up the API:

### Without docker:
- Create a virtual environment in the project directory and activate it.
```py
> py -m venv venv
> ./venv/Scripts/activate
```

- Install dependencies.
```py
> pip install requirements.txt
```
- Run the application.
```py
flask run
```

### With docker:
- Run the following commands in your project directory.
```py
> docker build -t corider-api .
```
```
> docker run -d -p 5000:5000 corider-api corider-api
```

- Now the application will start running on `localhost:5000`

### API testing
- Use Postman to test the API
- Following endpoints can be called
```
GET localhost:5000/users
GET localhost:5000/users/<user_id>
POST localhost:5000/users
PUT localhost:5000/users/<user_id>
DELETE localhost:5000/users/<user_id>
```

## Postman Preview:

### GET
![image](https://github.com/saarimshaikh/coRider_assignment/assets/65160026/ac95a5a6-73aa-4152-9b31-3a46a8600e24)

### GET by user id
![image-1](https://github.com/saarimshaikh/coRider_assignment/assets/65160026/c455e7b4-f483-4f17-8d85-504727c9fa02)
### POST
![image-2](https://github.com/saarimshaikh/coRider_assignment/assets/65160026/bd81b474-6ea8-4ea2-8ddf-07e005b0ceed)

### PUT
![image-3](https://github.com/saarimshaikh/coRider_assignment/assets/65160026/90b7a99c-b2af-47d9-bf67-1d6dde7923d0)

### DELETE
![image-4](https://github.com/saarimshaikh/coRider_assignment/assets/65160026/3f81323d-3631-4e45-8f93-f3d3d4802f91)
