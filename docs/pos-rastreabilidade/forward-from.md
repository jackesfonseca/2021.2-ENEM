# Matriz Forward-From
## 1. Introdução

Rastreabilidade é uma característica de sistemas, nos quais os requisitos são claramente ligados às suas fontes, bem como aos artefatos criados durante o ciclo de vida de desenvolvimento do sistema. Um elo é estabelecido entre as mudanças realizadas diante das necessidades dos usuários.

A Pós-rastreabilidade consiste em requisitos sendo ligados a artefatos que são criados durante o ciclo de vida de desenvolvimento do sistema.

A técnica de Pós-rastreabilidade Forward-From visa ligar requisitos a artefatos de desenho e implementação.

## 2. Legenda
Os elos de rastreabilidade deixam evidentes as correlações entre código e demais artefatos, sejam de desenho e/ou de requisitos.
O Meta-modelo de Toranzo permite debater sobre os elos de rastreabilidade. Nesse modelo, as informações a serem rastreadas devem ser classificadas em quatro níveis:

- Ambiental: congrega informações oriundas do contexto ambiental onde a organização está inserida e que podem afetar o sistema sendo desenvolvido;
- Organizacional: reune informações relacionadas à organização (missão, objetivos, metas e padrões) e que podem impactar os requisitos do sistema;
- Gerencial: agrega informações que permitem associar tarefas a requisitos, e que podem auxiliar a gerência do projeto;
- Desenvolvimento: abarca informações relacionadas aos diversos artefatos gerados no processo de Desenvolvimento, Gerencial;

E os principais elos de rastreabilidade são:

- Satisfação: classe origem tem dependência de satisfação com a classe destino.
- Recurso: classe origem tem dependência de recurso com a classe destino.
- Responsabilidade: registra a participação, responsabilidade e ação de pessoas sobre artefatos.
- Representação: captura a representação ou modelagem dos requisitos em outras linguagens.
- Alocado: classe origem está relacionada à classe destino, que representa um subsistema.
- Agregação: indica “composição” de elementos.

## 3. Matriz com Requisitos Funcionais
| ID | Requisito | Cenários | Léxicos | Casos de Uso | Histórias de Usuário | Categoria | Elo |
| -- | --------- | -------- | ------- | ------------ | -------------------- | --------- | --- |
| RF01 | O usuário deve ser capaz de fazer o login através do gov.br        | [C01](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/cenarios/#c01-login-unico)         |         |              | [US01](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/agil/historias-usuario/US1/)                     |           |     |
| RF02 |  O usuário deve ser capaz de visualizar o cronograma da prova        | [C03](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/cenarios/#c03-visualizar-cronograma)         |         |              | [US03](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/agil/historias-usuario/US3/)                     |           |     |
| RF03 |  O usuário deve ser capaz de acompanhar sua inscrição        |  [C02](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/cenarios/#c02-conferir-inscricao)        |         |              |   [US04](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/agil/historias-usuario/US4/)                   |           |     |
| RF04 | O usuário deve ser capaz de acompanhar pedido de isenção de taxa de inscrição  |          |         |              | [US05](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/agil/historias-usuario/US5/)                     |           |     |
| RF05 | O usuário deve ser capaz de ter acesso aos avisos e às notícias        | [C04](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/cenarios/#c04-definir-alertas)         |         |              | [US06](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/agil/historias-usuario/US6/)                     |           |     |
| RF06 | O usuário deve ser capaz de verificar as perguntas frequentes e as orientações       |          |         |              | [US07](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/agil/historias-usuario/US7/)                      |           |     |
| RF07 | O usuário deve ser capaz de visualizar/baixar/imprimir sua nota de provas do Enem     | [C06](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/cenarios/#c06-acessar-notas-e-resultado)         |         |              | [US08](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/agil/historias-usuario/US8/)                     |           |     |
| RF08 | O usuário deve ser capaz de visualizar/baixar/imprimir sua vista pedagógica das provas do Enem   |          |         |              | [US09](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/agil/historias-usuario/US9/)                      |           |     |
| RF09 | O usuário deve ser capaz de visualizar/baixar/imprimir sua redação das provas do Enem        |          |         |              | [US10](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/agil/historias-usuario/US10/)                     |           |     |
| RF10 | O usuário deve ser capaz de visualizar/baixar/imprimir seu gabarito das provas do Enem        | [C05](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/cenarios/#c05-consultar-o-proprio-gabarito-de-provas-e-espelho-da-redacao)         |         |              | [US11](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/agil/historias-usuario/US11/)                      |           |     |
| RF11 | O usuário deve ser capaz de visualizar/baixar/imprimir as provas do Enem    |  [C08](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/cenarios/#c08-visualizar-provas-anteriores-do-enem)        |         |              | [US12](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/agil/historias-usuario/US12/)                     |           |     |
| RF12 | O usuário deve ser capaz de visualizar/baixar/imprimir simulados do Enem     | [C07](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/cenarios/#c07-acessar-simulados-do-enem)         |         |              | [US13](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/agil/historias-usuario/US13/)                     |           |     |
| RF13 | O usuário deve ser capaz de visualizar métricas de desempenho dos participantes   |          |         |              | [US14](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/agil/historias-usuario/US14/)                     |           |     |
| RF14 | O usuário deve ser capaz de consultar escopo de conteúdo do exame   |          |         |              |                      |           |     |
| RF15 |         |          |         |              |                      |           |     |


## 4. Matriz com Requisitos Não-Funcionais

| ID    | Requisito                                                                                                                        | Léxicos                                                                                                                                                                                                            | NFR | Especificação suplementar |
| ----- | -------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------- | ---------- |
| RNF01 | O aplicativo deve ter compatibilidade com qualquer sistema operacional                                                           | [L01](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/lexicos/) | [Portabilidade](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/nfrframework/)        |
| RNF02 | O aplicativo deve recusar o acesso de pessoas não autorizadas                                                                    | [L01](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/lexicos/) | [Confiabilidade](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/nfrframework/)        |
| RNF03 | O aplicativo deve proteger os dados dos usuários                                                                                 | - | [Confiabilidade](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/nfrframework/)        |
| RNF04 | O aplicativo deve ser acessível para Pessoas com Deficiência (PcD)                                                               | - | [Acessibilidade](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/nfrframework/)        |
| RNF05 | O aplicativo deve consegui suportar uma grande quantidade de acessos simultâneos                                                 | - | [Navegabilidade](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/nfrframework/)        |
| RNF06 | O aplicativo deve ter baixo tempo de espera mesmo durante períodos de grande fluxo                                               | - | [Navegabilidade](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/nfrframework/)        |
| RNF07 | O aplicativo deve ter uma interface amigável na qual com no máximo 3 cliques o usuário consiga realizar a ação desejada | - | [Intuitividade](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/nfrframework/)      |
| RNF08 | O aplicativo deve deve se adaptar bem a dispositivos mobile                                                                      | - | [Portabilidade](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/nfrframework/)        |
| RNF10 | O aplicativo deve possuir funcionalidades em modo offline | - | [Navegabilidade](https://requisitos-de-software.github.io/2021.2-ENEM/modelagem/nfrframework/)       |

## 5. Bibliografia


## 6. Histórico de versão
| Versão | Data       | Descrição                                                                      | Autor   |
| ------ | ---------- | ------------------------------------------------------------------------------ | ------- |
| 1.0    | 30/03/2022 | Criação do documento                                                           | Antonio |
| 1.1    | 01/04/2022 | Adicionando introdução                                                         | Vitor |
