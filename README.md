# LARAVEL DOCKER SERVER

Docker-compose to run Laravel apps
## Usage

* Clone repo files in your project root folder .
* Make sure that the port in default.conf .
 file is the same in nginx service in docker-compose.yml .

* then run command :
```bash
docker-compose -d --build
```

* Now you can access your app via` http://127.0.0.1:8080/` or you may change the port .

* You can access phpmyadmin via `http://127.0.0.1:8585/` with server name `mysql` and username `root` and empty password . 
