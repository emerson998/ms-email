# MS-EMAIL

Serviço de envio e consulta de e-mails utilizando **Java + Spring Boot** e **JavaMailSender**.

## Funcionalidades
- Envio de e-mails com remetente, destinatário, assunto e corpo da mensagem.
- Registro do status de envio (`SENT` ou `ERROR`) e data/hora de envio.
- Persistência das informações no banco de dados.
- Consulta paginada de todos os e-mails enviados.
- Consulta de e-mail por ID (`UUID`).

---

## Tecnologias Utilizadas
- **Java 17**
- **Spring Boot**
- **Spring Data JPA**
- **Spring Mail (JavaMailSender)**
- **Lombok**
- **Banco de dados** (PostgreSQL)
- **Maven**
