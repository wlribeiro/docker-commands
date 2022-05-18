### fazer build da imagem
```
docker build <diretorio da imagem>
```
### fazer dowload de uma imagem
```
docker pull python
```

### nomeando imagem
```
docker tag <nome>:<tag>
```

### nomear durante a criação
```
docker build -t nome_da_imagem:tag_da_imagem .
```

### nremover imagem
```
docker rmi <id or name>
```