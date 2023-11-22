Assignment 2 Part 2

1. Docker File created for web(php)
2. Docker File created for db (mysql)
3. Docker Compose file created for web & db
4. Dcoker Compose Up Command and running on localhost:8001
5. Modify the php file and other lines are also working
6. Docker Scale
   docker-compose up --scale web=3
[+] Building 0.0s (0/0)                                                                                  docker:default
[+] Running 2/2
 ✔ Network part2_default  Created                                                                                  0.1s
 ✔ Container part2-db-1   Created                                                                                  0.1s
WARNING: The "web" service is using the custom container name "php_web". Docker requires each container to have a unique name. Remove the custom name to scale the service.
