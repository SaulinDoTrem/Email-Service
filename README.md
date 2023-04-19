# 🛠️ Para rodar o projeto

* Configurar o `application.properties`

  Configurar o banco de dados ;
  
  spring.datasource.url => URL do seu DB
  
  spring.datasource.username => User do seu DB 
  
  spring.datasource.password => Senha do seu DB
  
  spring.jpa.hibernate.ddl-auto => Create para criar, Update em produção
  
* Rotas disponíveis em https://documenter.getpostman.com/view/21091597/2s8Z6vaaoC

### Configuração smtp gmail ###

  * https://support.google.com/accounts/answer/185833 // vai precisar da senha fornecida seguindo o passo a passo do link

    spring.mail.host = smtp.gmail.com
  
    spring.mail.port = 587
  
    spring.mail.username = seu-email@gmail.com
  
    spring.mail.password = a-senha-fornecida
  
    spring.mail.properties.mail.smtp.auth=true
    
    spring.mail.properties.mail.smtp.starttls.enable=true
