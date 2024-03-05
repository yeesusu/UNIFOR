
# UNIFOR
**Nome:** Suzani Jia Yi Wang
**Diciplina:** Raciocínio lógico algorítmico
## EXERXÍCIO 3
###  FLUXOGRAMA

```mermaid
flowchart TD
A([INICIO])-->B{{digite um número:}}
B-->C[\X\]
C-->D{X>=0}
D--sim-->E[rest=X/2]
D--não
-->F{{número negativo}}
F-->Z([FIM])
E-->G{rest==0}
G--não-->H{{X=impar}}
H-->Z
G--sim-->I{{x=par}}
I-->Z
```

