## Metodologia

O objetivo desse documento é reunir todos os requistos que foram elicitados para o projeto a partir das técnicas. Na tabela foram identificados os metodos que originaram os requisitos, esses metodos são listados na coluna Técnica, e identificados por um código como demonstrado na Figura 1.

<center>
  <figcaption class="center">Figura 1: Legenda de rastreabilidade</figcaption>
  <img src="https://user-images.githubusercontent.com/53023400/154858872-f7f7c057-a096-4e0c-9a46-62d429b5447b.png" class="center">
  <figcaption class="center">Fonte: autoria própria</figcaption>
</center>


## Requisitos funcionais

|  ID  |  Requisito  |  Técnica  |   Priorização  |
|------|-------------|-----------|----------------|
| RF01 |  O usuário deve ser capaz de fazer o login através do gov.br | BF, IF, OF  | MUST  |
| RF02 |  O usuário deve ser capaz de visualizar o cronograma da prova | BF, IF, OF, SF, QF  | SHOULD  |
| RF03 |  O usuário deve ser capaz de acompanhar sua inscrição | BF, IF, OF, QF  | MUST  |
| RF04 |  O usuário deve ser capaz de acompanhar pedido de isenção de taxa de inscrição| BF, IF, QF  | SHOULD  |
| RF05 |  O usuário deve ser capaz de ter acesso aos avisos e às notícias | BF, IF, OF  | COULD  |
| RF06 |  O usuário deve ser capaz de verificar as perguntas frequentes e as orientações | BF  |  SHOULD |
| RF07 |  O usuário deve ser capaz de visualizar/baixar/imprimir sua nota de provas do Enem | BF, EF, IF, OF, SF, QF  | MUST  |
| RF08 |  O usuário deve ser capaz de visualizar/baixar/imprimir sua vista pedagógica das provas do Enem | BF, IF  | MUST  |
| RF09 |  O usuário deve ser capaz de visualizar/baixar/imprimir sua redação das provas do Enem | BF, IF, QF  | MUST  |
| RF10 |  O usuário deve ser capaz de visualizar/baixar/imprimir seu gabarito das provas do Enem | BF, QF  | SHOULD  |
| RF11 |  O usuário deve ser capaz de visualizar/baixar/imprimir as provas do Enem | BF, SF, QF  | COULD  |
| RF12 |  O usuário deve ser capaz de visualizar/baixar/imprimir simulados do Enem | SF  | WOULD  |
| RF13 |  O usuário deve ser capaz de visualizar métricas de desempenho dos participantes  | SF  | WOULD  |
| RF14 |  O usuário deve ser capaz de consultar escopo de conteúdo do exame  | SF  | COULD  |


## Requisitos não funcionais

|  ID  |  Requisito  |  Técnica  |   Priorização  |
|------|-------------|-----------|----------------|
| RNF01 |  O aplicativo deve ter compatibilidade com qualquer sistema operacional | BF, IF  | MUST  |
| RNF02 |  O aplicativo deve recusar o acesso de pessoas não autorizadas | BF, IF  | MUST  |
| RNF03 |  O aplicativo deve proteger os dados dos usuários | BF, IF, QF  | MUST  |
| RNF04 |  O aplicativo deve ser acessível para Pessoas com Deficiência (PcD) | BF, IF, QF  | MUST  |
| RNF05 |  O aplicativo deve consegui suportar uma grande quantidade de acessos simultâneos | BF, EF, IF, OF, QF  | MUST  |
| RNF06 |  O aplicativo deve ter baixo tempo de espera mesmo durante períodos de grande fluxo | BF, IF  |   |
| RNF07 |  O aplicativo deve deve ter ter uma interface amigável na qual com no máximo 3 cliques o usuário consiga realizar a ação desejada | BF, QF, SF  | SHOULD |
| RNF08 |  O aplicativo deve deve se adaptar bem a dispositivos mobile | BF  | MUST  |
| RNF10 |  O aplicativo deve possuir funcionalidades em modo offline | SF  | COULD  |

## Versionamento

| Versão | Data | Descrição | Autor |
|--------|------|-----------|-------|
| 1.0    | 18/02/2022 | Criação do Documento | Carlos rafael |
| 1.1    | 20/02/2022 | Adicionando resultados | Jackes Fonseca |
