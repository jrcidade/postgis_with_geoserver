# postgis_with_geoserver
Docker projetct with postgis and geoserver

>`Baixar o repositório do github:`
```
git clone git@github.com:jrcidade/postigis_with_geoserver.git
```
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

