# Introdução a Dados Primitivos e Variáveis em Python

### Introdução aos Dados Primitivos
- **Definição:** Dados primitivos são os tipos de dados básicos que uma linguagem de programação oferece.
- **Principais tipos em Python:**
  - `int`: Números inteiros (ex: 5, -10)
  - `float`: Números de ponto flutuante (ex: 3.14, -0.001)
  - `str`: Cadeias de caracteres (ex: "Olá, mundo!")
  - `bool`: Valores booleanos (True, False)

### Atribuição de Variáveis
- **Definição:** Atribuição é o processo de armazenar um valor em uma variável.
- **Sintaxe:**
  ```python
  nome = "Alice"  # Atribuição de uma string
  idade = 25      # Atribuição de um inteiro
  altura = 1.75   # Atribuição de um float
  ```

### Variáveis Simples
- **Uso de variáveis:**
  - Variáveis permitem armazenar valores que podem ser utilizados em cálculos ou operações.
  - Exemplo:
  ```python
  a = 10
  b = 5
  soma = a + b
  print(soma)  # Saída: 15
  ```
- **Regras de Declaração de Variáveis em Python**

1. **Nomes de Variáveis:**
   - Devem começar com uma letra (a-z, A-Z) ou um underscore (_).
   - Podem conter letras, números (0-9) e underscores.
   - Não podem começar com um número.
   - São sensíveis a maiúsculas e minúsculas (por exemplo, `idade` e `Idade` são considerados diferentes).

2. **Palavras Reservadas:**
   - Não podem ser usadas como nomes de variáveis palavras reservadas como: `if`, `else`, `while`, `for`, `class`, `def`, `return`, entre outras.

3. **Comprimento do Nome:**
   - Não há limite formal no comprimento dos nomes de variáveis, mas é recomendável que sejam descritivos e não muito longos para facilitar a leitura.

4. **Boas Práticas:**
   - Use nomes descritivos que indiquem o propósito da variável. Por exemplo, em vez de usar `x`, use `idade` ou `altura`.
   - Para variáveis compostas, use o estilo snake_case (ex: `minha_variavel`) para melhorar a legibilidade.

### Exemplos de Declarações Válidas e Inválidas

#### Válidas:
```python
nome = "João"           # Válido
idade = 30              # Válido
altura_em_metros = 1.75 # Válido
_nota_final = 8.5       # Válido
```

#### Inválidas:
```python
1idade = 30             # Inválido (começa com número)
nome completo = "Ana"   # Inválido (espaço no nome)
if = "teste"            # Inválido (palavra reservada)
```

### Constantes
- **Definição:** Constantes são valores que não mudam durante a execução do programa.
- **Conceito em Python:**
  - Embora Python não tenha uma forma nativa de definir constantes como em outras linguagens, uma convenção comum é usar letras maiúsculas.
  ```python
  PI = 3.14
  ```

#### Entrada de Dados
- **Função `input()`:** Usada para capturar entrada do usuário.
- **Exemplo:**
  ```python
  nome = input("Digite seu nome: ")
  print("Olá, " + nome + "!")
  ```

#### Saída de Dados
- **Função `print()`:** Usada para exibir dados.
- **Exemplo:**
  ```python
  idade = 30
  print("Sua idade é:", idade)
  ```

#### Exercício Prático
- **Atividade:** Crie um programa que solicite ao usuário seu nome, idade e altura, e depois exiba uma mensagem com essas informações.
  
```python
# Código do exercício
nome = input("Digite seu nome: ")
idade = int(input("Digite sua idade: "))
altura = float(input("Digite sua altura em metros: "))

print(f"Olá, {nome}! Você tem {idade} anos e sua altura é {altura} metros.")
```
