## FLUXOGRAMA
### 3.1

```mermaid
flowchart TD
A([início])-->B{{"digite um número aleatório"}}
B-->C[\x\]
C-->D{"x>0"}
D--V-->E{{"número escolhido é positivo"}}
E-->G[r=x%2]
G-->H{"r==0"}
H--sim-->I{{"o número escolhido é positivo e par."}}
H--não-->J{{"o número escolhido é positivo e ímpar."}}
I-->Z([FIM])
J-->Z
```

## PSEUDOCÓDIGO
```
ALGORITMO
ESCREVA "digite um número aleatório"
DECLARE x
INÍCIO
ENQUANTO x<0 FAÇA
	"digite um número."
FIM_ENQUANTO
ESCREVA "número escolhido é positivo"
r<--x%2
SE r==0
ESCREVA "o número escolhido é positivo e par."
SENÃO ESCREVA "o número escolhido é positivo e ímpar."
FIM_SE
FIM_ALGORITMO
```
