# :rocket: Gobarber_backend
 API do gobarber em NodeJs, desenvolvida no Bootcamp GoStack 9.0 da rocketseat
 

### 	:man_technologist: Sobre a api

A Fase 02 do GoStack 9.0 teve como finalidade o dominio do NodeJs, para isso foi desenvolvido uma api que será consumida por uma aplicação web e mobile.

##### Essa api tem como principais funções:
- Criação e gestão de perfis de prestadores de serviços e usuário da aplicação.
- Criação e gestão de agendamentos de serviços.
- Criação de rotas privadas e públicas.
- Autenticação de usuários com JWT.
- Conexão com bancos de dados: postgresql, mongoDB e redis.
- Distribuição de emails aos prestadores de serviço com fila via bee-queue.


### 📁 Instalação

```bash
  #  clone o repositório
  git clone https://github.com/mvgoliveira/gobarber_api

  #  navegue até o repositório clonado
  cd gobarber-api

  #  baixe as dependências
  yarn
  
  #  Crie containers com docker para os bancos de dados
  Docker run --name database -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres:11
  Docker run --name mongobarber -p 27017:27017 -d -t mongo
  Docker run --name redisbarber -p 6379:6379 -d -t redis:alpine
  Yarn sequelize db:migrate

  #  divirta-se!
  yarn dev
  yarn queue
```



### **📝 Licença**

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](https://github.com/mvgoliveira/gobarber_api/blob/main/LICENSE) para mais detalhes.


<hr>

Feito com :hearts: por **[Marcus Oliveira](https://www.linkedin.com/in/marcus-oliveira-3b92011a7/)**.
