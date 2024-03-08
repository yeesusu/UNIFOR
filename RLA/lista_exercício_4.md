# unifor
## fluxograma
### exercício4

```mermaid
flowchart TD
A([início])-->B{{"digite a idade do candidato"}}
B-->C[/x/]
C-->D{x>=18}
D--sim-->E{{"candidato pode tirar CNH"}}
D--não -->F[F=18-X]
F-->G{{"falta F anos para o candidato poder tirar CNH"}}
E-->Z([fim])
G-->Z
```
## pseudocódigo
```
ALGORITMO
DECLARE X NUMÉRICO
ESCREVA"DIGITE A IDADE DO CANDIDATO"
LEIA X
SE X>=18
ENTÃO ESCREVA "PODE TIRAR CNH"
SENÃO F⇐18-X
ESCREVA "FALTAM"F"ANO(s) PARA PODER TIRAR CNH" 
FIM_ALGORITMO
```

