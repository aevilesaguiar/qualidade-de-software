## Técnicas de Testes

O que são técnicas de testes?

<img width="574" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/ab60aa9c-a775-4534-ac8b-bf1d0c6bbf40">

**Técnica de teste Caixa Preta**


<img width="533" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/83765ff8-ad02-4e6d-8a77-0099e6f2e445">

Ou seja , agente não se importa como aquele software foi construido, qual a tecnologia se é java, C#...se é microsserviço. monolito, qual o banco de dados utilizado, nada disso importa. 
Nós temos um software pronto e a nossa preocupação é saber qual dado iremos inputar, quais os dados que esperamos como resultado. 

**Partição por Equivalência - Caixa Preta**


O que é?

<img width="548" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/f313ea82-e45e-497e-863c-4c727b2d387d">


Exemplo; SENHA


<img width="595" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/4fe82144-4549-426a-86df-ee418637057c">

3 REGRAS DE NEGÓCIOS 
e a tabela que garante que elas sejam validadas


<img width="596" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/7edc700b-a8fb-4362-a33d-c936d77d9268">
Se olharmos essas 3 regras  e a nossa tabela ao lado garantimos que o sistema realmente cumpre os 3 itens da regra de neócio não permitem esses tipos de senhas

Outro exemplo: Votação


<img width="587" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/525f8237-8b85-4f19-a079-759f6ea4529c">

Com essas entradas eu consegui testar as minhas regras de negócios.
