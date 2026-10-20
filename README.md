# Experiência Prática I - Monitoramento do preço da cesta básica

Algoritmos e Pensamento Computacional

Pseudocódigo que lê nome, preço anterior e preço atual de 3 produtos e informa se houve aumento, redução ou manutenção do preço. Código em [pseudocodigo.txt](pseudocodigo.txt).

## Passos do algoritmo

1. Declarar as variáveis dos três produtos.
2. Ler nome, preço anterior e preço atual do produto 1.
3. Ler os mesmos dados do produto 2.
4. Ler os mesmos dados do produto 3.
5. Para cada produto, checar se o preço anterior é maior que zero.
6. Calcular a variação percentual: (atual - anterior) / anterior * 100.
7. Se a variação for positiva, exibir aumento; se negativa, redução; se zero, preço mantido.
8. Finalizar.

## Variáveis

| Variável | Tipo |
|---|---|
| nome1, nome2, nome3 | caractere |
| anterior1, anterior2, anterior3 | real |
| atual1, atual2, atual3 | real |
| variacao1, variacao2, variacao3 | real |
| situacao1, situacao2, situacao3 | caractere |

Preços e variação são `real` por serem valores monetários/fracionários.
