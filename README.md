# passport-jwt-mysql

Initialisation du projet :

```
git clone https://github.com/qdanneville/passport-jwt-mysql

npm install

npm run start-dev
```

![](./images/arbo)

## Liste des concepts que vous trouverez dans ce projet :

Une authentification user
![](./images/user.controller.authenticate.PNG)
![](./images/user.service.authenticate.PNG)
![](./images/postman.authenticate.response.PNG)
![](./images/postman.authenticate.response.PNG)
![](./images/authenticate.log.server.PNG)

## Un register user

![](./images/user.service.register.PNG)
![](./images/user.controller.register.PNG)
![](./images/postman.register.request.PNG)
![](./images/postman.register.response.PNG)
![](./images/register.log.server.PNG)

## CreateHash lors du register

CompareHash lors de l’authenticate
Création d’un token JWT lors de l’authenticate
Vérification du token avec passport & jwt-passport pour accéder à certaines routes

## Liste des routes disponibles :

<http://localhost:5000/api/users/register>

<http://localhost:5000/api/users/authenticate>

<http://localhost:5000/api/dashboard>
