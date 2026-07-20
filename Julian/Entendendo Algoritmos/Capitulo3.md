# Recursão

Recursão é quando uma função chama a si mesma.

Toda função recursiva tem dois casos: o **caso-base** e o **caso recursivo**.

- **Caso base**: é o caso que marca onde encerra o looping das chamadas.
- **Caso recursivo**: é o caso que chama a própria função.

## Pilha

Uma pilha (*stack*) é uma estrutura de dados que organiza elementos seguindo o princípio **LIFO** (*Last In, First Out* — o último a entrar é o primeiro a sair).

- Imagine uma pilha de pratos: você sempre adiciona e remove do topo. Suas principais ações são o **push** (adicionar ao topo) e o **pop** (remover do topo).
- Todas as chamadas de função vão para a **pilha de chamadas**.
- A pilha de chamadas pode ficar muito grande e ocupar muita memória.