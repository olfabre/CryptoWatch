10 décembre

- Mis en place du site kawaiimediagroup.com qui hébergera les fichiers de l'application (serveur de production environnement Apache et php version 8.2.26  )

- Mise en place d'une dépôt git https://github.com/olfabre/CryptoWatch

- Installation Base de donnée: 
  Nom de la base de données distante: admin_CryptoWatch

- Serveur de bases de données 

  localhost:3306 (valeurs par défaut de MariaDB, v10.3.39)

Nom de l'utilisateur de la base de données * cryptowatch

mot de passe: 0590135%

Accès: phpAdmin https://51.178.36.249:8443/phpMyAdmin/index.php?db=admin_CryptoWatch

- installation de composer version 2.6.5 à la racine
- installation bibliothèques "vlucas/phpdotenv": "^5.6" pour gérer le variables d'environnements entre le serveur Dev et Prod
- On fige l'environnement php en verison 7.4.* pour la comptatibilité avec doctrine

on installer docker sur le local (mon post)
J'ai récupérer docker desktop pour Catalina que l'on peut retrouver à l'adresse suivante https://github.com/docker/for-mac/issues/6671#:~:text=https%3A//desktop.docker.com/mac/main/amd64/93002/Docker.dmg

mais aussi sur mon dépôt dans le répertoire /docker_catalina/Docker.dmg

On doit l'installer sur le mac et l'ouvrir

ensuite sur le CLI, faire la commande

```bash > docker info ```

résultat:

```bash
Client:
 Context:    default
 Debug Mode: false
 Plugins:
  buildx: Docker Buildx (Docker Inc., v0.9.1)
  compose: Docker Compose (Docker Inc., v2.13.0)
  dev: Docker Dev Environments (Docker Inc., v0.0.5)
  extension: Manages Docker extensions (Docker Inc., v0.2.16)
  sbom: View the packaged-based Software Bill Of Materials (SBOM) for an image (Anchore Inc., 0.6.0)
  scan: Docker Scan (Docker Inc., v0.22.0)

Server:
 Containers: 0
  Running: 0
  Paused: 0
  Stopped: 0
 Images: 0
 Server Version: 20.10.21
 Storage Driver: overlay2
  Backing Filesystem: extfs
  Supports d_type: true
  Native Overlay Diff: true
  userxattr: false
 Logging Driver: json-file
 Cgroup Driver: cgroupfs
 Cgroup Version: 2
 Plugins:
  Volume: local
  Network: bridge host ipvlan macvlan null overlay
  Log: awslogs fluentd gcplogs gelf journald json-file local logentries splunk syslog
 Swarm: inactive
 Runtimes: runc io.containerd.runc.v2 io.containerd.runtime.v1.linux
 Default Runtime: runc
 Init Binary: docker-init
 containerd version: 770bd0108c32f3fb5c73ae1264f7e503fe7b2661
 runc version: v1.1.4-0-g5fd4c4d
 init version: de40ad0
 Security Options:
  seccomp
   Profile: default
  cgroupns
 Kernel Version: 5.15.49-linuxkit
 Operating System: Docker Desktop
 OSType: linux
 Architecture: x86_64
 CPUs: 4
 Total Memory: 7.675GiB
 Name: docker-desktop
 ID: NCHV:Q4XQ:AED5:OIOV:NWFH:TZ5N:FBW7:DWHI:IJM7:SQN3:3I7R:U6QG
 Docker Root Dir: /var/lib/docker
 Debug Mode: false
 HTTP Proxy: http.docker.internal:3128
 HTTPS Proxy: http.docker.internal:3128
 No Proxy: hubproxy.docker.internal
 Registry: https://index.docker.io/v1/
 Labels:
 Experimental: false
 Insecure Registries:
  hubproxy.docker.internal:5000
  127.0.0.0/8
 Live Restore Enabled: false
```

le serveur distant est en php 7.4.33

Nous allons donc charger dans un premeir temps une image légère pour cette même version php 7.4.33

```bash
docker pull php:7.4.33-cli
```

![3](3.jpg)



On le voit afficher sur docker desktop dans l'onglet image

![4](4.jpg)





