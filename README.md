## Sistema de Gerenciamento de Lista de Compras em Supermercado

Organize suas compras no supermercado com eficiência!

Este projeto em Java implementa uma estrutura básica para gerenciar listas de compras. Ele fornece funcionalidades essenciais para adicionar, imprimir e remover itens da lista.

### Classe Principal: SupermarketArray

Representa a lista de compras internamente como um array de strings.
Oferece métodos para manipular a lista:

- `add(String item)`: Adiciona um novo item à lista.
- `print()`: Exibe a lista de compras formatada.
- `delete(int index)`: Remove um item específico da lista por índice.

### Funcionalidades

- **Capacidade definida**: A lista possui um tamanho máximo configurado durante a inicialização (`SupermarketArray(int size)`).
- **Notificações**:
  - Alerta o usuário quando a lista está cheia ao tentar adicionar itens.
  - Informa quando a lista está vazia ao tentar imprimir.
  - Indica índices inválidos ao tentar remover itens.
- **Gerenciamento de índice**:
  - Utiliza `lastIndex` para acompanhar a posição do último item válido no array.
  - O índice real do item na lista é `i` durante a impressão.
