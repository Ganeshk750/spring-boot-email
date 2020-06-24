# spring-boot-email
Spring Boot Sending Email with Freemarker HTML Templete

#POST REQUEST:-
```http://localhost:8080/sendingEmail```
```json
{
	"to": "abc@gmail.com",
	"from": "def@gmail.com",
	"subject": "Test Mail",
	"name": "DEMO NAME"
}
```
#OutPut:-
```
{
    "message": "mail send to : abc@gmail.com",
    "status": true
}
```
