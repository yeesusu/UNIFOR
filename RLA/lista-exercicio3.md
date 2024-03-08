
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

### PSEDOCODIGO

``` Algoritmo verifica_par_ímpar
DECLARE X,R NUMERICO
ESCREVA "Digite um número inteiro:"
LEIA X
SE X >= 0 ENTAO
	R = X % 2
	SE R == 0 ENTAO
		ESCREVA"O X é par"
	SENAO
		ESCREVA "O X é ímpar"
SENAO 
	ESCREVA "O X é negativo"
FIM_ALGORITIMO ```
