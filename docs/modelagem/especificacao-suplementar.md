# Especificação suplementar

## 1. Introdução
A especificação suplementar é um documento com o objetivo de explicitar os requisitos do aplicativo, tendo em vista os requisitos de usabilidade, confiabilidade, suportatibilidade e desempenho, além de outros requisitos, como: sistemas operacionais e ambientes, requisitos de compatibilidade e restrições de design.

### 1.1 Finalidade
A finalidade é  especificar os requisitos não-funcionais do aplicativo ENEM, descrevendo seu comportamento a partir do modelo de casos de usos e com isso capturando um conjunto completo de requisitos do sistema.

## 2. Escopo
Com o aplicativo Enem, é possível ver notícias sobre o exame, conferir informações de situação da inscrição, ver o cronograma de provas com datas e locais e ter acesso ao cartão de confirmação, trazer o gabarito das provas, o resultado individual após o exame ser realizado e o espelho da redação.

## 3. Requisitos Não-Funcionais

|  ID  |  Requisito  |  Técnica  |   Priorização  |
|------|-------------|-----------|----------------|
| RF01 |  O usuário deve ser capaz de fazer o login através do gov.br | [BF](../elicitacao/tecnicas-elicitacao/brainstorming.md), [IF](../elicitacao/tecnicas-elicitacao/introspeccao.md), [OF](../elicitacao/tecnicas-elicitacao/observacao.md)  | MUST  |
| RF02 |  O usuário deve ser capaz de visualizar o cronograma da prova | [BF](../elicitacao/tecnicas-elicitacao/brainstorming.md), [IF](../elicitacao/tecnicas-elicitacao/introspeccao.md), [OF](../elicitacao/tecnicas-elicitacao/observacao.md), [SF](../elicitacao/tecnicas-elicitacao/storyboard.md), [QF](../elicitacao/tecnicas-elicitacao/questionario.md)  | SHOULD  |
| RF03 |  O usuário deve ser capaz de acompanhar sua inscrição | [BF](../elicitacao/tecnicas-elicitacao/brainstorming.md), [IF](../elicitacao/tecnicas-elicitacao/introspeccao.md), [OF](../elicitacao/tecnicas-elicitacao/observacao.md), [QF](../elicitacao/tecnicas-elicitacao/questionario.md)  | MUST  |
| RF04 |  O usuário deve ser capaz de acompanhar pedido de isenção de taxa de inscrição| [BF](../elicitacao/tecnicas-elicitacao/brainstorming.md), [IF](../elicitacao/tecnicas-elicitacao/introspeccao.md), [QF](../elicitacao/tecnicas-elicitacao/questionario.md)  | SHOULD  |
| RF05 |  O usuário deve ser capaz de ter acesso aos avisos e às notícias | [BF](elicitacao/tecnicas-elicitacao/brainstorming.md), [IF](../tecnicas-elicitacao/introspeccao.md), [OF](../elicitacao/tecnicas-elicitacao/observacao.md)  | COULD  |
| RF06 |  O usuário deve ser capaz de verificar as perguntas frequentes e as orientações | [BF](../elicitacao/tecnicas-elicitacao/brainstorming.md) |  SHOULD |
| RF07 |  O usuário deve ser capaz de visualizar/baixar/imprimir sua nota de provas do Enem | [BF](../elicitacao/tecnicas-elicitacao/brainstorming.md), [EF](../elicitacao/tecnicas-elicitacao/entrevista.md), [IF](../elicitacao/tecnicas-elicitacao/introspeccao.md), [OF](../elicitacao/tecnicas-elicitacao/observacao.md), [SF](../elicitacao/tecnicas-elicitacao/storyboard.md), [QF](../elicitacao/tecnicas-elicitacao/questionario.md)  | MUST  |
| RF08 |  O usuário deve ser capaz de visualizar/baixar/imprimir sua vista pedagógica das provas do Enem | [BF](../elicitacao/tecnicas-elicitacao/brainstorming.md), [IF](../elicitacao/tecnicas-elicitacao/introspeccao.md)  | MUST  |
| RF09 |  O usuário deve ser capaz de visualizar/baixar/imprimir sua redação das provas do Enem | [BF](../elicitacao/tecnicas-elicitacao/brainstorming.md), [IF](../elicitacao/tecnicas-elicitacao/introspeccao.md), [QF](../elicitacao/tecnicas-elicitacao/questionario.md)  | MUST  |
| RF10 |  O usuário deve ser capaz de visualizar/baixar/imprimir seu gabarito das provas do Enem | [BF](../elicitacao/tecnicas-elicitacao/brainstorming.md), [QF](../elicitacao/tecnicas-elicitacao/questionario.md)  | SHOULD  |
| RF11 |  O usuário deve ser capaz de visualizar/baixar/imprimir as provas do Enem | [BF](../elicitacao/tecnicas-elicitacao/brainstorming.md), [SF](../elicitacao/tecnicas-elicitacao/storyboard.md), [QF](../elicitacao/tecnicas-elicitacao/questionario.md)  | COULD  |
| RF12 |  O usuário deve ser capaz de visualizar/baixar/imprimir simulados do Enem | [SF](../elicitacao/tecnicas-elicitacao/storyboard.md)  | WOULD  |
| RF13 |  O usuário deve ser capaz de visualizar métricas de desempenho dos participantes  | [SF](../elicitacao/tecnicas-elicitacao/storyboard.md)  | WOULD  |
| RF14 |  O usuário deve ser capaz de consultar escopo de conteúdo do exame  | [SF](../elicitacao/tecnicas-elicitacao/storyboard.md)  | COULD  |

### 3.1 Usabilidade
A interface deve ser intuitiva apresentando o conteúdo e os recursos de uma forma simples, direta e fornecer o mínimo de distração. Sendo assim, o usuário deve consegui realizar a ação desejada com o mínimo de esforço possível.

### 3.2 Confiabilidade

<h4 class="header-light">3.2.1 Disponibilidade</h4>
O serviço tem que está diponível 24/7 tendo que suportar uma grande quantidade de acesso simultâneos de usuários principalmente após a divulgação do local da prova e ao ser liberado a nota das provas.

<h4 class="header-light">3.2.2 Privacidade dos Dados</h4>
O aplicativo tem que seguir a Lei Geral de Proteção de Dados (LGPD).

### 3.3 Desempenho
A aplicação tem que ter um tamanho e um desempenho compativo com dispositivos mais fracos, visto que ENEM é um prova que engloba jovens de diferentes classes sociais.

### 3.4 Suportabilidade
O aplicativo deve ter compatibilidade com qualquer sistema operacional suportando a versão do Android 4.4 ou superior ou a versão do IOS 10.0 ou superior.

### 3.5 Requisito Físico
Os dispositivos deverão ter acesso a internet para acessar o aplicativo.

## 4. Bibliografia
<p>KADER, Saleh; Especificação Suplementar; Disponível em: <https://requisitos-habitica.netlify.com/EspecificacaoSuplementar>. Acesso em: 04/03/2022.</p>
<p>Play Store, Inep - ENEM, Disponível em: <https://play.google.com/store/apps/details?id=br.gov.inep.inepenem&hl=pt_BR&gl=US>. Acesso em: 04/03/2022.</p>
<p>Apple Store, Inep - ENEM, Disponível em: <https://apps.apple.com/br/app/enem-inep/id1114622953>. Acesso em: 04/03/2022.</p>

## 5. Versionamento

| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 04/03/2022 | Criação da página | Pedro Henrique e Vitor Diniz |
| 1.1 | 04/03/2022  | Elaboração do documento | Pedro Henrique e Vitor Diniz |
| 1.2 | 04/03/2022  | Revisando e padronizando índice do documento | Pedro Henrique e Vitor Diniz |
