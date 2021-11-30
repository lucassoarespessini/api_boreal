# API - BOREAL
> Meu nome é Lucas Soares Pessini e estou perticipando do Processo Seletivo do API Boreal.




## Inicializando o Programa

Executa o comando abaixo no diretório onde está o projeto baixado:

```sh
docker-compose up -d
```

Depois acessa o seguinte link http://127.0.0.1/docs#/ onde verica os endpoints que foram desenvolvidos.


## Para Ver Novas Modificações do Código

O código está presente em app/main.py. Caso seja alterado esse código e queira ver as novas modificações, salve o novo código em app/main.py e depois executa o seguinte comando.

```sh
docker exec -it myfastapi uvicorn app.main:app --host 0.0.0.0 --port 81 --reload
```
E as novas modificações serão acessadas na seguinte pagina http://127.0.0.1:81/docs#/.