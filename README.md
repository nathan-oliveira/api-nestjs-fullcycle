

### Comandos utilizado na criação do projeto
npm i --save @nestjs/typeorm typeorm mysql
npm i --save @nestjs/config

npm run typeorm migration:create -- --name CreateUserTable
npm run typeorm migration:run
npm run typeorm migration:revert

npm run typeorm entity:create -- --name=User

nest generate controller user

npm i --save @nestjs/swagger swagger-ui-express

npm i --save class-validator class-transformer

---

https://www.youtube.com/watch?v=BT7novtdAgI
02:01:23

