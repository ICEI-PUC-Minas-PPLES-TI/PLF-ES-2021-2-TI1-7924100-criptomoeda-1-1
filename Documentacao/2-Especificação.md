# Especificações do projeto

<span style="color:red">Pré-requisitos: <a href="1-Contexto.md"> Documentação de Contexto</a></span>

## Personas

1. **Augusto** tem 30 anos, é gerente em uma fábrica de bolsas de couro. É muito ocupado com seu trabalho e por conta da alta volatilidade do mercado, se sente desgastado ao tentar acompanhar o mercado. Gostaria de ter acesso mais fácil as principais atualizações e movimentações do mercado, sem ter que ficar procurando-as ativamente. Além disso, gostaria de melhorar seu conhecimento sobre o assunto, que não é muito profundo. Hoje, ele resolve esse problema acompanhando influenciadores da área.

2. **Jonathan** tem 42 anos e já investe há mais de cinco anos. Entretanto, sua maior dificuldade hoje é o tempo que gasta analisando e filtrando as informações relacionadas aos projetos em que deseja investir, ou já investe. Acredita que deixa muitas informações importantes passarem desapercebidas por conta da quantidade de dados em várias fontes diferentes.

3. **Marcos** tem 21 anos, é estudante de Engenharia Civil e curioso pelo mercado de criptomoedas. Como não tem experiência, investiu apenas um pequeno montante pois se sente preocupado em aplicar suas economias em algo que não conhece bem.

---

## Histórias de usuários

Com base na análise das personas foram identificadas as seguintes histórias de usuários:

| COMO... `PERSONA`   | QUERO/PRECISO...  `FUNCIONALIDADE` | PARA... `MOTIVO/VALOR`                 |
|---------------------|------------------------------------|----------------------------------------|
| Augusto | Receber as principais atualizações sobre o mercado | Me manter atualizado sem gastar muito tempo |
| Augusto | Aprender mais sobre o mercado | Para tomar decisões mais informadas |
| Jonathan | Ver as novidades do mercado concentradas em só lugar | Otimizar o tempo gasto analisando as informações e não perder acontecimentos importantes
| Marcos | De educação em criptomoedas | Não perder suas economias investindo em algo que não tem conhecimento

---

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

| ID     | Descrição do requisito  | Prioridade |
|--------|-------------------------|------------|
| RF-001 | Permitir que o usuário cadastre suas aplicações | ALTA |
| RF-002 | Mostrar atualizações de projetos, como notícias e eventos, relacionadas a carteira do usuário | ALTA |
| RF-003 | Permitir que o usuário veja o desempenho de seus investimentos | ALTA |
| RF-004 | Disponibilizar uma página com as informações de um determinado ativo | MÉDIA |
| RF-005 | Teste de conhecimento sobre o mercado | MÉDIA |
| RF-006 | Recomendar conteúdos educacionais de acordo com nível de conhecimento do usuário | BAIXA |


### Requisitos não Funcionais

| ID      | Descrição do Requisito  | Prioridade |
|---------|-------------------------|------------|
| RNF-001 | O sistema deve ser responsivo para rodar em um dispositivos móvel | ALTA |
| RNF-002 | A interface deve ser "clean" e passar confiança ao usuário | ALTA |

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |