# 🧠 Aula: Laços de Repetição em Lógica Computacional

## 📌 Conceito:
Laços de repetição são estruturas que permitem repetir um bloco de código várias vezes, de forma controlada, até que uma condição seja satisfeita.

Exemplo cotidiano:
“Enquanto o despertador não tocar, continue dormindo.”

## ➰ Tipos de Laços
1. while (enquanto)
Executa um bloco de código enquanto a condição for verdadeira.

```Python
contador = 0
while contador < 5:
    print("Valor:", contador)
    contador += 1
``` 
### 🔄 Fluxo:

- Verifica a condição.
- Se for verdadeira, executa o bloco.
- Volta a verificar a condição.

2. for (para)
Ideal para quando sabemos o número de repetições.

```python
for i in range(5):
    print("Valor:", i)
  ```
### 🔁 Fluxo:

- Define um valor inicial.
- Estabelece um fim.
- Incrementa automaticamente.

3. do...while (simulado em Python com while True)
Executa pelo menos uma vez, depois verifica a condição.

``` python
while True:
    valor = int(input("Digite um número positivo: "))
    if valor > 0:
        break
```
## 🎮 Atividade Prática (15 minutos)

- Desafio 1: Contador simples
  - Peça para o aluno imprimir os números de 1 a 10 usando um while.
- Desafio 2: Tabuada
  - Escreva um programa que pede um número e imprime a tabuada de 1 a 10.

## 🎁 Dica de Ouro

- Quantas vezes você quer que o código repita?
- Existe uma condição clara de parada?

## ❓ Discussão Final
- Quando usar while e quando usar for?
- O que acontece se a condição do while nunca for falsa?

## 📝 Exercício
- Desafio: Crie um programa que peça ao usuário um número secreto e fique pedindo até ele acertar.
