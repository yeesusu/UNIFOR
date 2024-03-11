# unifor
## fluxograma
### exercício2.11

```mermaid
flowchart TD
A([início])-->B[/x,q,c,rq,rc/]
B-->C{x>0}
C--sim-->D{{"digite o número"}}
D-->E["q=x^2"]
E-->F["c=x^3"]
F-->G["rq=x^(1/2)"]
G-->H["rc=x^(1/3)"]
H-->J{{"seguinte números são respectivamente em elevação ao quadrado, elevação ao cubo, em raiz ao quadrado, raiz ao cubo:"q, c, rq, rc}}
C--não-->I{{"número invalido!Tente novamente!"}}
J-->Z([Fim])
I-->Z
```

```
ALGORITMO
DECLARE x,q,c,rq,rc NÚMERICO
INÍCIO
SE x>0
ESCREVA "digite o número"
q<--x^2
c<--x^3
rq<--x^(1/2)
rc<--x^(1/3)
ESCREVA "seguinte números são respectivamente em elevação ao quadrado, elevação ao cubo, em raiz ao quadrado, raiz ao cubo:"q, c, rq, rc
SENÃO
ESCREVA "número invalido!Tente novamente!"
FIM_ALGORITMO

```
