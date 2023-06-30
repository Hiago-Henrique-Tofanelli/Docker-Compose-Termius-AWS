# Docker-Compose-Termius-AWS

# POR SFTP

* CRIAR AS PASTAS NO LINUX OU WINDOWS
* ABRIR SFTP NA INSTÂNCIA DESEJADA NA AWS
* UTILIZAR OS COMANDOS A SEGUIR, TENDO COMO BASE UMA PASTA CHAMADA compose-exemplo

* ``` ls ```, para checar se o diretório aparece

* MUDAR PARA O DIRETÓRIO CRIADO

```
cd compose-exemplo
```
* ``` ls ```, para checar se os arquivos estão presentes
* caso necessite alterar algum arquivo por linha de comando
```
sudo apt install vim
```

* Exemplo alterando Docker file

```
vim Dockerfile
```

*Para sair e salvar as alterações

```
esc + :wq
```

* verificando se as informações do arquivo Dockerfile foram alteradas
  
```
cat Dockerfile
```

* SUBIR ARQUIVOS DO COMPOSE
  
```
docker compose up -d
```
