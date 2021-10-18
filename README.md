# API Simples com NodeJS

# Descrição

API de clientes simples em NodeJS, com lista de clientes (db), aplicada no Postman e com os métodos: GET - rota: '/' (listar todos os clientes), POST - rota: '/add' (criar um cliente informando o id, nome e idade) e DELETE - rota: '/:id' (deletar um cliente infoemando o id).

# Dependências usadas

- express (framework web que roda o nodejs em tempo de execução); 
- body-parser (faz formatação e transformação de dados vindos do usuário);
- cors (recurso HTTP que permite que um aplicativo web em execução em um domínio acesse recursos em outro domínio); 
- nodemon (biblioteca do nodejs que reinicia automáticamente o servidor); 
- morgan (faz login ou mostra quais requisições estão chegando no servidor HTTP).

# Comando no terminal para rodar a aplicação

```bash
npm start
```

# Comando no terminal para parar a aplicação

```bash
Ctrl + C
```

# Resultado

- testar o método get no navegador:

colocar o link: https://localhost:18062 no navegador

<span>
      <img src="https://user-images.githubusercontent.com/85804895/137651291-416f826e-8f13-469b-9025-5cff1dfa4ed5.gif", width=900>
</span>




