Monitoring your nestjs application metrics and analyze it with grafana and prometheus. I explained how to implement these. You can check out my medium post : [Nestjs Monitoring With Prometheus and Grafana](https://medium.com/@kaant43/monitoring-nestjs-application-with-grafana-prometheus-d8fbb629547f)
#### Techs I use
 - NestJS
 - Docker
 - Grafana
 - Prometheus

#### Installation 
```bash
$ npm install
```
### Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

```
#### Dockerize your application
```bash
$ docker build -t image_name . 
```
#### Run Docker compose 
```bash
$ docker-compose up 
```


### License

Nest is [MIT licensed](LICENSE).
