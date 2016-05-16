# node-micro-service-front

> ⚠️ This project is a support for the blogpost [Docker — How to simply manage your microservices app with NodeJs](https://medium.com/p/489b8825053)

The purpose is to manage your Docker's microservice  container with NodeJs : 
- Micro service 1 : API provider
- Micro service 2 : Render app view (this repo)

More detail on the blog post :  https://medium.com/p/489b8825053

Releated : The Micro service gateway : https://github.com/olivierodo/node-micro-service-gateway

### Docker

https://hub.docker.com/r/olivierodo/node-micro-service-front/

Run the container :

```
docker run --name micro-service-front -p 8080:8080 -d olivierodo/node-micro-service-front
```

> ⚠️ This project only works if you can provide an api (/api/users or /api/users/{id})
