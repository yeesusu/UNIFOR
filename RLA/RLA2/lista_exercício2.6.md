# UNIFOR
## FLUXOGRAMA
### EXERCÍCIO2.6
```mermaid
flowchart TD
A([início])-->B[/qhamb,qcheese,qfritas,qrefri,qmilk/]
B-->C{{"digite a quantidade de cada produto que consumiu"}}
C-->D["custo final=(qhamb*3)+(qcheese*2.5)+(qfritas*2.5)+(qrefri*1)+(qmilk*3)"]
D-->E{{"conta final é de"custo final}}
E-->Z([Fim])
```

```
ALGORITMO
DECLARE qhamb,qcheese,qfritas,qrefri,qmilk
INÍCIO
ESCREVA"digite a quantidade de cada produto que consumiu"
LEIA qhamb,qcheese,qfritas,qrefri,qmilk
custo final<-- (qhburg * 3) + (qchees * 2,50) + (qfritas * 2,50) + (qrefri * 1) + (qmilk * 3)
ESCREVA "conta final é de"custo final
FIM_ALGORITMO
