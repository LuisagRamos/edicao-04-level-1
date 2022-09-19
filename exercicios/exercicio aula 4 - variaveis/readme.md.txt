#### _Exercício:_

Repare na variável `apresentacao` mostrada a seguir. Ela é uma `string` que representa um texto que pode mudar conforme o valor de outras variáveis.

Identifique e crie todas as variáveis necessárias para que o texto de `apresentacao` seja exibido sem erros. Depois, crie a variável `apresentacao` exatamente como mostrado a seguir e a imprima da seguinte forma: `console.log(apresentacao)`.

```javascript
apresentacao = "Meu nome é " + nomeCompleto + " (sou conhecido[a] como " + apelido + ") e tenho " + idade + " anos. Nasci no dia " + dataNascimento + ", na cidade de " + localNascimento + ". Tenho " + altura + "m de altura e atualmente estou " + (trabalhando ? "empregado" : "desempregado") + "."
```

Resolução
```

nomeCompleto = "Luisa Gabriele de Fraga Ramos"
apelido = "Luh"
idade = 26
dataNascimento = "10/10/1995"
localNascimento = "Igrejinha"
altura = 1.62
trabalhando = true


apresentacao = "Meu nome é " + nomeCompleto + " (sou conhecido[a] como " + apelido + ") e tenho " + idade + " anos. Nasci no dia " + dataNascimento + ", na cidade de " + localNascimento + ". Tenho " + altura + "m de altura e atualmente estou " + (trabalhando ? "empregado" : "desempregado") + "."

console.log (apresentacao)
``` 