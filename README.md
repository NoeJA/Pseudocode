# Pseudocódigo
## Función: Calcular el mayor de dos números
Inputs:
Número A
Número B
Output: El número mayor entre A y B
1.	Si A>B:
Answer=A
2.	Si A<B:

Answer=B

3.	Cualquier otro resultado:
Asnwer=Error

## Determinar el mayor de tres números

Inputs:
Número A
Número B
Número C
Output: El número mayor entre A, B y C
  1.	Si A>B>C:
    Answer=A
  2.	Si B>A>C:
    Answer=B
  3. Si C>A>B:
    Answer= C
  4. Cualquier otro resultado:
    Answer= Inválido

## Determinar si un número es o no primo
Input:
A=Número

Output:
Verdadero o Falso

Contador=0
Para i en un rango=(1, longitud(A)+1):
  Si Residuo de división entera de A/i=0
  Contador+=1
 Retornar si contador==2


## Determinar si dos cadenas son palíndromas

Input:
S(string)

Output:
Versadero o falso
C= Cadena vacía
Para i en un rango=(longitud(S),0):
  C=C+S[i]
  
Retornar si C==S

## Determinar si “ant” es una subcadena de “Se han establecido antecedentes desde el sigo XIX”
Input:
string=“Se han establecido antecedentes desde el sigo XIX”
string1="ant"

Output:
Verdadero o falso

Retornar si string1 está/pertenece en string
