### ✅ 1. Calculadora de Horas Trabalhadas

**Contexto:**  
Você é um programador freelancer e quer calcular o valor total a receber com base nas horas trabalhadas e no valor cobrado por hora.

**Desafio:**
- Crie uma função `calcularPagamento` que:
  - Recebe dois parâmetros: `horasTrabalhadas` e `valorHora`.
  - Retorna o valor total a receber (multiplicação simples).
  - Se `horasTrabalhadas` for menor ou igual a 0, exiba uma mensagem de erro.
  - Se o valor total for maior que R$2000, exiba uma mensagem especial parabenizando.

**🧩 Requisitos adicionais:**
- Crie um formulário HTML para inserir as informações.
- Exiba o resultado com `innerHTML`.

---

### ✅ 2. Simulador de Login

**Contexto:**  
Você está simulando uma tela de login de um sistema.

**Desafio:**
- Crie uma função `login` que:
  - Recebe dois parâmetros: `email` e `senha`.
  - Compare esses valores com dois valores definidos na própria função (ex: `emailValido = "admin@teste.com"` e `senhaValida = "1234"`).
  - Se estiverem corretos, exiba `"Login realizado com sucesso"`.
  - Caso contrário, exiba `"E-mail ou senha inválidos"`.

**🧩 Requisitos adicionais:**
- Crie um formulário HTML com campos de e-mail e senha.
- Exiba a mensagem de login com `innerHTML`.

---

### ✅ 3. Classificador de Nível de Tarefa

**Contexto:**  
Você quer classificar uma tarefa de acordo com a sua prioridade e mostrar o nome da atividade junto com a classificação.

**Desafio:**
- Crie uma função `classificarTarefa` que:
  - Recebe dois parâmetros: `atividade` (string) e `prioridade` (number).
  - Use `switch` para exibir:
    - 1 → “A atividade [atividade] é urgente.”
    - 2 → “A atividade [atividade] é importante.”
    - 3 → “A atividade [atividade] é opcional.”
    - Qualquer outro número → “Prioridade inválida para a atividade [atividade].”

**🧩 Requisitos adicionais:**
- Crie um formulário HTML com:
  - Um campo de texto para o nome da atividade.
  - Um `select` com as opções de prioridade (1, 2 ou 3).
- Exiba o resultado da classificação com `innerHTML`.

---

### ✅ 4. Validador de Cadastro

**Contexto:**  
Você quer validar os dados de um novo usuário antes de efetuar o cadastro.

**Desafio:**
- Crie uma função `validarCadastro` que:
  - Recebe três valores: `nome`, `idade` e `email`.
  - Valide se:
    - O nome não está vazio.
    - A idade é maior ou igual a 18.
    - O e-mail contém o caractere "@".
  - Exiba mensagens diferentes para cada tipo de erro.
  - Se tudo estiver certo, exiba uma mensagem de sucesso.

**🧩 Requisitos adicionais:**
- Crie um formulário HTML com os três campos.
- Use `innerHTML` para mostrar as mensagens.

---

### ✅ 5. Calculadora Simples

**Contexto:**  
Você quer criar uma calculadora de operações básicas.

**Desafio:**
- Crie uma função `calcular` que:
  - Recebe dois números e um operador (`+`, `-`, `*`, `/` ou `%`).
  - Realiza a operação correspondente e retorna o resultado.
  - Se o operador não for válido, exiba uma mensagem de erro.

**🧩 Requisitos adicionais:**
- Crie um formulário HTML com dois campos numéricos e um de operador.
- Exiba o resultado da operação com `innerHTML`.

---
