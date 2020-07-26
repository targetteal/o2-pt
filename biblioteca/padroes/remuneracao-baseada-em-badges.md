# Remuneração Baseada em Badges

## Contexto

Uma [Organizacao][organizacao] de porte médio ou grande que faz uso de uma estrutura baseada em [Papéis][papeis] e que busca formas mais claras e justas de reconhecer financeiramente as habilidade individuais de seus [Parceiros][parceiros].

## Forças

Na maior parte das organizações, não há clareza sobre como decisões de remuneração são tomadas ou que critérios são considerados. As habilidades e talentos individuais que os [Parceiros][parceiros] usam de forma recorrente no seu grupo de trabalho precisam ser reconhecidas e o mecanismo para que isso aconteça precisa ser o mais claro e objetivo possível.

## Problema

Não existe um sistema de remuneração transparente, justo e com poder de decisão descentralizado na [Organização][organizacao]. Pessoas com habilidades e talentos diferentes precisam ser recompensadas de acordo, sem relacionarmos diretamente com a estrutura de [Papéis][papeis], pois ela muda com muita frequência.

## Solução

A solução aqui proposta define como a [Organização][organizacao] cria e modifica um sistema de remuneração baseado em uma biblioteca de badges.

O primeiro elemento desse padrão é a criação de um papel responsável pela biblioteca de badges.

> **Papel**: Bibliotecário de badges
>
> **Propósito**: _Badges que representam condecorações claras e úteis para a organização_.
>
> **Responsabilidades**:
>
> * Manter e publicar a biblioteca oficial de Badges
> * Revisar e avaliar adições ou propostas de mudanças à biblioteca de Badges quando propostas completas de Badges forem enviadas por quaisquer Papéis ou pessoas da organização;
> * Auxiliar outros Papéis e pessoas na construção de propostas de Badges, mediante solicitação e sobre a confirmação de que um Guia acredita que a Badge representa uma consideração significativa na escolha da atribuição.

O segundo passo é adicionar uma restrição que deixa claro o processo que as pessoas precisam seguir para propor novas badges ou fazer alterações/exclusões em badges já existentes.

> **Restrição**: Definir Badges.
>
> A Biblioteca oficial de Badges da organização lista aquelas disponíveis para que as pessoas ganhem um reconhecimento em habilidades, talentos, capacidades e conquistas. Cada definição de Badge deve conter uma descrição da habilidade, talento, capacidade ou conquista que a Badge representa, e pode, opcionalmente, incluir um processo ou outro mecanismo para as pessoas adquirirem ou perderem a Badge.
>
> Ninguém poderá adicionar, modificar ou remover Badges da Biblioteca, a não ser que cada Bibliotecário de Badges confirme que ele/ela não vê nenhuma Objeção à mudança, ou falhe em responder com uma Objeção dentro do prazo de uma semana a partir da mudança proposta. Em qualquer caso, nenhuma Badge na Biblioteca poderá ser modificada ou removida enquanto outro processo ou decisão ativa depender da Badge \(embora ela possa ser marcada como “inativa” e tornada indisponível para novo uso, e como alternativa uma versão atualizada pode ser adicionada para novo uso\).

Em seguida é necessário deixar claro qual o mecanismo para que se possa ganhar ou perder uma badge, faremos isso através de outra restrição.

> **Restrição**: Adquirir & Perder Badges.
>
> Uma pessoa receberá uma Badge quando pelo menos duas pessoas que já possuírem a Badge afirmarem que eles/elas claramente e repetidamente viram o candidato demonstrar a habilidade ou capacidade descrita pela Badge, citando exemplos. No entanto, se não houverem pessoas suficientes que de fato possuam a Badge ou tenham trabalhado com o candidato para availiá-lo, então o\(s\) Inicializador\(es\) de Badges poderão então conceder a Badge usando qualquer evidência que bem entenderem, enquanto que a maioria dos Inicializador\(es\) de Badges defenderem a concessão e nenhum deles ativamente for contra. Se o candidato para a concessão for também um Inicializador de Badges, ele/ela não deverá contar para o propósito de avaliar a sua própria nomeação de Badge.
>
> Se nenhum mecanismo for especificado juntamente com a definição da Badge de como alguém pode perdê-la, então, como um mecanismo padrão, o seguinte se aplica:
>
> A Badge concedida irá automaticamente expirar dois anos após a concessão, a não ser que seja renovada através do mesmo mecanismo exigido para a concessão inicial. Além disso, a Badge poderá ser revogada antes por quaisquer duas pessoas que já possuem a Badge, que pediram por uma requalificação na qual a pessoa falhou em prontamente requalificar-se para a Badge, usando qualquer mecanismo exigido pela concessão inicial.

Quando uma nova badge é criada ou até mesmo no início desse padrão é natural que algumas badges não tenham pessoas especializadas já atuando, então talvez seja necessário a criação de um papel que inicie esse processo ou algum outro que contemple essa fase do processo.

> **Papel**: Inicializador de Badges
>
> **Propósito**: _Concessões de Badges altamente perspicazes e cautelosas para inicializar apenas pessoas suficientes em novas Badges_
>
> Responsabilidades:
>
> * Avaliar pessoas para Badges mediante a sua autonomeação quando não houverem pessoas suficientes que de fato possuem a Badge, trabalhem com o solicitante e que possam avaliar de forma sensata.

### Para ligar Badges a níveis de remuneração

Agora é hora de entender como a [Organização][organizacao] define as suas camadas de remuneração e como as badges podem ser ligadas a estas camadas.

> **Papel**: Arquiteto da Remuneração
>
> **Propósito**: _O sistema de remuneração certo para a organização e as pessoas._
>
> **Responsabilidades**:
>
> * Desenhar, implementar e evoluir os sistemas de remuneração de toda a organização e os processos relacionados para determinar a remuneração de pessoas
> * Definir e publicar possíveis camadas de remuneração, juntamente com os critérios gerais ou perfis de exemplo para guiar a marcação de conjuntos de Badges em camadas adequadas
>
> **Papel**: _Guardião da Remuneração \(Círculo de Parceiros\)_
>
> **Propósito**: _Níveis relativos de remuneração justos para conjuntos de Badges, alinhados com a orientação do Arquiteto da Remuneração._
>
> **Responsabilidades**:
>
> * Avaliar as propostas de valorização de Badges perante outras propostas no Banco de Dados de Valorização de Badges e perante orientações gerais publicadas pelo Arquiteto da Remuneração.
>
> **Restrição**: Valorização de Badges
>
> O “Banco de Dados de Valorização de Badges” é uma listagem dos conjuntos específicos de Badges, com cada conjunto mapeado a uma camada de remuneração definida pelo Arquiteto da Remuneração. A remuneração de tempo integral para uma pessoa deverá ser equivalente à camada mais alta que corresponde a um conjunto de Badges que a pessoa possui \(ou o rateio equivalente para um compromisso parcial\).
>
> O Banco de Dados de Valorização de Badges poderá ser apenas modificado através de uma Proposta que resulta em nenhuma Objeção de todos os Guardiões da Remuneração, usando o Processo de Tomada de Decisão Integrativa. Esta proposta poderá ser feita de forma assíncrona apenas para os Guardiões da Remuneração, usando as regras para propostas assíncronas descritas na Constituição, ou através de uma reunião especial de “Valorização de Badges” agendada por qualquer pessoa. Todos os Guardiões da Remuneração devem ser convidados para esta reunião, assim como o facilitador eleito no círculo, e esta deverá somente ser agendada por 30 minutos. A maioria dos Guardiões da Remuneração deve comparecer à reunião para esta prosseguir, e mesmo com a maioria presente ela não poderá prosseguir se qualquer Guardião da Remuneração solicitar um reagendamento.
>
> Durante a Reunião de Valorização de Badges, a pessoa que agendou a reunião poderá propor uma ou mais modificações à valorização de um conjunto de Badges para o “Banco de Dados de Valorização de Badges”, e o facilitador da reunião deverá processar a Proposta através do Processo de Tomada de Decisão Integrativa, mas com somente os Guardiões da Remuneração participando da Rodada de Objeções \(se o Facilitador eleito escolher não participar, as regras da Constituição para selecionar substitutos se aplicam\). Qualquer proposta que falhe em passar dentro do tempo alocado para reunião é automaticamente descartada. Nenhuma pessoa poderá agendar uma Reunião de Valorização de Badges antes de um mês decorrido desde a última reunião que a pessoa agendou.

Através do processo definido acima, a valorização ligada a qualquer conjunto de Badges poderá ser reduzida, ou mais Badges poderão ser adicionadas a um conjunto existente. Nesses casos, qualquer pessoa cujo nível de remuneração estava ligado com o conjunto de badges modificado poderá manter o seu nível de remuneração calculado de acordo com o conjunto antigo de Badges e a valorização associada por um período de 12 meses seguidos da mudança; neste ponto, níveis de remuneração associados a conjuntos de Badge legados expirarão automaticamente.

### Para administrar a remuneração

Agora vamos criar um papel que dá transparência a todos na [Organização][organizacao] sobre quem detém qual badge e deixar claro o valor da remuneração atrelada aquela badge \(principais badges relacionadas a cada pessoa.\)

> **Papel**: Administrador da Remuneração
>
> **Propósito**: _Manutenção acurada de registros de Badges detidas por cada pessoa e os níveis de remuneração resultantes._
>
> **Responsabilidades**:
>
> * Definir e publicar uma fonte oficial de quais pessoas detém quais Badges
>
>   Publicar e manter um mapeamento oficial de conjuntos de Badges e camadas de remuneração \(Banco de Dados de Valorização de Badges\)
>
> * Identificar e publicar a camada de remuneração que cada pessoa se encaixa baseado no seus conjuntos de Badge mais valiosos listados no Banco de Dados
> * Revisar evidências enviadas por pessoas que outra pessoa ganhou ou perdeu uma Badge, dados os processos ou mecanismos definidos pela Badge, e atualizar os registros de Badges e remuneração se evidências claras e convincentes indicarem que uma Badge foi adquirida ou perdida
> * Rastrear gatilhos baseados em tempo ou em eventos que expirem Badges, e, mediante uma expiração, notificar as partes afetadas e atualizar os registros relevantes

O Objetivo desse padrão é não só cuidar de [Parceiros][parceiros] que já desempenham atividades dentro da [Organização][organizacao] mas também cuidar de novos [Parceiros][parceiros] que estão entrando na organização, para que desde o início se tenha uma remuneração justa e transparente.

> **Restrição**: Transição para a Remuneração Baseada em Badges
>
> Qualquer papel que faça ofertas para novas pessoas se juntarem à organização deve dar a essas pessoas uma remuneração inicial baseada no conjunto de Badges que a pessoa que desempenha o papel acredita que a nova pessoa possa vir a adquirir. A remuneração desta pessoa não poderá cair abaixo da camada inicial definida por um período de 12 meses após juntar-se à organização \(exceto devido a mudança na relação para uma dedicação parcial ou por ser removido da Organização\).

Pessoas que juntaram-se à empresa antes do lançamento do sistema de remuneração Baseada em Badges podem optar por manter o seu nível de remuneração calculado pelo sistema antigo, até tenham Badges suficientes para providenciar um nível de remuneração comparável ou maior através do novo sistema.

### Exemplo prático

Um caso prático para compensar engenheiros de desenvolvimento de software:

**Possíveis badges**:

* Senior Frontend developer
* Senior Backend develope
* Senior Android developer
* Senior iOS developer

**Possíveis níveis de remuneração**:

* Frontend + Backend = V
* Backend + Android = W
* Frontend + Backend + Android = X
* Frontend + Backend + Android + iOS = Y
* Backend + iOS = Z

### Observações sobre a Legislação Trabalhista

Em alguns países, a legislação trabalhista não permite a redução dos salários. Neste cenário, mesmo que alguém perca uma Badge, o salário real se mantém, mas o “salário virtual” reduz. Sendo assim, a pessoa precisa recuperar essa lacuna perdida ganhando ainda mais badges para aumentar a sua remuneração.

## Contexto Resultante

Após a adoção desse padrão ou variações dele, a [Organização][organizacao] começa a construir sua biblioteca de badges e o processo decisório pode ser simplificado ou não, dependendo das tensões sentidas. Ainda pode existir a necessidade de tratar da remuneração variável, talvez com Merit Money or Money Pile.

## Fundamentação

Este padrão foi baseado no [“Badge-based Compensation”](https://www.holacracy.org/badge-based-compensation-app/), descrito por Brian Robertson como uma possível solução de como tratar remuneração na Holacracia. O padrão foi então adaptado para uso na Organização Orgânica.

[organizacao]: ../../meta-acordos/organizacao.md
[parceiros]: ../../meta-acordos/organizacao.md#parceiros
[papeis]: ../../meta-acordos/estrutura-organizacional.md#papeis
