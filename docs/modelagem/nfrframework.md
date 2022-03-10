## 1. Introdução

O NFR Framework é uma abordagem para representar e analisar Requisitos Não-Funcionais.
Seu objetivo é ajudar desenvolvedores na implementação de soluções personalizadas, levando
em consideração as características do domínio e do sistema em questão. Tais características
incluem Requisitos Não-funcionais, Requisitos funcionais, prioridades e carga de
trabalho. Esses fatores determinam a escolha de alternativas de desenvolvimento para um
determinado sistema (CHUNG et al., 2000).

## 2. Softgoals
 - Softgoals NFR
 - Softgoals de Operacionalização
 - Softgoals de Afirmação
## 3. Decomposições
 - Decomposição de Softgoal NFR
 - Decomposição de Operacionalização
 - Decomposição de Afirmação (Claims)
 - Priorização


## 4. Legenda
### Softgoals
<img width="500" alt="nfr_guide" src="https://user-images.githubusercontent.com/51385738/157487932-c710441a-78a3-4dbb-ad17-9baf2fa7d2ea.png">
<center>
<figcaption> Figura 01 - Legendas Softgoals </figcaption>
</center>

### Interdependecy
<img width="500" alt="nfr_line_guide" src="https://user-images.githubusercontent.com/51385738/157487958-0f254ac9-1b3a-4ba8-b591-651f8ce27f60.png">
<center>
<figcaption> Figura 02 - Legendas Interdependecy </a></figcaption>
</center>

## 5. Requisitos não funcionais

|  ID  |  Requisito  |  Técnica  |   Priorização  |
|------|-------------|-----------|----------------|
| RF01 |  O usuário deve ser capaz de fazer o login através do gov.br | [BF](../tecnicas-elicitacao/brainstorming.md), [IF](../tecnicas-elicitacao/introspeccao.md), [OF](../tecnicas-elicitacao/observacao.md)  | MUST  |
| RF02 |  O usuário deve ser capaz de visualizar o cronograma da prova | [BF](../tecnicas-elicitacao/brainstorming.md), [IF](../tecnicas-elicitacao/introspeccao.md), [OF](../tecnicas-elicitacao/observacao.md), [SF](../tecnicas-elicitacao/storyboard.md), [QF](../tecnicas-elicitacao/questionario.md)  | SHOULD  |
| RF03 |  O usuário deve ser capaz de acompanhar sua inscrição | [BF](../tecnicas-elicitacao/brainstorming.md), [IF](../tecnicas-elicitacao/introspeccao.md), [OF](../tecnicas-elicitacao/observacao.md), [QF](../tecnicas-elicitacao/questionario.md)  | MUST  |
| RF04 |  O usuário deve ser capaz de acompanhar pedido de isenção de taxa de inscrição| [BF](../tecnicas-elicitacao/brainstorming.md), [IF](../tecnicas-elicitacao/introspeccao.md), [QF](../tecnicas-elicitacao/questionario.md)  | SHOULD  |
| RF05 |  O usuário deve ser capaz de ter acesso aos avisos e às notícias | [BF](tecnicas-elicitacao/brainstorming.md), [IF](../tecnicas-elicitacao/introspeccao.md), [OF](../tecnicas-elicitacao/observacao.md)  | COULD  |
| RF06 |  O usuário deve ser capaz de verificar as perguntas frequentes e as orientações | [BF](../tecnicas-elicitacao/brainstorming.md) |  SHOULD |
| RF07 |  O usuário deve ser capaz de visualizar/baixar/imprimir sua nota de provas do Enem | [BF](../tecnicas-elicitacao/brainstorming.md), [EF](../tecnicas-elicitacao/entrevista.md), [IF](../tecnicas-elicitacao/introspeccao.md), [OF](../tecnicas-elicitacao/observacao.md), [SF](../tecnicas-elicitacao/storyboard.md), [QF](../tecnicas-elicitacao/questionario.md)  | MUST  |
| RF08 |  O usuário deve ser capaz de visualizar/baixar/imprimir sua vista pedagógica das provas do Enem | [BF](../tecnicas-elicitacao/brainstorming.md), [IF](../tecnicas-elicitacao/introspeccao.md)  | MUST  |
| RF09 |  O usuário deve ser capaz de visualizar/baixar/imprimir sua redação das provas do Enem | [BF](../tecnicas-elicitacao/brainstorming.md), [IF](../tecnicas-elicitacao/introspeccao.md), [QF](../tecnicas-elicitacao/questionario.md)  | MUST  |
| RF10 |  O usuário deve ser capaz de visualizar/baixar/imprimir seu gabarito das provas do Enem | [BF](../tecnicas-elicitacao/brainstorming.md), [QF](../tecnicas-elicitacao/questionario.md)  | SHOULD  |
| RF11 |  O usuário deve ser capaz de visualizar/baixar/imprimir as provas do Enem | [BF](../tecnicas-elicitacao/brainstorming.md), [SF](../tecnicas-elicitacao/storyboard.md), [QF](../tecnicas-elicitacao/questionario.md)  | COULD  |
| RF12 |  O usuário deve ser capaz de visualizar/baixar/imprimir simulados do Enem | [SF](../tecnicas-elicitacao/storyboard.md)  | WOULD  |
| RF13 |  O usuário deve ser capaz de visualizar métricas de desempenho dos participantes  | [SF](../tecnicas-elicitacao/storyboard.md)  | WOULD  |
| RF14 |  O usuário deve ser capaz de consultar escopo de conteúdo do exame  | [SF](../tecnicas-elicitacao/storyboard.md)  | COULD  |

## 6. Diagrama


### 6.1 Diagrama Geral sem propagação
![NFR_semPropagacao](https://user-images.githubusercontent.com/53023400/157520738-48cdb14e-9fb7-4a80-9fd5-e288c546089a.jpg)
<center>
<figcaption> Figura 03 - NFR Framework Geral sem propagação </figcaption>
</center>

### 6.2 Diagrama Geral com propagação
![NFR_comPropagacao](https://user-images.githubusercontent.com/53023400/157521127-c901b744-d8e8-4aa7-8c8b-1d4d34d0a1e3.jpg)
<center>
<figcaption> Figura 04 - NFR Framework Geral com propagação </figcaption>
</center>

## 7. Bibliografia
[1] CHUNG, L.; NIXON, B. A.; YU, E.; MYLOPOULOS, J. Non-functional requirements in software engineering. Springer Science & Business Media: [s.n.], 2000. v. 5. Disponível aqui. Acessado em 09/03/22.

[2] DA SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. 2019. Dissertação (Mestrado em Ciência da Computação) - Universidade Federal de Pernambuco, Recife, 2019.


## 8. Histórico de versão
| Versão | Data | Descrição | Autor |
| :--: | :--: | :--: | :--: |
| 1.0 | 09/03 | Criação do documento | Eduardo Gurgel |
| 2.0 | 09/03 | Adição do documento de usabilidade | Eduardo Gurgel, Jackes Fonseca |

