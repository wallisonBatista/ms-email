"# ms-email" 

##Dicas para configurar o projeto

## Utilizar o pg-admin4 com a conexão com o postgreSQL
## Utilizar a senha do gmail para APP's para realizar a configuração no application.properties

##endpoint Post 
http://localhost:8080/sending-email

##dados a serem enviados na requisição 
##{	
    "ownerRef": "nome, depois irá receber um id ...",
	"emailFrom": "email@email.com",
	"emailTo" : "email@email.com",
	"subject": "titulo e-mail",
	"text": "corpo e-mail"
}