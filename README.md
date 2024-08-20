# ansible-docker-services-role

I can define services in the `services/` directory.  
Each service gets its own directory with a `docker-compose.yml` and a (optional) `.env` file.

In the `docker-compose.yml` and `.env` file you can use variables from the `vars/vault.yml` using the Jinja syntax.
