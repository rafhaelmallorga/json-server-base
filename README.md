# Seja bem-vindo a esta API

## **Desenvolvida por Rafhael Mallorga.**

---

Para criar um novo usuario voce deve utilizar um dos endpoints abaixo:

> POST /register

> POST /signup

> POST /users

O corpo da mensagem deve conter no minimo as chaves abaixo:

```
{
  "email": "email@email.com",
  "password": "password"
}
```

Para efetuar o login use qualquer um dos dois endpoints abaixo:

> POST /login

> POST /signin

Corpo da mensagem para o login:

```
{
  "email": "email@email.com",
  "password": "password"
}
```

## **Criando um novo Post**

Utilize o endpoint `/posts` com o metodo `POST`

Obs: É necessário estar logado para criar novos posts (Token obrigatório)

## **Listando os Post**

Utilize o endpoint `/posts` com o metodo `GET`

## **Criando um novo Comentario**

Utilize o endpoint `/comments` com o metodo `POST`

Obs: É necessário estar logado para criar novos comentarios (Token obrigatório)

## **Listando os Comentarios**

Utilize o endpoint `/comments` com o metodo `GET`
