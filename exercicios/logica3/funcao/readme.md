
## Sistema de correção de provas

Nesse exercício vamos simular um sistema de correção de provas e imprimir a quantidade de acertos com a nota da aluna.

**a)** Declare uma função de nome `corrigirProva` que tenha apenas um parâmetro chamado `prova`. 

**b)** Sabendo que o parâmetro `prova` será sempre um objeto com o seguinte formato:

```javascript=
const prova = {
    aluna: "May",
    materia: "Português",
    valor: 10,
    questoes: [
        {
            resposta: "a",
            correta: "b"
        },
        {
            resposta: "c",
            correta: "c"
        },
        {
            resposta: "e",
            correta: "b"
        },
        {
            resposta: "b",
            correta: "b"
        },
        {
            resposta: "c",
            correta: "c"
        }
    ]
}
```

Implemente a função `corrigirProva` de modo que, ao receber um objeto como este como parâmetro, o resultado seja o seguinte.

```
A aluna May acertou 3 questões e obteve nota 6
```

