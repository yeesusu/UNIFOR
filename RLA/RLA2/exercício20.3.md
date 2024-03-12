## fluxograma
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
