# Lógica de Programação - Estrutura Condicional IF


## **1. Introdução**
- Em programação, muitas vezes precisamos tomar decisões com base em condições.
- A estrutura condicional **if** permite executar diferentes blocos de código dependendo de uma condição.

## **2. Sintaxe do IF**
A estrutura **if** segue a seguinte sintaxe:

```python
if condição:
    # Código executado se a condição for verdadeira
```

**Exemplo:**
```python
idade = 18
if idade >= 18:
    print("Você é maior de idade.")
```

---

## **3. IF-ELSE**
Se quisermos executar um bloco de código quando a condição for **falsa**, usamos **else**:

```python
if condição:
    # Código executado se a condição for verdadeira
else:
    # Código executado se a condição for falsa
```

**Exemplo:**
```python
idade = 16
if idade >= 18:
    print("Você é maior de idade.")
else:
    print("Você é menor de idade.")
```

## **4. IF-ELIF-ELSE**
Podemos testar múltiplas condições com **elif**:

```python
if condição1:
    # Código se condição1 for verdadeira
elif condição2:
    # Código se condição2 for verdadeira
else:
    # Código se nenhuma condição for verdadeira
```

**Exemplo:**
```python
nota = 75
if nota >= 90:
    print("Aprovado com A.")
elif nota >= 70:
    print("Aprovado com B.")
elif nota >= 50:
    print("Aprovado com C.")
else:
    print("Reprovado.")
```

## **5. Condições com Operadores**
Podemos usar operadores lógicos e relacionais nas condições:

- **Operadores relacionais:** `>, <, >=, <=, ==, !=`
- **Operadores lógicos:** `and, or, not`

**Exemplo:**
```python
idade = 20
tem_carteira = True
if idade >= 18 and tem_carteira:
    print("Pode dirigir.")
else:
    print("Não pode dirigir.")
```

## **6. Exercícios Práticos**
1. Escreva um código que verifique se um número é positivo, negativo ou zero.
2. Crie um programa que peça a idade do usuário e informe se ele pode votar.
3. Desenvolva um código que avalie a nota de um aluno e exiba a classificação (A, B, C, Reprovado).
4. Faça um programa que verifique se um ano é bissexto.
5. Escreva um código que solicite um usuário e senha e valide o login.


