# Decomposição da Estrutura

## Contexto

Em organizações autogeridas, o poder é transferido das relações pessoais para os acordos organizacionais, como [Papéis][papeis], [Círculos][circulos] e [Restrições][restricoes]. Para que esses acordos tenham peso e legitimidade, eles precisam refletir a realidade atual da [Organização][organizacao], o que requer atualizações e relembramento constantes.

No entanto, é comum que depois de algum tempo, [Papéis][papeis] ou [Restrições][restricoes] propostos inicialmente acabem caindo em desuso, pois não há um [Papel][papeis] específico responsável por fazer uma "faxina" na [Estrutura Organizacional][estrutura-organizacional]. Esses acordos obsoletos permanecem na estrutura, ocupando espaço desnecessariamente e aumentando a quantidade de informações, tornando todo o sistema mais confuso e difícil de navegar.

Se houvesse uma maneira de determinar uma validade para os acordos, eles poderiam se decompor naturalmente quando se tornarem obsoletos, evitando a necessidade de revisões demoradas, mas ainda permitindo que acordos válidos sejam renovados.

## Forças

- Manter acordos antigos em desuso pode tornar a Estrutura mais confusa e difícil de navegar;
- Remover periodicamente acordos obsoletos de forma manual consome tempo e esforço dos integrantes;
- Acordos que perderam a validade, mas permanecem na estrutura, podem gerar desinformação e decisões equivocadas;
- Com muitos acordos desnecessários, fica mais difícil para novos integrantes compreenderem a [Estrutura Organizacional][estrutura-organizacional];	
- Ter uma estrutura enxuta e atualizada aumenta a credibilidade e reforça o poder nos acordos.

## Solução

Este padrão requer a adição de alguns novos Meta-Acordos:

### Decomposição da Estrutura

Todos os [Papeis][papeis] e [Restrições][restricoes] da [Organização][organizacao] possuem uma data de validade, que é definida automaticamente como 3 meses a frente do momento da sua criação. Toda vez que os [Papeis][papeis] ou [Círculos][circulos] sofrerem uma modificação por meio da interação [Adaptar][adaptar], sua data de validade é renovada para 3 meses a frente do momento da mudança.

Uma [Restrição][restricoes] pode ser adotada para redefinir esse período de validade inicial ou qual o período adicionado à validade quando ocorre uma modificação.

#### Vencimento 

Toda vez que um [Papel][papeis] ou [Restrição][restricoes] vencer, ele será automaticamente excluído da Estrutura Organizacional e considerado inválido. Toda vez que um [Círculo][circulos] permanecer sem nenhum [Papel][papeis] ou [Restrição][restricoes] por mais de 3 meses, ele será automaticamente transformado em um [Papel][papeis].

#### Revalidação 

Qualquer [Integrante do Círculo][integrantes-do-circulo] poderá submeter na interação [Adaptar][adaptar] uma proposta de revalidação de um [Papel][papeis] ou [Restrição][restricoes], bastando apresentar na sua [Tensão][tensoes] uma evidência de que aquele acordo continua sendo útil e necessário. 

## Contexto Resultante

A estrutura se torna mais enxuta e focada, com apenas os acordos realmente necessários no momento. Os integrantes precisam se engajar periodicamente para revalidar os acordos que ainda são úteis.

## Fundamentação

Esse padrão se inspira em conceitos de decomposição natural e obsolescência programada de sistemas.

## Usos Conhecidos

Em experientação na TT.

<!-- Links -->
[meta-acordos]: ../../meta-acordos.md#meta-acordos-da-organizacao-organica
[organizacao ]: ../../meta-acordos.md#1-organizacao
[proposito]: ../../meta-acordos.md#1.1-proposito
[colegas]: ../../meta-acordos.md#1.2-colegas
[tensoes]: ../../meta-acordos.md#1.3-tensoes-criativas
[estrutura-organizacional]: ../../meta-acordos.md#2-estrutura-organizacional
[papeis]: ../../meta-acordos.md#2.1-papeis
[energizacao]: ../../meta-acordos.md#2.1.1-energizacao
[autoridade-do-papel]: ../../meta-acordos.md#2.1.2-autoridade-do-papel
[deixando-papeis]: ../../meta-acordos.md#2.1.3-deixando-papeis
[circulos]: ../../meta-acordos.md#2.2-circulos
[circulos-nao-alteram-sua-definicao]: ../../meta-acordos.md#2.2.1-circulos-nao-alteram-sua-definicao
[circulos-nao-estruturam-seus-circulos-internos]: ../../meta-acordos.md#2.2.2-circulos-nao-estruturam-seus-circulos-internos
[artefatos-do-circulo]: ../../meta-acordos.md#2.3-artefatos-do-circulo
[circulos-podem-delegar-artefatos]: ../../meta-acordos.md#2.3.1-circulos-podem-delegar-artefatos
[integrantes-do-circulo]: ../../meta-acordos.md#2.4-integrantes-do-circulo
[restricoes]: ../../meta-acordos.md#2.5-restricoes
[restricoes-nao-estabelecem-responsabilidades]: ../../meta-acordos.md#2.5.1-restricoes-nao-estabelecem-responsabilidades
[prioridades-do-circulo]: ../../meta-acordos.md#2.6-prioridades-do-circulo
[reunioes-e-interacoes]: ../../meta-acordos.md#3-reunioes-e-interacoes
[revisar]: ../../meta-acordos.md#3.1-revisar
[sincronizar]: ../../meta-acordos.md#3.2-sincronizar
[adaptar]: ../../meta-acordos.md#3.3-adaptar
[operacoes-de-adaptar]: ../../meta-acordos.md#3.3.1-operacoes-de-adaptar
[decisao-integrativa]: ../../meta-acordos.md#3.3.2-decisao-integrativa
[proposta]: ../../meta-acordos.md#3.3.2.1-proposta
[apresentacao-de-exemplos]: ../../meta-acordos.md#3.3.2.2-apresentacao-de-exemplos
[facilitador-pode-descartar-a-proposta]: ../../meta-acordos.md#3.3.2.3-facilitador-pode-descartar-a-proposta
[objecoes]: ../../meta-acordos.md#3.3.2.4-objecoes
[objecoes-validas]: ../../meta-acordos.md#3.3.2.5-objecoes-validas
[facilitador-pode-descartar-a-objecao]: ../../meta-acordos.md#3.3.2.6-facilitador-pode-descartar-a-objecao
[integracao]: ../../meta-acordos.md#3.3.2.7-integracao
[quebra-dos-meta-acordos]: ../../meta-acordos.md#3.3.2.8-quebra-dos-meta-acordos
[cuidar]: ../../meta-acordos.md#3.4-cuidar
[reuniao-de-circulo]: ../../meta-acordos.md#3.5-reuniao-de-circulo
[somente-integrantes-podem-tratar-tensoes]: ../../meta-acordos.md#3.5.1-somente-integrantes-podem-tratar-tensoes
[formato-da-reuniao]: ../../meta-acordos.md#3.5.2-formato-da-reuniao
[integrantes-ausentes]: ../../meta-acordos.md#3.5.3-integrantes-ausentes
[priorize-a-reuniao]: ../../meta-acordos.md#3.5.4-priorize-a-reuniao
[restricoes-de-facilitacao]: ../../meta-acordos.md#3.6-restricoes-de-facilitacao
[uma-tensao-de-cada-vez]: ../../meta-acordos.md#3.6.1-uma-tensao-de-cada-vez
[lista-de-tensoes]: ../../meta-acordos.md#3.6.2-lista-de-tensoes
[interacoes-assincronas]: ../../meta-acordos.md#3.7-interacoes-assincronas
[novas-interacoes]: ../../meta-acordos.md#3.8-novas-interacoes
[papeis-essenciais]: ../../meta-acordos.md#4-papeis-essenciais
[guia]: ../../meta-acordos.md#4.1-guia
[energizacao-do-guia]: ../../meta-acordos.md#4.1.1-energizacao-do-guia
[representante]: ../../meta-acordos.md#4.2-representante
[facilitador]: ../../meta-acordos.md#4.3-facilitador
[escriba]: ../../meta-acordos.md#4.4-escriba
[papeis-essenciais-eleitos]: ../../meta-acordos.md#4.5-papeis-essenciais-eleitos
[colegas-elegiveis]: ../../meta-acordos.md#4.5.1-colegas-elegiveis
[eleicoes]: ../../meta-acordos.md#4.5.2-eleicoes
[alteracoes-nos-papeis-essenciais]: ../../meta-acordos.md#4.5.3-alteracoes-nos-papeis-essenciais
[alteracoes-nos-papeis-essenciais-nao-propagam]: ../../meta-acordos.md#4.5.3.1-alteracoes-nos-papeis-essenciais-nao-propagam
[energizacao-de-papeis-definidos]: ../../meta-acordos.md#5-energizacao-de-papeis-definidos
[foco]: ../../meta-acordos.md#5.1-foco
[autorresponsabilizacao]: ../../meta-acordos.md#5.2-autorresponsabilizacao
[transparencia]: ../../meta-acordos.md#5.3-transparencia
[ato-heroico]: ../../meta-acordos.md#5.4-ato-heroico
