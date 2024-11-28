# Podman commands

## installation

https://github.com/containers/podman/blob/main/docs/tutorials/podman-for-windows.md#podman-for-windows

```
podman machine init

podman machine start
```

connect to VM
```
podman machine ssh
```

Run container httpd
```
podman run -dt -p 8080:80/tcp docker.io/library/httpd
```

Other useful commands:
```
podman container ls

podman ps

podman logs 30c8687948ec

podman stop 30c8687948ec

podman ps -a

podman images

podman rm 30c8687948ec #remove container

podman rmi docker.io/library/httpd #remove image
```

```
