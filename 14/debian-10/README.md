
docker build -f Dockerfile-Custom -t ghcr.io/desaccu/bitnami-docker-postgresql-repmgr/postgresql-repmgr:14.3.0-debian-10-r18 .

docker push ghcr.io/desaccu/bitnami-docker-postgresql-repmgr/postgresql-repmgr:14.3.0-debian-10-r18


docker build -f Dockerfile-Custom -t registry.kub.cloudccu.cl/ops/postgres-ha-kube/postgresql-repmgr:14.3.0-debian-10-r18 .

docker push registry.kub.cloudccu.cl/ops/postgres-ha-kube/postgresql-repmgr:14.3.0-debian-10-r18