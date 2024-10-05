## TECH CHALLENGE

### Descrição do problema

O laboratório de exames clínicos, Check Lab está enfrentando problemas com o não comparecimento de pacientes que realizam agendamentos de exames. Ao não realizarem o cancelamento do agendamento o laboratório não consegue liberar o horário para um novo paciente, o que acarreta prejuízos para o mesmo.

### Descrição da solução encontrada

Com o intuito de diminuir ou até mesmo zerar os não comparecimentos, optou-se por contratar uma empresa para fornecer o serviço de confirmação de agendamento seja via SMS, WhatsApp ou outros meios cabíveis.

### Descrição do software a ser implementado

Para que o fornecedor de confirmações de agendamento consiga nos atender, foi solicitado a disponibilização de uma API Rest onde ele possa recuperar uma lista de agendamentos a serem confirmados e onde ele possa informar quais agendamentos foram cancelados. 

Foi realizado um mapeamento no Miro de todo o processo de agendamento de exames, o link para o Miro se encontra logo abaixo neste documento. 

Apesar de mapear todo o processo de agendamento, optamos por implementar apenas um protótipo da API Rest que servirá o fornecedor de confirmações de agendamento. Com isso trabalharemos em um Subdomínio de Suporte, ou seja, um processo que auxilia o subdomínio principal.

### Conclusão

Para o mapeamento e entendimento do que precisava ser implementado, utilizamos os conceitos de DDD para auxiliar no processo.

O Domain-Driven Design (DDD) é uma abordagem de desenvolvimento de software que se concentra no domínio do problema que o software está resolvendo. O DDD fornece um conjunto de princípios e práticas que ajudam a modelar o domínio de forma clara e concisa, o que nos auxiliou nos seguintes pontos:

- O DDD ajudou a garantir que nós tivéssemos um completo entendimento dos processos envolvidos no domínio principal. Com esse entendimento conseguimos separar os processos em domínio principal e em domínios de suporte.
- Com o auxilio do DDD tentamos abstrair o máximo possível para que a solução desenvolvida fosse o mais adaptável possível às mudanças no domínio do problema.
- A organização que o DDD trás ajuda a criar software que é mais fácil de manter e evoluir. Isso ocorre porque somos orientados a pensar na reutilização de componentes e a modularização do código.

O processo de Event Storming e Brainstorming parece inicialmente algo não muito produtivo, mas notamos durante nossos encontros que é um processo fundamental. O embate de ideias e de pontos de vistas de vários atores que estão envolvidos com o processo e que possuem diferentes visões sobre o mesmo, torno o processo do mapeamento muito rico em detalhes e na descoberta de possíveis falhas futuras.

Em resumo esperamos que com a solução proposta a clinica tenha uma quantidade menor de não comparecimentos aos agendamentos.

### Entregáveis

Documentação de Event Storming: https://miro.com/app/board/uXjVNAM5emU=/

