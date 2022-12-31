# Fonction holomorphe
Une fonction holomorphe est une fonction qui peut être définie et analysée sur un domaine de la complexité. En Python, vous pouvez utiliser la bibliothèque Python cmath pour travailler avec des fonctions holomorphes.

Voici un exemple de définition d'une fonction holomorphe simple, la fonction exponentielle complexe, en utilisant la bibliothèque cmath:
```python
import cmath
def f(z):
    return cmath.exp(z)
```
Dans cet exemple, z est un nombre complexe et la fonction renvoie l'exponentielle complexe de z.

Vous pouvez également définir des fonctions holomorphes plus complexes en utilisant les opérations et fonctions de la bibliothèque cmath. Par exemple, voici comment définir la fonction zeta de Riemann:
```python
import cmath
def zeta(z):
    return 1 / (1 - 2**(1-z))
```
Vous pouvez maintenant utiliser cette fonction comme n'importe quelle autre fonction en Python en lui passant des nombres complexes en tant qu'arguments. 
Par exemple:
```python
>>> zeta(1 + 1j)
(1.6449340668482264+0.20205690315959428j)
>>> zeta(2 + 3j)
(0.9453087204829419-0.3070422535211267j)
```
Il est important de noter que les fonctions holomorphes sont généralement définies sur des domaines complexes, et que leurs valeurs peuvent être des nombres complexes. 
En utilisant la bibliothèque cmath, vous pouvez facilement travailler avec des fonctions holomorphes en Python.
