# Keycloak

Keycloak is an Open Source Identity and Access Management solution for modern Applications and Services.

This repository contains the source for spinning Keycloak Server, PhpMyAdmin, MySql MariaDB containers.


## Help and Documentation

* [Documentation](https://www.keycloak.org/documentation.html)
* [User Mailing List](https://groups.google.com/d/forum/keycloak-user) - Mailing list for help and general questions about Keycloak

Special Thanks:

courtesy : https://www.youtube.com/watch?v=1u8GlfKyB_Q&t=0s

github : https://github.com/leodip/demo-golang-fiber-keycloak-nextjs/tree/f83d339a2918eb3a326b172a18b76f45dd9247fe/docker


Most of the compose script was extracted from the learnings from above video

Note:

Make sure to remove the volumes that was created by the compose.

```docker volume rm keycloak-on-docker_mariadb-server-vol```

otherwise the inital sql script wont be executed which is needed the create the keycloak database and the default user before the keycloak warms up

```on your terminal run docker compose up```
