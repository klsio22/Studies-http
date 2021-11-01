### Para instalar JSON Server , obs (deve ter o node instalado na maquina)

npm install -g json-server

### Para inicializar um servidor db.json

json-server --watch db.json

---

### (para pegar o respose)

curl protocolo-subdomínio-domínio-path

### (para pegar o headers sem o body)
curl --head protocolo-subdomínio-domínio-path
curl -I protocolo-subdomínio-domínio-path

### para pegar o headers com o body

curl -i protocolo-subdomínio-domínio-path

### Para pegar todos os headers

curl -v protocolo-subdomínio-domínio-path

### Para receber o metodo option sem o body somente o header

curl -X OPTIONS protocolo-subdomínio-domínio-path -i ()
---
### Inserir um dado na tabela com o metodo post no back-end
curl -d '{ "id": 3, "title": "json-server-3", "author": "Keyvin" }' -H "Content-Tye: application/json" -X POST http://localhost:3000/posts

---

### Metódo PUT Para Atualizar um recurso por completo no back-end não é recomendado para formulários
curl -d '{"name":"kleydimison"}' -H 'Content-Type: application/son' -X PUT protocolo-subdomínio-domínio-path

---

### Metodo PATH 