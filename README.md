# Installation#

### For Microservices
```
npm i --save @nestjs/microservices
```

### RabbitMQ
```
npm i --save amqplib amqp-connection-manager
```

---
_Hot Reload için uygulamayı bu şekilde başlatabilirsin_

```
npm run start:dev
```
---


### MongoDB
```
npm install --save mongoose
```

* tsconfig.json dosyasında aşağıdaki komut yoksa ekliyoruz
```
"extends": "@ljharb/tsconfig",
```