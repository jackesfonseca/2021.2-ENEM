# Matriz Backward-From

## 1. Introdução

A rastreabilidade de requisitos acontece quando os requisitos são claramente ligados às suas fontes e aos artefatos criados durante o ciclo de vida de desenvolvimento do sistema. Assim, podendo tomar ambas direções forward (para frente) e backward (para trás).

Será apresentado nessa página a matriz de rastreabilidade backward-from que liga os requisitos às suas fontes.

A tabela que representa a rastreabilidade contém cinco colunas, ID que lista os códigos dos requisitos, sendo F para Requisitos Funcionais, e NF para Requisitos Não-Funcionais, a coluna de requisito, onde estão os requisitos do produto, a coluna de origem, que contém as técnicas que deram origem aquele requisito, nesta são atribuídos códigos que correspondem a cada categoria, estas representações são descritas na <a href="#legenda">Figura 01</a>, a coluna de categoria, que explicita as categorias pertencentes daquele requisito e estão descritas na  <a href="#descricao">Tabela 01</a>, e por fim a coluna de elo onde é apresentado os relacionamentos da rastreabilidade .

<a id="legenda"></a>
<center>
  <br><figcaption class="center">Figura 01: Legenda de rastreabilidade</figcaption>
  <img src="https://user-images.githubusercontent.com/53023400/154858872-f7f7c057-a096-4e0c-9a46-62d429b5447b.png" class="center">
  <figcaption class="center">Fonte: autoria própria</figcaption>
</center>
<br>
<div class="divisoria"></div>
<a id="descricao"></a>
<center>
    <br><figcaption class="center">Tabela 01: Descrição de categoria</figcaption>
</center>

|Categoria|Descrição|
|--|--|
|Ambiental|informações oriundas do contexto no qual a organização está inserida|
|Desenvolvimento|informações associadas aos diversos artefatos gerados ao longo do processo de desenvolvimento (artefatos de requisitos, diagramas, códigos, casos de teste e outros)|
|Gerencial|informações que auxiliam a gerência do projeto|
|Organizacional|informações pertencentes à organização (missão, objetivos e estratégias)|

<center>
    <figcaption class="center">Fonte: autoria própria</figcaption>
</center>

## 2. Requisitos Funcionais

| ID   | Requisito                                                                                      | Técnica                                                                                                                                                                                                                                                     | Categoria | Elo |
| ---- | ---------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------- | ----- |
| RF01 | O usuário deve ser capaz de fazer o login através do gov.br                                    | [BF](../elicitacao/tecnicas-elicitacao/brainstorming.md), [IF](../elicitacao/tecnicas-elicitacao/introspeccao.md), [OF](../elicitacao/tecnicas-elicitacao/observacao.md)                                                                                                                              | Desenvolvimento, Organizacional | Elo |
| RF02 | O usuário deve ser capaz de visualizar o cronograma da prova                                   | [BF](../elicitacao/tecnicas-elicitacao/brainstorming.md), [IF](../elicitacao/tecnicas-elicitacao/introspeccao.md), [OF](../elicitacao/tecnicas-elicitacao/observacao.md), [SF](../elicitacao/tecnicas-elicitacao/storyboard.md), [QF](../elicitacao/tecnicas-elicitacao/questionario.md)                                          | Desenvolvimento, Gerencial | Elo |
| RF03 | O usuário deve ser capaz de acompanhar sua inscrição                                           | [BF](../elicitacao/tecnicas-elicitacao/brainstorming.md), [IF](../elicitacao/tecnicas-elicitacao/introspeccao.md), [OF](../elicitacao/tecnicas-elicitacao/observacao.md), [QF](../elicitacao/tecnicas-elicitacao/questionario.md)                                                                                   | Desenvolvimento, Gerencial, Organizacional | Elo |
| RF04 | O usuário deve ser capaz de acompanhar pedido de isenção de taxa de inscrição                  | [BF](../elicitacao/tecnicas-elicitacao/brainstorming.md), [IF](../elicitacao/tecnicas-elicitacao/introspeccao.md), [QF](../elicitacao/tecnicas-elicitacao/questionario.md)                                                                                                                            | Desenvolvimento, Gerencial, Organizacional | Elo |
| RF05 | O usuário deve ser capaz de ter acesso aos avisos e às notícias                                | [BF](../elicitacao/tecnicas-elicitacao/brainstorming.md), [IF](../elicitacao/tecnicas-elicitacao/introspeccao.md), [OF](../elicitacao/tecnicas-elicitacao/observacao.md)                                                                                                                              | Gerencial, Organizacional | Elo |
| RF06 | O usuário deve ser capaz de verificar as perguntas frequentes e as orientações                 | [BF](../elicitacao/tecnicas-elicitacao/brainstorming.md)                                                                                                                                                                                                                  | Ambiental, Gerencial, Organizacional | Elo |
| RF07 | O usuário deve ser capaz de visualizar/baixar/imprimir sua nota de provas do Enem              | [BF](../elicitacao/tecnicas-elicitacao/brainstorming.md), [EF](../elicitacao/tecnicas-elicitacao/entrevista.md), [IF](../elicitacao/tecnicas-elicitacao/introspeccao.md), [OF](../elicitacao/tecnicas-elicitacao/observacao.md), [SF](../elicitacao/tecnicas-elicitacao/storyboard.md), [QF](../elicitacao/tecnicas-elicitacao/questionario.md) | Desenvolvimento, Organizacional | Elo |
| RF08 | O usuário deve ser capaz de visualizar/baixar/imprimir sua vista pedagógica das provas do Enem | [BF](../elicitacao/tecnicas-elicitacao/brainstorming.md), [IF](../elicitacao/tecnicas-elicitacao/introspeccao.md)                                                                                                                                                                       | Desenvolvimento, Organizacional | Elo |
| RF09 | O usuário deve ser capaz de visualizar/baixar/imprimir sua redação das provas do Enem          | [BF](../elicitacao/tecnicas-elicitacao/brainstorming.md), [IF](../elicitacao/tecnicas-elicitacao/introspeccao.md), [QF](../elicitacao/tecnicas-elicitacao/questionario.md)                                                                                                                            | Desenvolvimento, Organizacional | Elo |
| RF10 | O usuário deve ser capaz de visualizar/baixar/imprimir seu gabarito das provas do Enem         | [BF](../elicitacao/tecnicas-elicitacao/brainstorming.md), [QF](../elicitacao/tecnicas-elicitacao/questionario.md)                                                                                                                                                                       | Desenvolvimento, Organizacional | Elo |
| RF11 | O usuário deve ser capaz de visualizar/baixar/imprimir as provas do Enem                       | [BF](../elicitacao/tecnicas-elicitacao/brainstorming.md), [SF](../elicitacao/tecnicas-elicitacao/storyboard.md), [QF](../elicitacao/tecnicas-elicitacao/questionario.md)                                                                                                                              | Desenvolvimento, Organizacional | Elo |
| RF12 | O usuário deve ser capaz de visualizar/baixar/imprimir simulados do Enem                       | [SF](../elicitacao/tecnicas-elicitacao/storyboard.md)                                                                                                                                                                                                                     | Desenvolvimento, Organizacional | Elo |
| RF13 | O usuário deve ser capaz de visualizar métricas de desempenho dos participantes                | [SF](../elicitacao/tecnicas-elicitacao/storyboard.md)                                                                                                                                                                                                                     | Desenvolvimento, Gerencial, Organizacional | Elo |
| RF14 | O usuário deve ser capaz de consultar escopo de conteúdo do exame                              | [SF](../elicitacao/tecnicas-elicitacao/storyboard.md)                                                                                                                                                                                                                     | Gerencial, Organizacional | Elo |

## 3. Requisitos Não - Funcionais

| ID    | Requisito | Técnica | Categoria |  Elo |
|-------|-----------|---------|-----------|------|
| RNF01 | O aplicativo deve ter compatibilidade com qualquer sistema operacional | [BF](../elicitacao/tecnicas-elicitacao/brainstorming.md), [IF](../elicitacao/tecnicas-elicitacao/introspeccao.md) | Gerencial |  Elo |
| RNF02 | O aplicativo deve recusar o acesso de pessoas não autorizadas | [BF](../elicitacao/tecnicas-elicitacao/brainstorming.md), [IF](../elicitacao/tecnicas-elicitacao/introspeccao.md) | Gerencial |  Elo |
| RNF03 | O aplicativo deve proteger os dados dos usuários                                                                                 | [BF](../elicitacao/tecnicas-elicitacao/brainstorming.md), [IF](../elicitacao/tecnicas-elicitacao/introspeccao.md), [QF](../elicitacao/tecnicas-elicitacao/questionario.md)                                                                                                 | Ambiental |  Elo |
| RNF04 | O aplicativo deve ser acessível para Pessoas com Deficiência (PcD)                                                               | [BF](../elicitacao/tecnicas-elicitacao/brainstorming.md), [IF](../elicitacao/tecnicas-elicitacao/introspeccao.md), [QF](../elicitacao/tecnicas-elicitacao/questionario.md)                                                                                                 | Desenvolvimento, Gerencial |  Elo |
| RNF05 | O aplicativo deve consegui suportar uma grande quantidade de acessos simultâneos                                                 | [BF](../elicitacao/tecnicas-elicitacao/brainstorming.md), [EF](tecnicas-elicitacao/entrevista.md), [IF](../elicitacao/tecnicas-elicitacao/introspeccao.md), [OF](../elicitacao/tecnicas-elicitacao/observacao.md), [QF](../elicitacao/tecnicas-elicitacao/questionario.md) | Desenvolvimento, Gerencial |  Elo |
| RNF06 | O aplicativo deve ter baixo tempo de espera mesmo durante períodos de grande fluxo                                               | [BF](../elicitacao/tecnicas-elicitacao/brainstorming.md), [IF](../elicitacao/tecnicas-elicitacao/introspeccao.md)                                                                                                                                                          | Desenvolvimento, Gerencial |  Elo |
| RNF07 | O aplicativo deve deve ter ter uma interface amigável na qual com no máximo 3 cliques o usuário consiga realizar a ação desejada | [BF](../elicitacao/tecnicas-elicitacao/brainstorming.md), [QF](../elicitacao/tecnicas-elicitacao/questionario.md), [SF](../elicitacao/tecnicas-elicitacao/storyboard.md)                                                                                                   | Desenvolvimento, Organizacional |  Elo |
| RNF08 | O aplicativo deve deve se adaptar bem a dispositivos mobile                                                                      | [BF](../elicitacao/tecnicas-elicitacao/brainstorming.md)                                                                                                                                                                                                                   | Desenvolvimento, Organizacional |  Elo |
| RNF10 | O aplicativo deve possuir funcionalidades em modo offline                                                                        | [SF](../elicitacao/tecnicas-elicitacao/storyboard.md)                                                                                                                                                                                                                      | Desenvolvimento |  Elo |


## 4. Bibliografia <a id="Bibliografia"></a>

Davis, A. M., **Software Requirements: Objects, Functions and States**. Englewood Cliffs, New Jersey: Prentice Hall. 1993.  

## 5. Versionamento

| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 01/04/2022 | Criação do página | Pedro Henrique |
| 1.1 | 01/04/2022 | Elaboração do documento | Pedro Henrique |
