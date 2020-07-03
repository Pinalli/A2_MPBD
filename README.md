
### Atividade Prática A2 da cadeira de Modelagem e Projeto de Banco de Dados - PUCRS

* Considere os seguintes artefatos entregues a um time de desenvolvimento por gestores de empresa de aluguel de patinetes:
![relatorio](https://user-images.githubusercontent.com/18580532/86480743-fa0f4b00-bd24-11ea-92c6-1218d26cfb7b.png)
Observações adicionais:

1. Os telefones devem ser armazenados com DDD e número separados.

2. Os parceiros também são usuários. Além dos atributos de usuário eles possuem também um tipo: M – Manutenção ou R – Recarga.

3. Os roteiros podem sair e chegar em uma estação ou não. Caso isso aconteça, a saída ou a chegada da viagem serão associadas à estação. Caso contrário, serão associadas simplesmente a coordenadas. Dica: não é necessário construir uma especialização.

4. Os meios de pagamento possuem um id único e cada um deles está associado a somente um usuário. Eles podem ser de dois tipos: cartões ou contas do Paypal. Sobre cartões é necessário armazenar o número, a bandeira e a validade. Para contas do Paypal é necessário armazenar o número, o username e o limite de crédito.

5. Em acréscimo aos requisitos especificados por meio do relatório e complementados pelos numerados de 1 a 4, descreva em português novos requisitos cuja implementação demande a criação de:
pelo menos mais 4 tabelas, com no mínimo duas colunas cada uma, sendo uma a chave primária;

* um relacionamento 1 para N não identificador;
* um relacionamento 1 para N identificador; e
* um relacionamento N para N com atributos.
* Complemente o lógico com essas novas tabelas e relacionamentos no Astah.

Utilize sua criatividade para criar as entidades e relacionamentos, mas o faça de forma a manter a coerência com a realidade.

1. (5,0) Aplique a técnica de Normalização de Dados conforme vista em aula, desde o diagrama de dependências funcionais, integrando nele o relatório apresentado e as observações adicionais. Após, passe a estrutura para a 1ª, 2ª e 3ª Formas Normais, nesta ordem, apresentando todo o desenvolvimento.

Para desenhar o diagrama de dependências funcionais utilize qualquer editor, como o https://draw.io/. Ou faça no papel e envie uma ou mais fotografias.
Lembre-se da dica que vimos na revisão: inicie construindo um diagrama entidade-relacionamento de rascunho, isso ajudará a encontrar a superkey e a entender qual a estrutura do banco de dados.

2. (5,0) Partindo do resultado da normalização, construa o Esquema Lógico Relacional utilizando a notação do IDEF1X do Astah (Diagrama ER).

O esquema conceitual deverá utilizar chaves primárias simples (uma única coluna), conforme vimos na aula de 17/06/2020.
Deverão ser definidos pelo menos dois índices não-únicos e dois índices únicos (além das chaves primárias), conforme vimos na aula de 22/06/2020.

## Artefatos a entregar

* Um texto online (digitado na própria tarefa) contendo os novos requisitos propostos.

* Um arquivo .ZIP contendo:

* Arquivos com as imagens dos diagramas de dependência funcional construídos para realizar a normalização de dados;

* Um arquivo do Astah contendo o esquema lógico relacional. É responsabilidade do aluno garantir que o arquivo está correto. Arquivos corrompidos e que por qualquer motivo não sejam lidos pela ferramentas serão considerados como "não entregues".
