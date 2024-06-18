# Atividade de Verificação de Número e Texto 🚀

![Imagem Ilustrativa](https://www.google.com.br/url?sa=i&url=https%3A%2F%2Farymax.org.br%2Finiciativa%2Freprograma%2F&psig=AOvVaw1282O5jrTTeUiysnJC349d&ust=1718767803738000&source=images&cd=vfe&opi=89978449&ved=0CBEQjRxqFwoTCIC8rYmb5IYDFQAAAAAdAAAAABAd)

Este código em Python realiza duas tarefas principais: verificar se um número inteiro é par ou ímpar e contar o número de caracteres em um texto.

#### Funcionalidades:

1. **Verificação de Par e impar**
   - A função `verificar_par_impar(numero)` verifica se um número inteiro é par ou ímpar.
   - Retorna "par" se o número for divisível por 2 e "ímpar" caso contrário.

2. **Contagem de Caracteres:**
   - A função `contar_caracteres(texto)` conta o número total de caracteres em uma string, excluindo espaços.
   - Utiliza `len(texto)` para contar todos os caracteres e `texto.count(" ")` para subtrair espaços em branco.

#### Uso do Script:

- O usuário é solicitado a inserir um número inteiro e um texto.
- Se o número não for inteiro e o texto contiver apenas dígitos, o script exibe uma mensagem de erro.
- Caso contrário, ele calcula e exibe se o número é par ou ímpar e o número de caracteres no texto.

#### Exemplos de Saída:

- **Exemplo 1 (Entrada Válida):**
- Digite um número inteiro: 7
- Digite um texto: Olá, mundo!
- O número 7 é ímpar. 😉
- O texto "Olá, mundo!" possui 10 caracteres. 📝

