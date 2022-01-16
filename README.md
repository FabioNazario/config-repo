# config-repo

Modo de usar:<br>

Adicione a seguinte propriedade no **application.yml** de seu servidor de configuração para utilizar este repositório como arquivo de configuração:

```yml
spring:
  cloud:
    config:
      server:
        git:
          uri: https://github.com/FabioNazario/config-repo
```
