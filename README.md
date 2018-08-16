# http-knocking-docker-compose-example
Example of [http-knocking](https://github.com/nwtgck/http-knocking) on Docker Compose

![demo1](demo_images/demo1.gif)

## Run the server

```bash
docker-compose up
```

## Knocking

After running server, go to <http://localhost:8282/>. However, you should see a blank site.


## Knocking procedure

1. Access to http://localhost:8282/alpha  
1. Access to http://localhost:8282/foxtrot  
1. Access to http://localhost:8282/lima  

Then, you will see a [ghost](https://ghost.org/) site! Ghost is a the open source platform for professional publishers.

You can close the site by the reverse order.
