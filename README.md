# First Microtask
## It is a microservice to handle error




## API Reference

#### Get error message

http
  GET https://xndzc3.deta.dev/api/error-endpoint



## Installation

bash
    git clone https://github.com/JUTEWFA/microtask1.git


### `Navigation`
bash
    cd microtask1

### `Installation`



bash
  npm i




### `Runserver`

bash
  npm start







# Second Microtask
## It is a microservice which accumulates three different microservice APIs : ErrorHandler,Authentication and Visitor counter


## Installation

bash
    git clone https://github.com/JUTEWFA/microtask2.git


### `Navigation`
bash
    cd microtask2

bash
    cd AuthAPI or cd ErrorHandler or cd ViewCounter

### `Installation`



bash
  npm i




### `Runserver`

bash
  npm start



## API Reference

### Authentication

#### Sign-up(Returns token )

http
  POST http://localhost:3000/api/sign-up


| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `body` | `email` | *Required*|
| `body` | `password` | *Required*|


#### Log In(Returns token)

http
  GET http://localhost:3000/api/sign-in


| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `body` | `email` | *Required*|
| `body` | `password` | *Required*|

|



### Visitor counter


http
  POST http://localhost:3000/api/get-views








### ErrorHandler

#### Get a random error message which is handled by a dummy ErrorHandler middleware

http
  GET http://localhost:3000/api/error







# Third Microtask
## It is a microservice that takes the user's Latitude and Longitude as input and returns their  current address. It can also be used to get the Latitude and Longitude of a location by filling out the address.


## Installation

bash
    git clone https://github.com/JUTEWFA/microtask3.git


### `Navigation`
bash
    cd microtask3


### `Installation`



bash
  npm i




### `Runserver`

bash
  npm start



## API Reference


#### Takes the user's location and returns their address

http
  GET https://06o7k9.deta.dev









## Author

- [@JUTEWFA](https://github.com/JUTEWFA)
