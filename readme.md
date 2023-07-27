keycloak identiy management server with mysql mariadb on docker 

courtesy : https://www.youtube.com/watch?v=1u8GlfKyB_Q&t=0s
github : https://github.com/leodip/demo-golang-fiber-keycloak-nextjs/tree/f83d339a2918eb3a326b172a18b76f45dd9247fe/docker
Most of the compose script was extracted from the learnings from above video

Note:

Make sure to remove the volumes that was created by the compose.

```docker volume rm keycloak-on-docker_mariadb-server-vol```

otherwise the inital sql script wont be executed which is needed the create the keycloak database and the default user before the keycloak warms up

```on your terminal run docker compose up```
