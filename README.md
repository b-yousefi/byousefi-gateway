# byousefi-gateway

`docker-compose.yml` uses `Dockerfile` to build a **nginx** docker image which is configured to pass requests to two running web application based on the request url on ports **80** and **443**.

-  requests starting with `/bookshop/` or `/bookshop`  are passed to `bookshop_react` docker container, running image of [bookshop-react](https://github.com/b-yousefi/bookshop-react) project
-  requests starting with `/portfolio/` or `/portfolio` are passed to `portfolio_react` docker container, running image of [portfolio](https://github.com/b-yousefi/portfolio) project
