# postgresql and pgadmin

## STEPS

(edit and use your own credentials before running the command: docker-compose up -d)

1. docker-compose up -d
This will pull the images and run the configuration specified in docker-compose.yml file. -d is for detach mode
2. open the pgadmin: open a browser and enter localhost:8000
3. login the credentials specified in the docker-compose.yml.
4. on the left side right click the Servers: Create > Server
  * General tab - enter your server name
  * Connection tab
    - Hostname/address: postgres
    - username: enter username
    - password: enter password
