### Exercícios de If

1. **Verificação de Idade**:
   - Escreva um programa que peça ao usuário a idade e verifique se ele é maior de idade (18 anos ou mais). Exiba uma mensagem apropriada.
   ```python
   idade = int(input("Digite sua idade: "))
   if idade >= 18:
       print("Você é maior de idade.")
   else:
       print("Você é menor de idade.")
   ```

2. **Maior número**:
   - Peça ao usuário para inserir dois números e verifique qual deles é maior. Exiba uma mensagem mostrando o maior número.
   ```python
   num1 = int(input("Digite o primeiro número: "))
   num2 = int(input("Digite o segundo número: "))
   if num1 > num2:
       print(f"O maior número é: {num1}")
   elif num2 > num1:
       print(f"O maior número é: {num2}")
   else:
       print("Os números são iguais.")
   ```

3. **Classificação de Nota**:
   - Solicite ao usuário uma nota (de 0 a 10) e informe se ele foi aprovado (nota maior ou igual a 7) ou reprovado.
   ```python
   nota = float(input("Digite sua nota: "))
   if nota >= 7:
       print("Aprovado!")
   else:
       print("Reprovado!")
   ```



6. **Sistema de Login Simples**:
   - Crie um programa que peça um nome de usuário e uma senha, e verifique se estão corretos (defina uma combinação correta nos códigos) para permitir o acesso.
   ```python
   usuario_correto = "admin"
   senha_correta = "1234"
   
   usuario = input("Digite o nome de usuário: ")
   senha = input("Digite a senha: ")
   
   if usuario == usuario_correto and senha == senha_correta:
       print("Acesso permitido.")
   else:
       print("Acesso negado.")
   ```