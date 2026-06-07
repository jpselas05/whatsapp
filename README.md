# Estrutura de Dados

Repositório didático da disciplina de Estrutura de Dados (T390), voltado para
alunos de graduação em Computação. A ideia central é implementar as estruturas
do zero, de forma simples, legível e comentada, para que seja possível estudar
não apenas como usar cada estrutura, mas também como ela funciona internamente.

Os códigos evitam bibliotecas prontas de estruturas de dados sempre que isso
ajuda o aprendizado. Em vez de esconder ponteiros, vetores, colisões ou
rotações, o repositório expõe essas operações para que elas possam ser
analisadas em aula, depuradas e modificadas pelos alunos.

## Organização Geral

```text
Unidade3/
Unidade4/
QuestoesPraticas/
  06-Hash/
  07-Arvores/
```

Cada unidade possui um README próprio com a ordem sugerida de estudo.

## Conteúdo da Disciplina

### Unidade III - Estruturas de dados dispersas

Explicar o funcionamento de estruturas de dados dispersas na resolução de
problemas computacionais.

Implementar algoritmos com estruturas de dados dispersas.

Valorar a importância das estruturas de dados dispersas para organização e busca
de dados.

Conteúdo:

1. 03.01 - Tabelas hashing.
2. 03.02 - Função de hashing.
3. 03.03 - Endereçamento aberto: tentativa linear e tentativa quadrática.
4. 03.04 - Endereçamento fechado.

### Unidade IV - Estruturas de dados hierárquicas

Identificar os cenários propícios para o emprego de estruturas de dados
hierárquicas.

Aplicar estruturas de dados hierárquicas na resolução de problemas
computacionais.

Ser crítico no uso das estruturas de dados hierárquicas na resolução de
problemas computacionais.

Conteúdo:

1. 04.01 - Árvore N-ária.
2. 04.02 - Árvore binária.
3. 04.03 - Árvore de busca.
4. 04.04 - Árvore balanceada AVL.

## Padrão dos Códigos

Os arquivos seguem um padrão didático simples:

- seções para atributos, construtor, métodos básicos, inserção, remoção, busca
  e representação;
- `main` com exemplo determinístico e comentado.
