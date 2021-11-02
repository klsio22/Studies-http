### Para instalar JSON Server , obs (deve ter o node instalado na maquina)

`npm install -g json-server`

---
### Para inicializar um servidor db.json

`json-server --watch db.json`

---
### parâmetros usados

-I = para pegar o head
-X = executar o metodo
-v = pegar todos elementos 
-d = inserir dados nos recursos
-H = Tipos de dados

---

### Para pegar o respose

`curl protocolo-subdomínio-domínio-path` 

---
### Para pegar o headers sem o body

`curl --head protocolo-subdomínio-domínio-path`
`curl -I protocolo-subdomínio-domínio-path`

---
### para pegar o headers com o body

`curl -i protocolo-subdomínio-domínio-path`

---
### Para pegar todos elementos 

`curl -v protocolo-subdomínio-domínio-path`

---
### Para receber o método OPTION sem o body somente o header

`curl -X OPTIONS protocolo-subdomínio-domínio-path -i`

---
### Inserir um dado na tabela com o método POST no back-end

`curl -d '{ "id": 3, "title": "json-server-3", "author": "Keyvin" }' -H "Content-Tye: application/json" -X POST protocolo-subdomínio-domínio-path`

---

### Método PUT Para Atualizar um recurso por completo no back-end não é recomendado para formulários pois não é seguro

`curl -d '{"name":"kleydimison"}' -H 'Content-Type: application/son' -X PUT protocolo-subdomínio-domínio-path`

---

### Método PATCH Para fazer Atualização/Alteração parcial

`curl -d '{"author": "Jeferson" }' -H "Content-Type: application/json" -X PATCH protocolo-subdomínio-domínio-path/id`

---

### Método DELETE Vai deletar dados deve ser aplicado em formulários pois não é seguro perca do dado será inalterável

`curl -X DELETE protocolo-subdomínio-domínio-path/id`

