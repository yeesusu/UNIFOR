# unifor
## fluxograma
### exercício2.4

```mermaid
flowchart TD
A([início])-->B{{"digite o custo de fábrica do carro"}}
B-->C[/c/]
C-->D[d=c*12%]
D-->E[i=c*45%]
E-->F[s=c+d+i]
F-->G{{"o custo de fábrica do carro=c e imprima o custo ao consumidor=s"}}
G-->Z([Fim])
```
## peseudocódigo
```
ALGORIMO
ESCREVA"digite o custo de fábrica do carro"
DECLARE c
INÍCIO
d<--c*12%
i<--c*45%
s<--c+d+i
ESCREVA"o custo de fábrica do carro="c" e imprima o custo ao consumidor="s""
FIM_ALGORITMO
```
