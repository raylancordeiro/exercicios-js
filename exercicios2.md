### 1. Lista de Tarefas com Prioridades

Crie um programa que:
- Permita ao usuário inserir uma tarefa (string) e uma prioridade (número).
- Armazene cada tarefa como uma string formatada ("Tarefa - Prioridade X") em um array.
- Exiba todas as tarefas na tela usando `forEach`.

Adicione botões no HTML para adicionar uma nova tarefa e limpar a lista. Use `innerHTML` para exibir os dados.

---

### 2. Cálculo de Média de Notas

Crie um formulário onde o usuário insira notas (números) de um aluno uma por vez.
- Use `push` para adicionar a nota a um array.
- Mostre a média das notas usando `reduce` toda vez que uma nova nota for inserida.
- Se a média for maior ou igual a 7, exiba "Aprovado", senão, "Reprovado".

Use `innerHTML` para mostrar os resultados em tempo real.

---

### 3. Filtro de Palavras

Permita ao usuário digitar uma lista de palavras separadas por vírgula.
- Transforme a string em um array com `split`.
- Filtre e exiba apenas as palavras que começam com uma letra específica (ex: "A").
- Use `filter`, `trim` e `innerHTML`.

---

### 4. Ordenador de Números

Crie um campo de input onde o usuário digita números separados por vírgula.
- Armazene os números em um array.
- Exiba o array ordenado (menor para maior) usando `sort`.
- Mostre o maior e o menor número com `Math.max.apply` e `Math.min.apply`.

---

### 5. Verificador de Lista de Compras

Permita ao usuário inserir itens de uma lista de compras.
- Armazene os itens em um array.
- Verifique se um determinado item está na lista usando `includes`.
- Mostre uma mensagem "Item encontrado" ou "Item não encontrado".

Use um botão para adicionar e outro para buscar. Exiba os dados com `innerHTML`.

___

### 6. Cadastro de Usuários

Crie um formulário com nome, idade e email.
- Armazene cada cadastro como um objeto dentro de um array.
- Exiba todos os usuários cadastrados com `forEach`.
- Use desestruturação ao exibir os dados.

---

### 7. Contador de Tipos de Produto

Crie um array de objetos com produtos, cada um com nome e tipo (ex: "fruta", "bebida", "limpeza").
- Ao clicar em um botão, exiba quantos produtos existem de cada tipo.
- Use `reduce` e `Object.entries` para contar e exibir os dados.

---

### 8. Atualizador de Status de Tarefa

Crie uma lista de tarefas (array de objetos com `nome` e `concluida: false`).
- Exiba as tarefas com um botão "Concluir".
- Ao clicar no botão, atualize o status da tarefa para `true` usando `map`.
- Mostre visualmente as tarefas concluídas.

---

### 9. Buscador de Funcionário

Crie um array de objetos com funcionários (nome, cargo e email).
- Permita buscar pelo nome usando `find`.
- Exiba os dados completos do funcionário ou "Funcionário não encontrado".

---

### 10. Sistema de Votação

Crie um array de objetos representando candidatos com nome e votos.
- Adicione botões de "Votar" em cada um.
- Ao votar, incremente o número de votos do candidato com `forEach`.
- Exiba o vencedor (quem tem mais votos) com `reduce`.

Use `innerHTML` para mostrar os resultados atualizados.
