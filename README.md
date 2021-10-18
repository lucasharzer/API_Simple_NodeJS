# API Simples com NodeJS

- Descrição

API de clientes simples em NodeJS, com lista de clientes (db), aplicada no Postman e com os métodos: GET - rota:'/' (listar todos os clientes), POST - rota:'/add' (criar um cliente informando o id, nome e idade) e DELETE - rota:'/:id' (deletar um cliente infoemando o id).

- Dependências usadas

1 - express (framework web que roda o nodejs em tempo de execução); 
2 - body-parser (faz formatação e transformação de dados vindos do usuário);
3 - cors (recurso HTTP que permite que um aplicativo web em execução em um domínio acesse recursos em outro domínio); 
4 - nodemon (biblioteca do nodejs que reinicia automáticamente o servidor); 
5 - morgan (faz login ou mostra quais requisições estão chegando no servidor HTTP).

- Comando para rodar a aplicação

```bash
npm start
```





