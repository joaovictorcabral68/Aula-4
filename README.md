# Validador de Maioridade
>O objetivo desse projeto é fazer um leitor de idade para um jogo, se o usuário for maior de 18 o acesso é permitido se não acesso negado

---

## Lógica utilizada 
1. O usuário entra no jogo
2. E oprograma faz a pergunta da data que ele nasceu
3. O programa lê essa data
4. Faz a comparação da data informada e a data atual
5. E dá a resposta
6. Se a comparação der maior ou 18 acesso liberado
7. Se não acesso negado

---

## Programa 

- **Variaveis:** `Inteiro` Usei essa variavel pois a entrada vai ser só de números inteiros, e para o usúario dar valor à ela.
- **Dados de entrada:** `Escreva/Leia` O comando escreva para dar as instruções e respostas para o usuário e o comando leia para "chamar" as variaveis.
- **Estrutura condicional:** `Se/Senão` Usei esses comandos para o programa entender as condições, para dar uma resposta positiva se atender as condições se não uma reposta negativa
- **Operadores:** `-,>=` Usei esses operadores para o programa fazer o cálculo, subtrair o ano atual e o ano de nascimento do usuário e identificar se o resultado é maior ou igual a 18 anos.

---

## Resultado
```Portugol
programa {
  funcao inicio() {
    inteiro data
    escreva("Esse jogo é para maiores de 18 anos\nQual o ano que você nasceu?:")
    leia(data) 
   se (2026-data >=18)
   escreva("Acessso Permitido")
   senao
   escreva("Acesso negado")
    
  }
}
```
---

# O Radar de Velocidade

## Objetivo
>O objetivo desse projeto era fazer uma leitura de velocidade, se o carro estivesse à mais de 80, aplica uma multa de 7$ por km, se não desejar uma boa viagem.

---

## Lógica Utilizada 

1. O programa precisa saber qual à velocidade do carro
2. O usuário informa
3. O programa fará a leitura da velocidade informada
4. O programa vai fazer a comparação da velocidade informada pelo usuário e a velocidade de entrada que é: 80km
5. Se passar de 80 o programa fará o cálculo de 7$ por km
6. Se não o programa vai informar "Boa viagem!" para informar que o condutor está liberado

---

## Programa

- **Variaveis:** `inteiro` usei as variaveis `vel` para o usuário dar valor à ela que no caso é a velocidade em que o veículo estava, e a `multa` que eu atribui o valor de 80km nela para fazer o cálculo.
- **Dados de entrada:** `Escreva/Leia` O comando escreva para dar as instruções e respostas para o usuário e o comando leia para "chamar" as variaveis.
- **Estrutura condicional:** `Se/Senão` Usei esses comandos para o programa entender as condições, para liberar o condutor se atender as condições se não faz o cálculo da multa.
- **Operadores:** `>,=,-,*` Usei o `=` para atribuições, o `>` para informar o programa que a velocidade tinha que ser maior à 80 para ele aplicar a multa, o `-` para subtrair o valor da velocidade permitida e a velocidade que o condutor passou, e a `*` para multiplicar o resultado da subtração por 7.

---

## Resultado

```Portugol
programa {
  funcao inicio() {
    inteiro vel, multa=80
   escreva("Qual a velocidade do condutor?:")
    leia(vel)
    se(vel>multa)
    escreva("O condutor deve pagar uma multa de ", (vel-multa)*7, "$")
    senao
    escreva("Boa Viagem!")
     }
}
```

---





