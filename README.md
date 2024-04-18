Este código em C implementa um sistema simples de gerenciamento de notícias.

### Estruturas de Dados:
- `NewsNode`: Estrutura que representa uma notícia, contendo informações como ID, título, autor, texto e ponteiros para o próximo e o anterior nó da lista.
- `NewsList`: Estrutura que mantém uma lista encadeada de notícias.
- `HistoryNode`: Estrutura que representa um nó do histórico de notícias acessadas, contendo um ponteiro para o nó da notícia e um ponteiro para o próximo nó na fila.
- `HistoryQueue`: Estrutura que mantém uma fila encadeada para o histórico de notícias acessadas.

### Funções Principais:
- `createNewsNode`: Cria um novo nó de notícia com as informações fornecidas.
- `insertNews`: Insere uma nova notícia na lista de notícias.
- `removeNews`: Remove uma notícia da lista de notícias com base no ID fornecido.
- `findNews`: Busca uma notícia na lista de notícias com base no ID fornecido.
- `mostrarProximo`: Mostra a próxima notícia na lista, se disponível.
- `mostrarAnterior`: Mostra a notícia anterior na lista, se disponível.
- `ir_para_ultimo`: Move para a última notícia na lista.
- `historico`: Mostra o histórico das últimas notícias acessadas.
- `todas_noti`: Lista todas as notícias presentes na lista.

### Funcionalidades Principais no `main`:
1. Inserção de uma nova notícia.
2. Remoção de uma notícia existente.
3. Busca por uma notícia pelo ID.
4. Listagem de todas as notícias.
5. Navegação para a próxima, anterior ou última notícia.
6. Visualização do histórico das últimas notícias acessadas.
7. Encerramento do programa.

O código utiliza entrada do usuário para interagir com as funcionalidades do sistema. Cada opção do menu corresponde a uma operação específica sobre as notícias.
