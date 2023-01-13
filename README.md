# Full Cycle - Desafio GO

## Pré-requisitos:
* Publicar a imagem no docker hub
* Apresentar no console 'Full Cycle Rocks!!'
* imagem precisa ter menos de 2MB

## Via código

Após o projeto clonado, para buildar a imagem docker

```
docker build -t <name> . -f Dockerfile
```

Para rodar
```
docker run --name fullCycle <name>
```

## Rodando via Docker HUB

Rodar o comando
```
docker run --name fullCycle fabiostefani/fullcycle:latest
```


### Ambos os modos deve imprimir
Full Cycle Rocks