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

**Analise de valor limite - Caixa Preta**


<img width="539" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/c6962fd8-b323-46df-ba6a-cd062dc0568d">


<img width="580" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/d236712c-28da-4f76-aa68-c98ece56a30b">


**Tabela de decisão - Caixa Preta**


<img width="542" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/1343ef47-7eb1-4e93-819c-2c5e5a9753ed">


<img width="581" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/3862cc8b-ba65-42de-88c1-364403859fdb">


<img width="582" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/908d4a38-17c6-418a-9353-985410e99d51">

*Exemplo PIX*


<img width="613" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/19c96f4f-2b06-461d-a66b-e3cf98bbce79">


<img width="613" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/dfaf5779-162b-4fc6-b9b6-f4bd230d45ac">

**Transição de Estado - Caixa Preta**


<img width="564" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/d379fb73-bee2-47fd-b93e-c2fd88a19a2f">

*Exemplo - Compra Online*

<img width="608" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/69a78717-5cb5-4bae-82d0-799acad8a8a6">

**Técnicas de Teste Caixa Branca**


<img width="548" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/8303ce30-aee7-4fa8-a46f-15e9e4bddff8">

Isso quer dizer que o testador tem que ter acesso e conhecimento sobre a estrutura interna daquele sistema/software, tem que conhecer o código fonte, arquitetura, a tecnologia, tudo que compõe, 
tudo que ajudou a construir aquele software.

Quando realizamos teste caixa-branca nós abrimos o código fonte  e vai identificando pontos que vai ser necessário ser testado, por exemplo um if que tem muitas condicionais, ou seja verifica os pontos e verifica se todas aquelas combinações estão funcionando.

**Cobertura de Instrução - Caixa Branca**


<img width="588" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/97178a41-8880-4dc9-8361-7a04b9879337">

*Exemplo Consumo de alcool*

100% de cobertura
<img width="589" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/ad15cd49-4921-47fc-a504-d9ad572776fc">


se eu colocar 18, falta validar o menor que 18...
<img width="612" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/fd9b5a6d-63d6-4f4e-b6c0-bef97dff8980">


**Cobertura de Decisão - Caixa Branca**


<img width="545" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/5517945f-df07-46d7-bfd2-9427c56e8234">

verifica se todas as condicionais estão sendo executadas.

Exemplo: 100% de cobertura, feito teste de decisão;E não precisa está explicito, é importante também conhecer a regra de negócio;

<img width="586" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/3551fa49-29c6-499f-a751-6eb8a546a377">

**Baseada na Experiência**


<img width="572" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/8c0d84ad-d877-40c6-ac38-548d23bef3a2">

é uma técnica empirica baseada na experiência do testador.

*Suposição de erro*


<img width="597" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/dd70a500-67bb-4bf4-acb5-1d5c2dd2b5ff">

*Teste exploratório*


<img width="593" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/1f554fda-cc85-4a56-8f64-c9571014a57d">


*Testes baseados numa lista de verificação*


<img width="603" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/1ef8e092-3210-4f8f-a8c3-b791f1a00aae">


<img width="587" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/45e0955f-673c-4d40-86c7-d973395123a3">

