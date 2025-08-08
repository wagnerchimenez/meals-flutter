# meals-flutter

# Como executar aplicação

```shell
# Criar o container da aplicação
docker compose up -d

# Baixar dependências do projeto
docker exec -it meals bash
flutter pub get

# Executar aplicação
flutter run -d web-server --web-port=80 --web-hostname=0.0.0.0
```

Acessar URL
- [http://localhost](http://localhost)