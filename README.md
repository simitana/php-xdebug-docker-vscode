## Ambiente de depuração PHP/XDebug com Docker
### Como usar:
no terminal rode os seguintes comandos:
```bash
git clone git@github.com:simitana/php-xdebug-docker-vscode.git
cd php-xdebug-docker-vscode
docker compose up
```
após o build o servidor podera ser acessado em `127.0.0.1:8123/testes.php`
o XDebug precisa iniciar uma sessão, portando na url deve ser passado o parametro `XDEBUG_SESSION`, exemplo `127.0.0.1:8123/testes.php?XDEBUG_SESSION`
