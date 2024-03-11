
# unifor
## fluxograma
### exercício2.2
```mermaid
flowchart TD
A([início ])-->B{{digite a temperatura em celsius}}
B-->C[/x/]
C-->D["F = (9/5 * C) + 32"]
D-->E{{"Temperatura em Fahrenheit é de"F}}
E-->Z([Fim])

```
## pesudograma
```
ALGORITMO calctemperatura
DECLARE C, F NÚMERICO
INÍCIO
ESCREVA "digite a temperatura em Celsius"
LEIA C
F<--(9/5*C)+32
ESCREVA "Temperatura em Fahrenheit é de" F
FIM_ALGORITMO```
