# Kubernetes

## Executando localmente via docker-compose (`sem Kubernetes`)

```sh
cd Kubernetes/src/api
docker-compose up
```

Acesse: http://localhost:40080/index.html para visualizar o resultado.

## Executando deploy no Kubernetes

Execute a instalação do Helm: https://helm.sh/docs/intro/install/

**Com o ambiente já configurado e imagem dicker já no docker.hub*

> Para subir a imagem para o docker hub foi executado o comando: **docker push alanbarros/apb.store.auth**

Execute:

```sh
cd Kubernetes/helm
helm install meu-app .
```

Acesse: http://localhost:30088/index.html para visualizar o resultado.