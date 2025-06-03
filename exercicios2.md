# Exercícios de Arrays em JavaScript

## 1. `push`

**Situação:**  
Você está desenvolvendo um sistema simples para registrar a lista de compras do mês. Cada vez que o usuário adiciona um item, ele deve ser colocado no final da lista.

**Desafio:**  
Dado o array inicial `let listaDeCompras = ['Arroz', 'Feijão'];`, adicione os itens `'Leite'` e `'Ovos'` utilizando o método `push`.

---

## 2. `pop`

**Situação:**  
Em uma aplicação de fila de impressão, o último documento adicionado pode ser cancelado antes de ser impresso.

**Desafio:**  
Dado o array `let filaDeImpressao = ['doc1.pdf', 'doc2.pdf', 'relatorio.xls'];`, remova o último documento utilizando `pop` e mostre qual documento foi cancelado.

---

## 3. `shift`

**Situação:**  
Você está criando uma agenda de atendimentos. A cada novo atendimento finalizado, o primeiro nome da fila deve ser removido.

**Desafio:**  
Dado o array `let fila = ['Maria', 'João', 'Ana'];`, utilize `shift` para remover a pessoa que já foi atendida. Mostre quem foi atendido e como ficou a fila.

---

## 4. `unshift`

**Situação:**  
Um sistema de entregas permite adicionar entregas urgentes no início da fila.

**Desafio:**  
Dado o array `let entregas = ['Pedido 102', 'Pedido 103'];`, adicione o `'Pedido Urgente 101'` no início utilizando `unshift`.

---

## 5. `forEach`

**Situação:**  
Você está exibindo uma lista de tarefas para o dia com numeração.

**Desafio:**  
Dado o array `let tarefas = ['Lavar roupa', 'Estudar JS', 'Fazer exercícios'];`, utilize `forEach` para exibir cada tarefa precedida de sua posição, começando do 1.  
**Exemplo esperado:**  
1. Lavar roupa  
2. Estudar JS  
3. Fazer exercícios

---

## 6. `sort`

**Situação:**  
Você está criando uma ferramenta para ordenar os nomes dos alunos em ordem alfabética para um certificado.

**Desafio:**  
Dado o array `let alunos = ['Carlos', 'Amanda', 'Bruno'];`, use `sort` para ordenar os nomes e exibi-los.

---

## 7. `indexOf`

**Situação:**  
Um sistema de busca precisa encontrar a posição de um produto específico em um estoque.

**Desafio:**  
Dado o array `let estoque = ['Teclado', 'Mouse', 'Monitor', 'Impressora'];`, descubra a posição do item `'Monitor'` usando `indexOf`.

---

## 8. `includes`

**Situação:**  
Uma lista de presença deve verificar se determinado aluno está presente.

**Desafio:**  
Dado o array `let presentes = ['Lucas', 'Fernanda', 'Beatriz'];`, verifique se `'Fernanda'` está presente usando `includes` e exiba uma mensagem apropriada.

---

👨‍💻 Boa sorte! Depois de resolver, experimente criar seus próprios exemplos com essas funções!
--- 

### 9. Lista de Tarefas com Prioridades

Crie um programa que:
- Permita ao usuário inserir uma tarefa (string) e uma prioridade (número).
- Armazene cada tarefa como uma string formatada ("Tarefa - Prioridade X") em um array.
- Exiba todas as tarefas na tela usando `forEach`.

Adicione botões no HTML para adicionar uma nova tarefa e limpar a lista. Use `innerHTML` para exibir os dados.

---

### 10. Cálculo de Média de Notas

Crie um formulário onde o usuário insira notas (números) de um aluno uma por vez.
- Use `push` para adicionar a nota a um array.
- Mostre a média das notas usando `reduce` toda vez que uma nova nota for inserida.
- Se a média for maior ou igual a 7, exiba "Aprovado", senão, "Reprovado".

Use `innerHTML` para mostrar os resultados em tempo real.

---

### 11. Filtro de Palavras

Permita ao usuário digitar uma lista de palavras separadas por vírgula.
- Transforme a string em um array com `split`.
- Filtre e exiba apenas as palavras que começam com uma letra específica (ex: "A").
- Use `filter`, `trim` e `innerHTML`.

---

### 12. Ordenador de Números

Crie um campo de input onde o usuário digita números separados por vírgula.
- Armazene os números em um array.
- Exiba o array ordenado (menor para maior) usando `sort`.
- Mostre o maior e o menor número com `Math.max.apply` e `Math.min.apply`.

---

### 13. Verificador de Lista de Compras

Permita ao usuário inserir itens de uma lista de compras.
- Armazene os itens em um array.
- Verifique se um determinado item está na lista usando `includes`.
- Mostre uma mensagem "Item encontrado" ou "Item não encontrado".

Use um botão para adicionar e outro para buscar. Exiba os dados com `innerHTML`.

___

### 14. Cadastro de Usuários

Crie um formulário com nome, idade e email.
- Armazene cada cadastro como um objeto dentro de um array.
- Exiba todos os usuários cadastrados com `forEach`.
- Use desestruturação ao exibir os dados.

---

### 15. Contador de Tipos de Produto

Crie um array de objetos com produtos, cada um com nome e tipo (ex: "fruta", "bebida", "limpeza").
- Ao clicar em um botão, exiba quantos produtos existem de cada tipo.
- Use `reduce` e `Object.entries` para contar e exibir os dados.

---

### 16. Atualizador de Status de Tarefa

Crie uma lista de tarefas (array de objetos com `nome` e `concluida: false`).
- Exiba as tarefas com um botão "Concluir".
- Ao clicar no botão, atualize o status da tarefa para `true` usando `map`.
- Mostre visualmente as tarefas concluídas.

---

### 17. Buscador de Funcionário

Crie um array de objetos com funcionários (nome, cargo e email).
- Permita buscar pelo nome usando `find`.
- Exiba os dados completos do funcionário ou "Funcionário não encontrado".

---

### 18. Sistema de Votação

Crie um array de objetos representando candidatos com nome e votos.
- Adicione botões de "Votar" em cada um.
- Ao votar, incremente o número de votos do candidato com `forEach`.
- Exiba o vencedor (quem tem mais votos) com `reduce`.

Use `innerHTML` para mostrar os resultados atualizados.
