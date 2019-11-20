# mapathon-backend
REST API for the Mapathon Project (645-1)

The server was written as a Node.js app using the following main libraries and technologies:

Express.js for defining the routes (GET/POST/PATCH...)

Express-JWT and jwks-rsa for validating JWT access tokens sent by your apps

Sequelize as an Object-Relational Mapper (ORM)

MariaDB as a database (in production, SQLite for development)

Swagger for documenting the API (YAML file format)

SwaggerUI-Express for automatically generating the documentation webpage

All the authentication was done using Auth0, there is a free plan which already allows many features.
