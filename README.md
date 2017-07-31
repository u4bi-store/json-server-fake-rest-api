#### 프로토타입화를 위한 REST API (json-server)

##### install
```
npm install
```

##### run
```
npm run watch db.json
```

##### routes
```

GET http://localhost:3000/weapons
GET http://localhost:3000/vehicles
GET http://localhost:3000/setup

GET http://localhost:3000/weapons/1
GET http://localhost:3000/vehicles/1

DELETE http://localhost:3000/weapons/1
DELETE http://localhost:3000/vehicles/1


PUT http://localhost:3000/setup
open - false


POST http://localhost:3000/weapons
name  - M4
price - 15000

PUT http://localhost:3000/weapons/4
name  - M4A1
price - 16000

```


- **json-server** : full fake REST API with zero coding in less than 30 seconds [https://github.com/typicode/json-server](https://github.com/typicode/json-server)
