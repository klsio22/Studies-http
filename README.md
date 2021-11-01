### Para instalar JSON Server , obs (deve ter o node instalado na maquina)

npm install -g json-server

### Para inicializar um servidor db.json

json-server --watch db.json

---

### (para pegar o respose)

curl protocolo-subdomínio-domínio-path

### (para pegar o headers sem o body)

curl -I protocolo-subdomínio-domínio-path

### para pegar o headers com o body

curl -i protocolo-subdomínio-domínio-path

### Para pegar todos os headers

curl -v protocolo-subdomínio-domínio-path

### Para receber o metodo option sem o body somente o header

curl -X OPTIONS protocolo-subdomínio-domínio-path -i ()
