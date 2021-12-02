# DockerProjekt2

W celu uruchomienia stack należy użyć polecenia ```docker-compose up -d```

Do utworzenia bazy danych należy uzyć polecenia ```docker exec <nazwa_kontenera> mysql --execute="CREATE DATABASE <nazwa_bazy_danych>" --user=<nazwa_uzytkownika> --password=<haslo_uzytkownika>```

Do wygenerowania struktury projektu należy użyć polecenia ```docker container run --rm -it --name mgraph -v $(pwd):/input pmsipilot/docker-compose-viz render -m image docker-compose.yaml```
