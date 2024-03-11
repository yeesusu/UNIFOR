# unifor
## fluxograma
### exercício2.7

```mermaid
flowchart TD
A([início])-->B[/qcarro,valor_venda/]
B-->C{{"digite a quantidade de carros vendido"}}
C-->D["X=500+(qcarro*50)"]
D-->E{{"digite o valor_venda"}}
E-->F[salário=X+valor_venda]
F-->G{{"salário do vendedor é"salário}}
```
## pseudocódigo

```
ALGORITMO
DECLARE qcarro,valor_venda NÚMERICO
DECLARE nome
INÍCIO
ESCREVA"digite seu nome completo:"
LEIA nome
ESCREVA"digite a quantidade de carros vendido"
LEIA qcarro
X<--500+(qcarro*50)
ESCREVA"digite o valor_venda"
LEIA valor_venda
salário<--X+valor_venda
ESCREVA"salário do vendedor é"salário
FIM_ALGORITMO
```
