# Decomposição da Estrutura

## Contexto

Em organizações autogeridas, o poder é transferido das relações pessoais para os acordos organizacionais, como Papéis, Círculos e Restrições. Para que esses acordos tenham peso e legitimidade, eles precisam refletir a realidade atual da organização, o que requer atualizações e relembramento constantes.

No entanto, é comum que depois de algum tempo, Papéis ou Restrições propostos inicialmente acabem caindo em desuso, pois não há um Papel específico responsável por fazer uma "faxina" na estrutura organizacional. Esses acordos obsoletos permanecem na estrutura, ocupando espaço desnecessariamente e aumentando a quantidade de informações, tornando todo o sistema mais confuso e difícil de navegar.

Se houvesse uma maneira de determinar uma validade para os acordos, eles poderiam se decompor naturalmente quando se tornarem obsoletos, evitando a necessidade de revisões demoradas, mas ainda permitindo que acordos válidos sejam renovados.

## Forças

- Manter acordos antigos em desuso pode tornar a Estrutura mais confusa e difícil de navegar;
- Remover periodicamente acordos obsoletos de forma manual consome tempo e esforço dos integrantes;
- Acordos que perderam a validade, mas permanecem na estrutura, podem gerar desinformação e decisões equivocadas;
- Com muitos acordos desnecessários, fica mais difícil para novos integrantes compreenderem a estrutura organizacional;
- Ter uma estrutura enxuta e atualizada aumenta a credibilidade e reforça o poder nos acordos.

## Solução

Este padrão requer a adição de alguns novos Meta-Acordos:

### Decomposição da Estrutura

Todos os Papeis e Restrições da Organização possuem uma data de validade, que é definida automaticamente como 3 meses a frente do momento da sua criação. Toda vez que os Papeis ou Círculos sofrem uma modificação por meio da interação Adaptar, sua data de validade é renovada para 3 meses a frente do momento da mudança.

Uma Restrição pode ser adotada para redefinir esse período de validade inicial ou qual o período adicionado à validade quando ocorre uma modificação.

#### Vencimento 

Toda vez que um Papel ou Restrição vencer, ele deverá ser automaticamente excluído da Estrutura Organizacional e considerado inválido. Toda vez que um Círculo permanecer sem nenhum Papel ou Restrição por mais de 3 meses, ele deverá ser automaticamente transformado em um Papel.

#### Revalidação 

Qualquer Integrante do Círculo poderá submeter na interação Adaptar uma proposta de revalidação de um Papel ou Círculo, bastando apresentar na sua Tensão uma evidência de que aquele acordo continua sendo útil e necessário. 

## Contexto Resultante

A estrutura se torna mais enxuta e focada, com apenas os acordos realmente necessários no momento. Os integrantes precisam se engajar periodicamente para revalidar os acordos que ainda são úteis.

## Fundamentação

Esse padrão se inspira em conceitos de decomposição natural e obsolescência programada de sistemas.

## Usos Conhecidos

Em experientação na TT.