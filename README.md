# Kubernetes

## Executando localmente via docker-compose (`sem Kubernetes`)

```sh
cd Kubernetes/src/api
docker-compose up
```

Acesse: http://localhost:40080/index.html para visualizar o resultado.

## Executando deploy no Kubernetes

**Com o ambiente já configurado e imagem dicker já no docker.hub*

> Para subir a imagem para o docker hub foi executado o comando: **docker push alanbarros/apb.store.auth**

Execute:

```sh
cd Kubernetes/manifest
kubectl apply -f .
```

Acesse: http://localhost:30088/index.html para visualizar o resultado.