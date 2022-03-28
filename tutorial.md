# Por onde começar? 

Uma grande dificuldade em iniciar na área é por onde começar a estudar. Além dos recursos listados no início desse projeto, uma boa maneira de começar é fazendo um projeto simples de backend você mesmo e tentar vincular isso com o que você leu, viu em algum curso ou teve contato. 

A ideia desse tutorial é fazer com que você possa ter uma experiência mão na massa para começar a entender e criar aplicações de backend. 

## Uma proposta

Para começar, vamos partir do *problema* que queremos resolver. No caso do nosso tutorial, vamos partir do seguinte: 

Suponha que você faz parte de um time de desenvolvimento, e o seu objetivo é garantir que as demandas que surgirem para o sistema backend do seu site sejam implementadas. 
O seu time já tem uma aplicação front-end que é responsável por fazer o carregamento de páginas de um site, e até então, tudo era feito utilizando um provedor externo de serviços -- ou seja, apenas o frontend é mantido pelo time do qual você faz parte. 

Então, surge a decisão de que, a partir de agora, vamos iniciar um projeto de migração para fazer com que o nosso site também tenha a parte de backend sendo desenvolvida internamente. 

Antes de tudo, coisas que são importantes nesse tipo de discussão e que provavelmente foi a motivação para tomar essa decisão: 
- será que precisamos fazer tudo internamente? 
- qual será o custo disso para a nossa empresa? 
- ponderar entre o custo e ganho realmente reflete na solução de trazer o desenvolvimento para dentro de casa? 

Dado que essas perguntas foram respondidas pelo seu gerente ou lider técnico como sim, vamos implementar, agora a nossa missão é fazer essa migração acontecer. 

Temos várias formas de conduzir esse processo:

1. Passar meses reescrevendo todas as regras de negócio da nossa aplicação em um software novo 
2. Dividir o escopo em diversos pedaços e ir implementando aos poucos e alterando os endpoints chamados no frontend

A opção 2 tende a ser bem aceita, porque foca em progresso contínuo ao invés de uma grande entrega de uma só vez, e o time decide ir por esse caminho. 

Partindo do pressuposto que usamos esse provedor externo para fazer os seguintes fluxos: 

- Cadastro, atualização e exclusão de produtos 
- cadastro de usuário e login
- venda de produtos 

Para essa etapa inicial, vamos fazer a implementação dos endpoints de produtos. 

## Mão na massa

Agora que as decisões burocráticas foram tomadas, vamos começar! Nesse tipo de projeto, quando estamos fazendo isso sem um time, é comum ter vontade de sair escrevendo código. 
Isso é uma abordagem válida quando todos os requisitos (lista de coisas que devem existir no projeto) está muito clara. Spoiler: geralmente esse não é o caso. 

O ideal, então, é tentar estruturar como isso deve ser feito, quais partes serão feitas e em qual ordem, como vamos apresentar isso para pessoas não técnicas, etc. 

Eu particularmente gosto de desenhar. Elaborar um diagrama com os módulos ou pedaços da aplicação. 






