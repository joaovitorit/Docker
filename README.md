########################## PROCEDIMENTOS REALIZADO NO DOCKER ##########################

# Realizando Backup do banco Mysql rodando em container para máquina host

docker exec -i -t nomedobancodedados mysqldump -u root --password=senhadousuárioroot nomedobanco > arquivo.sql

Obs: O nome do arquivo pode ser especificado um caminho de diretório ex: /opt/arquivo.sql


