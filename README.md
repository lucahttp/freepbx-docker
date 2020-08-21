# freepbx docker compose


<div>
<img  src="https://upload.wikimedia.org/wikipedia/en/1/19/FreePBX_Logo.jpg"  width="150px"  height="150px">
<img  src="https://upload.wikimedia.org/wikipedia/commons/4/4e/Docker_%28container_engine%29_logo.svg"  width=""  height="150px">
</div>
  
  

to have your own freepbx server you need to run the following command

  

```console
docker-compose -f "docker-compose.yml" up -d --build
```
or

```console
docker-compose up --force-recreate --renew-anon-volumes --build
```

  
  

is a docker compose to create a complete containerized solution for FreePBX, it contains a mysql container and an freepbx container that runs something that made tiredofit, made for a trainig purposes
