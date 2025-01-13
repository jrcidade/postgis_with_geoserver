# postgis_with_geoserver
Docker projetct with postgis and geoserver

Repositório para usar em um Servidor Local para usar os arquivos em produção.
[Dúvidas](https://wa.me/message/H73OMWQ3X346E1)

>`Baixar o repositório do github:`
```
git clone git@github.com:jrcidade/postigis_with_geoserver.git
```
>`Acessar a pasta: postgis_with_geoserver e mover o arquivo env.example para .env:`
```
sudo cp env.example .env
```
>`Editar as seguintes variáveis:`
<br />
DB_NAME=db_name
<br />
LC_ALL=C.UTF-8
<br />
POSTGRES_USER=postgres
<br />
POSTGRES_PASSWORD=XXXXXX
<br />
POSTGRES_DB=db_name
<br />
DB_PORT=port_ext:5432
<br />
<br />


>`Construir o projeto`
```
sudo docker-compose up --build
```
>`Subir o projeto`
```
sudo docker-compose up --d
```

