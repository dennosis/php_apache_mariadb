# Ambiente de desenvolvimento com php, apache, mariadb, codeignaiter

1 - instalar docker: 
    docker-compose
    docker

2 - baixar as imagens dos servicos com os comandos (pode ser que precise rodar como administrador: 
    docker pull php
    docker pull mariadb

3 - comando para iniciar o ambiente (pode ser que precise rodar como administrador):
    docker-compose up


OBS:

- antes de rodar verificar se não esta rodando o apache(xamp/wamp);
- Quando sobe os container do banco pela primeira vez eles iniciam vazios, ai tem importar uma base