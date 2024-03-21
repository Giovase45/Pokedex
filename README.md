<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Execute in DEV

1. Clone repository
2. Execute
```
npm install
```
3. Install Nest CLI
```
npm i -g @nestjs/cli
```

4. Up Database
```
docker-compose up -d
```

5. Clone the file __.env.template__ and rename copy to __.env__ - Add not existent values.

6. Start Application
```
npm run start:dev
```

7. Rebuild data with Seed
```
http://localhost:3000/api/v2/seed
```

#Stack Used
* MongoDB 5
* Nest
