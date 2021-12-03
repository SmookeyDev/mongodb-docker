# MongoDB

## 📝 Requisitos para rodar o banco de dados

- Docker
- Docker Compose

## 💭 Configuração/Inicialização

1.Instale o Docker seguindo o tutorial a seguir:
https://docs.docker.com/engine/install/ubuntu/

2.Instale o Docker Compose seguindo o tutorial a seguir: https://docs.docker.com/compose/install/

3.Clone este repositório usando o seguinte comando:
```terminal
$ git clone git@github.com:smookeydev/mongodb-docker.git
```

4.Copie o arquivo de configuração de exemplo para um arquivo de configuração real:
```terminal
$ cp .env.example .env
```

5.Troque os valores existentes no arquivo de configuração, os valores são:
  * **DB_PORT**: Porta que será usada para o banco de dados. (Opcional)
  * **DB_NAME**: Nome do banco de dados. (Obrigatório)
  * **DB_USER**: Usuário do banco de dados. (Obrigatório)
  * **DB_PASS**: Senha do usuário do banco de dados. (Obrigatório)

6.Inicie o banco de dados rodando o seguinte comando:
```terminal
$ make up
```