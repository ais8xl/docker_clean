## Setup clean project
1. Build/run containers

   ```
   docker-compose up -d
   ```
3. Enter to container

  ```
   2.1 Show docker containers
   -   docker container ls
   2.2 Enter to container
   -   docker exec -it <CONTAINER ID> sh
  ```
5. Run commands for project installation:

  ```
   composer install
  ```
