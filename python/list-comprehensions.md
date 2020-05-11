# List Comprehension

List Comprehension (Compreensão de listas) foi concebida na PEP 202 e é uma forma concisa de criar e manipular listas.
Sua sintaxe básica é:
~~~python
    [expr for item in lista]
~~~
**Exemplo:** dado o seguinte código:
~~~python
for item in range(10):
  lista.append(x**2)
~~~
Podemos reescrevê-lo, utilizando list comprehensions, da seguinte forma:
~~~python
lista = [item**2 for item in range(10)]
~~~

## Com condicional

Sua sintaxe básica é:
~~~python
[expr for item in lista if cond]
~~~

Exemplo: 
~~~python
resultado = [numero for numero in range(20) if numero % 2 == 0]
~~~
