# Curso Microsserviços Java com Spring Boot e Spring Cloud

Foi criado uma aplicação bem simples, simulando um RH, mas com foco em microserviços, portanto o projeto não tem lógicas complexas, requisições customizadas e nem tratamento de erros.

### Visão geral do sistema

![Visão geral do sistema](https://raw.githubusercontent.com/santosediego/assets/8008adffc743f808795c9578c67874d129b4fa33/microsservicos/visaoGeralSistema.png)

### Modelo conceitual do projeto

![Modelo conceitual](https://raw.githubusercontent.com/santosediego/assets/8008adffc743f808795c9578c67874d129b4fa33/microsservicos/modeloCenceitual.png)

## Competências
- Feign;
- Ribbon;
- Eureka;
- Hystrix;
- Zuul;
- Configuração centralizada;
- Oauth 2.0;
- Jwt;
- Docker

### Collection Postman completa

[`Postman| Collection`](https://api.postman.com/collections/1242165-67d08dc0-531c-45aa-a211-a02cba6f0e5d?access_key=PMAT-01GKP91EKZCH09H3PX5YYXESA1)

### Environment Postman

```
api-gateway : http://localhost:8765
config-host : http://localhost:8888
client-name : myappname123
client-secret : myappsecret123
username : leia@gmail.com
password : 123456
token :
```
## Como executar o projeto

Pré-requisitos:
- Java 11;
- Configurações da aplicação no [github](https://github.com/acenelio/ms-course-configs);
- Executar primeiramente o projeto hr-config-server em seguida hr-eureka-server, os demais não tem ordem correta.

```bash
# clonar repositório
git clone https://github.com/santosediego/microsservicos.git

# entrar na pasta referente ao microserviço
cd microsservicos/hr-...

# executar o projeto
./mvnw spring-boot:run
```

# Autor

[Diego Santos](https://www.linkedin.com/in/santosediego/ "Perfil Linkedin Diego Santos")

[`Certificado do curso | Udemy`](https://www.udemy.com/certificate/UC-50e35a13-fdf9-4f6e-ad0d-316b53559d02/) 🚀
