# Unifor raciocínio lógico algoritmico

## fluxugrama
### exercício 1

```mermaid 
flowchart TD
A([ínicio])-->B{{digite dois números}}
B-->C[/N1,N2,M/]
C-->D[soma=N1+N2]
D-->E[M=soma//2]
E-->F{M>=6}
F--sim-->G{{Aprovado!}}
F--não -->H{{Reprovado!}}
G-->I([fim])
H-->I([fim])
```
## pseudocódigo
```ALGORITMO 
DECLARE N1, N2, M NÚMERICO
ESCREVA "DIGITE DOIS NÚMEROS"
LEIA N1,N2
soma ⇐N1+N2
M=soma//2
ESCREVA "MÈDIA="M
SE M>=6
ENTÃO ESCREVA "APROVADO"
SENÃO ESCREVA "REPROVADO"
FIM_ALGARITMO
```


