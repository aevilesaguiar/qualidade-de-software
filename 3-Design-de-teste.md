##Design de Teste

**Pirâmide de Testes e níveis de Testes**

Test Piramide(Martin Fowler)

<img width="463" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/2f9f7e11-a5e3-4b0b-a3ca-3e2e50221158">


https://martinfowler.com/bliki/TestPyramid.html


Qual é a ideia de estratégia dessa pirâmide, que consigamos entender em quais momentos e quanto devemos focar em cada tipo desses testes. Temos 3 tipos de testes nessa piramide o unitario é a maior fatia,
é a base da pirâmide, e dentro da automação de testes também ela é a base.
Quanto mais próximo da parte unitária, mais rápido esse teste executa, ele é mais barato também, ele é um teste rápido, pequeno e não depende de muitas coisas para executar. A performance dele é muito 
rápida e a gente tem um feedback rápido, se a aplicação está dando sucesso ou falha, então ele é muito bom e ele representa uma grande fatia aqui dentro dessa divisão de tipos de teste.

Na dentro desse livro do Google Engineer It Software Engine with Google, nós temos 80% desse teste unitário. Eles usam essa métrica pra dividir entre os times.Tem times que é mais outros que é menos. 
É muito da estratégia é de entender onde o software está dando bugs e erros, aonde tem mais dificuldades
dentro do software para definir a estratégia.Então a gente entender o que o unitário é o mais barato e o mais rápido de ser executado.

A segunda camada tem a integração, que é uma fatia menor, ele também continua sendo mais rápido e mais barato do que o end to end.E ele possui essa fatia, a Google diz que são uns 15% que eles investem 
nessa nesse tipo de teste.

Evpor último end2end, é um tipo de teste que valida como se fosse um usuário mesmo. Ele valida a integração de todas as partes, simulando como se fosse um usuário utilizando a aplicação. A fatia dele é 
muito pequena , por que ele é muito caro e demorado para executar. 

**Teste de Unidade**


<img width="523" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/ab521708-8694-4efe-a0d2-ff147fa558e2">

Valida cada código, função isoladamente.

Função a e b que soma, validando que a função somar deve ser igual a 5.

<img width="324" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/5855e6a8-a14b-427a-b01c-a6951d9f902b">

**Teste de Integração**


<img width="578" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/f2fa30a2-126e-49ec-87d9-daa6a2855a6e">


<img width="584" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/4a32e350-fe8b-43c7-8c8c-cfed0ae02a08">

**Teste end to end**


<img width="560" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/58753511-7a8f-40a3-a21e-81dcba8aa3c4">

Simular a execução do teste como se fosse um usuário;

<img width="586" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/1f9fa59a-2e78-4eff-a4fe-3b19192eb457">

Nesse exemplo foi usado o cypress, simulando um login, está validando os dados, simular um usuário. garantindo que todas as partes estãoo sendo executadas.

Esse teste é muito cara, que não seja penoso, que não quebre.

**Adicionando testes em todos os níveis**


<img width="546" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/5ac18d55-33d4-4f86-8e94-860f4ea25ec0">


<img width="488" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/83f71a5d-cd78-43dc-a132-d166aa98240a">



<img width="547" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/d208ea18-8d5d-4989-8997-fbfffa4cab3f">


<img width="548" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/5e7d35a2-115e-4624-b2fe-d88336eb8bc7">


<img width="546" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/101a2f4e-3ac8-46c3-a145-38ad1183d48a">


<img width="442" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/831c2b54-0f8f-47f1-85e9-d8787972a9b7">


**Teste de Regressão**

<img width="548" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/6fa2360d-9097-43b4-87b2-738f709eda06">

Nosso software recebe uma quantidade de commits, como o software é contantemente alterado, e a função do teste de regressão é exatamente garantir que ele continue funcionando, mesmo após alterações.
O teste de regressão dá mais confiança, manter o software estável, garantir que o que foi implantado funcione e o que já estava implantado continue e funcionar

**Testes Funcionais**

<img width="494" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/2cd08e46-c14e-4623-97b6-f86e779c6b2b">

O teste funcional deve garantir que as regras continuem funcionando, ele é focado no que e em como as regras de negócios são executados, pensa no papel de usuário, e também no nível de unidade.

Ou seja ele é executado em todos os niveis desde unidade até end to end.



**Testes não funcionais**

<img width="527" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/5c2a35bc-a928-43dc-aa22-d44b6516ba57">

Estamos testando o desempenho, tempo de resposta, o teste de usabilidade, o quão é fácil o usuário usar, teste de segurança verificar vulnerabilidade do sistema.
por exemplo uma pagina deve levar no máximo 2 segundos para abrir;


**Teste de Fumaça**


<img width="560" alt="image" src="https://github.com/aevilesaguiar/qualidade-de-software/assets/52088444/9917099d-026c-4905-9835-d6c1693e6721">

O teste de fumaça faz teste nos fluxos principais, são testes rápidos de serem executados pois não exploram a fundo as funcionalidades do software. Com isso temos um feedback rápido.

Smoke teste são automatizados, e garantimos que os caminhos felizes estejam sendo executados corretamente.
