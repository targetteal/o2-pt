# Processo de Desenvolvimento da O2

### Processo de Atualização

1) Criar uma branch a partir da branch master para a nova versão, respeitando as regras de versionamento.

2) Realizar um commit para cada mudança aplicada, descrevendo o commit de acordo com as regras definidas. 

3) Abrir um "Pull Request" para a branch "master" após o encerramento do desenvolvimento de cada nova versão.

4) Criar um "release" e uma "tag" para cada nova versão, aplicando o mesmo título da versão.

5) Atualizar o GitBook, acrescentando um novo link para a nova branch.

### Regras de Versionamento 

(Utilizando o [Versionamento Semântico](https://semver.org/lang/pt-BR/) como referência)

Formato da denominação das versões: "v0.0.0", onde:

- O número à esquerda (chamado de MAJOR) indica mudanças profundas que podem conter incompatibilidades com outras versões da Biblioteca de Padrões
- O número ao meio (chamado de MINOR) indica acréscimos e alterações menores que não alteram a estrutura de tópicos do documento.
- O número à direita (chamado de PATCH) indica pequenas correções, sem acrescentar ou remover nenhuma parte do documento.
- Toda nova versão deve começar com a letra "v" em minúsculo seguida do seu número de versão correspondente.

### Branches Fixas

- master: Última versão dos Meta-Acordos da O2 contendo os últimos patches e atualizações.
- vN.N.N: Versões anteriores dos Meta-Acordos da O2 para histórico e compatibilidade com a Biblioteca de Padrões.
- targetteal: Versão atual dos Meta-Acordos da O2 que estão sendo utilizados na Target Teal, podendo conter seções de experimentação interna diferentes da versão atual da O2.
