# unifor
## fluxograma
### exercício2.4

```mermaid
flowchart TD
A([início])-->B{{"digite o custo de fábrica do carro"}}
B-->C[/c/]
C-->D["custo_total=c+(c*12%)+(c+45%)"]
D-->G{{"o custo ao consumidor é"custo_total}}
G-->Z([Fim])
```
## peseudocódigo
```
ALGORIMO calccusto
DECLARE c
ESCREVA"digite o custo de fábrica do carro"
LEIA c
INÍCIO
custo_total<--c+(c*12%)+(c*45%)
ESCREVA"o conta ao consumidor"custo_total
FIM_ALGORITMO
```
