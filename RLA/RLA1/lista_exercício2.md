# unifor
## fluxograma
### exercício_2

```mermaid 
flowchart TD
A([ínicio])-->B{{"digite o salario atual"}}
B-->C[/X/]
C-->D{X<=500}
D--sim-->E[S=X+X*20%]
D--não -->F[S=X+X*10%]
E-->G{{salario final==S}}
F-->G
G-->H([fim])
```

## pseudocódigo
```
ALGORITMO 
DECLARE X, S NUMÉRICO
ESCREVA "DIGITE O SALÁRIO ATUAL"
LEIA X
SE X<=500
ENTÃO S⇐X+(X*20%)
SENÃO S⇐X+(X*10% )
ESCREVA "SALÁRIO FINAL=" S
FIM_ALGORITMO.
```
