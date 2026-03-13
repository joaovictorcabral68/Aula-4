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

# Sistema de Aprovação Escolar

## Objetivo
> O objetivo desse projeto era criar um sistema que calculasse média de alunos na escola e se a nota fosse maior ou igual que 7.0 o aluno é aprovado, entre 6.9 e 5.0 ele fica de recuperação, menor que 5.0 é reporvado.

---

## Lógica Utilizada

1. O usuário recebe duas perguntas
2. Informa as duas notas separadamente
3. O programa lê essas duas notas
4. Faz o cálculo da media
5. E faz a leitura do resultado
6. Se o resultado for maior ou igual a 7 o programa vai escrever "Aprovado"
7. Se estiver entre 5.0 e 6.9 o programa vai escrever "Recuperação"
8. E se for menor que 5.0 o programa escreve "Reprovado"

---

## Programa

- **Variaveis:** `Real` usei a variavel `nota1` para o usuário preencher a primeira nota do aluno, a variavel `nota2`para preencher a segunda nota e a variavel `média` para ser preenchida com o resultado do cálculo.
- **Dados de entrada:** `Escreva/Leia` O comando escreva para dar as instruções e respostas para o usuário e o comando leia para "chamar" as variaveis.
- **Estrutura condicional:** `Se` Usei esse comando para separar as condições pedidas, e para cada resultado ele me da respostas diferentes.
- **Operadores:** `+,=,/,<=,>=,<` A soma `+` é aplicada nos dois números informados pelo usuário e logo em seguida é feita a divisão `/` para que o resultado seja a média do aluno, o igual `=` para fazer a atribuição do resultado para a variavel `media`, depois de fazer a leitura do resultado o programa me da uma resposta diferente se for `>=`à 7.0, `>=` à 5.0 e `<=` à 6.9 e `<` que 5.

---

## Resultado
```Portugol
programa {
  funcao inicio() {
    real nota1, nota2, media
    escreva("Qual foi a primeira nota do aluno?:")
    leia(nota1)
    escreva("Qual foi a segunda nota do aluno?:")
    leia(nota2)
    media=(nota1+nota2)/2
    escreva("A media do aluno foi: ", media)
    se (media>=7.0)
    escreva(" Aprovado!")
    se (media>=5.0 e media<=6.9)
    escreva(" Recuperação")
    se (media<5)
    escreva("Reprovado")
    

    
  }
}
```

---

# Par ou Ímpar?

## Objetivo
>O objetivo desse projeto é fazer a leitura de um número e informa se ele é par ou ímpar.

---
## Lógica utilizada

1. O usuário informa um número
2. O programa faz a leitura desse número
3. E ele faz uma divisão por 2
4. Se o resto dessa divisão for igual à 0
5. O programa escreve "Par"
6. Se nao
7. O programa escreve ímpar

---
## Programa

- **Variaveis:** `Inteiro` usei a variavel `num`para o usuário preencher com um número
- **Dados de entrada:** `Escreva/Leia` O comando escreva para dar as instruções e respostas para o usuário e o comando leia para "chamar" as variaveis.
- **Estrutura condicional:** `Se` Usei esse comando para separar as condições pedidas, e para cada resultado ele me da respostas diferentes.
- **Operadores:** `%,=`, usei esses doi operadores para informar ao programa que para um número ser par, o resto `%` de uma divisão por doi tem que ser igual `==` à 0.

---
## Resultado
```Portugol
programa {
  inteiro num

  funcao inicio() {
      escreva("Informe um número:")
      leia(num)
      se(num %2==0)
      escreva("Par")
      senao
      escreva("Ìmpar")
    
  }
}
```

---

# Analisador de Triângulos

## Objetivo
>O objetivo desse projeto é fazer a leitura de três números, e ver se eles podem formar um triângulo, Se sim, classifique em: - Equilátero: Todos os lados iguais. - Isósceles: Dois lados iguais. - Escaleno: Todos os lados diferentes.

---

## Lógica Utilizada 
1. O usuário tem que informar 3 números diferentes
2. O programa faz a leitura dos números
3. Se Todos os lados forem iguais o programa vai informar que é um triângulo equilatero
4. Se dois lados forem iguais o programa vai informar que é Isóceles
5. E se todos os lados forem diferentes o programa vai informar que é Escaleno

---

## Programa

- **Variaveis:** Usei as variaveis `Lado1/lado2/lado3` para o usuário dar valor à elas.
- **Dados de entrada:** `Escreva/Leia` O comando escreva para dar as instruções e respostas para o usuário e o comando leia para "chamar" as variaveis.
- **Estrutura condicional:** `Se/senao` Usei esse comando para separar as condições pedidas, e para cada resultado ele me da respostas diferentes, caso nao atenda nenhuma das condições o programa da uma resposta negativa.
- **Operadores:** `>,=,+` Usei esses operadores para informar ao programa que se a soma `+` das variaveis `lado1/lado2`for maior `>` que a variavel `lado3` é possivel formar um triângulo e se todos os lados fossem iguais `==` é triângulo equilátero, se dois lados forem iguais `==` é isóceles, e se nehum lado for igual é Escaleno.

---

## Resultado

```Portugol
programa {
    inteiro lado1, lado2, lado3
  funcao inicio() {
    
escreva("Qual o valor do primeiro lado?:")
leia(lado1)
escreva("Qual o valor do segundo lado?:")
leia(lado2)
escreva("Qual o valor do terceiro lado:")
leia(lado3) 
se(lado1+lado2>lado3){
escreva("Formando triângulo")
}
senao
escreva("Com esses valores não da para formar um triângulo")
se(lado1==lado2 e lado1==lado3 e lado3==lado1){
  escreva("\nTriângulo equilátero")
}
se(lado1==lado2 ou lado1==lado3 ou lado3==lado1){
  escreva("\nTriângulo Isóceles")
}
senao
escreva("\nTriângulo escaleno")
  }
}
```

---












