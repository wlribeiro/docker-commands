# docker commands

### docker run
```
docker run ubuntu
```

### manter rodando no terminal
```
docker run -it ubuntu
```


### ver containes em execução
```
docker ps
```
ou
```
docker container ls
```

### ver containes que foram executados
```
docker ps -a
```

### executar em background
```
docker run -d nginx 
```

### expor porta
```
docker run -d -p 80:80 nginx
```

### parar container
```
docker stop <id or name>
```

### iciar containers
```
docker start <id or name>
```

### iciar containers com terminal
```
docker start -it <id or name>
```

### nome para um container
```
docker run -d -p 80:80 --name ngx_app nginx
```

### acessando logs
```
docker logs <id or name>
```

### remover containers da maquina
```
docker rm <id or name>
```

### remove tudo que não esta sendo usado
```
docker system prune
```

### remove container apos execução
```
docker run -rm <container>
```

### copiar para um container ou do container para maquina
```
docker cp caminho1 caminho2
```

### verificarinformações do processamento
```
docker top
```