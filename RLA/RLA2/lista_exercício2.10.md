# unifor
## fluxograma
### exercício2.10

```mermaid
flowchart TD
A([início])-->B[/área, perímetro/]
B-->C{{"digite o raio  do círculo"}}
C-->D[área=Ⲡ * raio^2]
D-->E[perímetro= 2 * Ⲡ * raio]
E-->F{{"Área do círculo"área}}
F-->G{{"Perímetro do círculo"perímetro}}
G-->Z([Fim])
```

```
ALGORITMO calcarea e perimetro
DECLARE área, perímetro NÚMERICO
INÍCIO
ESCREVA "digite o raio  do círculo"
área<--Ⲡ * raio^2
perímetro<-- 2 * Ⲡ * raio
ESCREVA "Área do círculo"área
ESCREVA "Perímetro do círculo"perímetro
FIM_ALGORTIMO
```
