# json-server-config

* ter o Node instalado na maquina
* rodar no comando: npm init -y
* instalar o json-server: npm i json-server

## criar a fake-api
* npx json-server --watch database.json

### Obs
* Toda vez que nós alterarmos o arquivo database.json manualmente, temos que para o comando no terminal e roda novamente.

Ex: rode o comando CTRL + d para parar o terminal e depois rode novamenteo comando npx json-server --watch database.json para ver a alteração.

* adicionar o arquivo .gitignore para adicionar a pasta node_modules
ex: no arquivo .gitignore, digite: node_modules/