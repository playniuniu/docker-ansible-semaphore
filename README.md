# Docker for ansible-semaphore

### Run

1. You need create a mysql/mariadb 

2. You need to create **semaphore_config.sh** file, the example file is in config/ folder

3. Put your **semaphore_config.sh** in YOUR_FOLDER and run command:

    ```bash
    docker run -d --name=semaphore -p 3000:3000 -v YOUR_FOLDER:/data playniuniu/ansible-semaphore
    ```

### Desc

- Dockerhub: [playniuniu/ansible-semaphore](https://hub.docker.com/r/playniuniu/ansible-semaphore/)

- Github: [docker-ansible-semaphore](https://github.com/playniuniu/docker-ansible-semaphore)

- For detail, you could check the [ansilbe-semaphore](https://github.com/ansible-semaphore/semaphore)
