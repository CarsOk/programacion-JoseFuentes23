# Septiembre 13 de 2021

## Ejercio en visual basic

Hacer un programa que calcule el promedio de 5 notas y le muestre un mensaje al usuario indicando si el estudiante gano o no la asignatura. En el colegio se califica hasta 10 y se aprueba con un 7.


```
Sub calcularpromedio()
    a = Int(InputBox("Escriba primera nota"))
    b = Int(InputBox("Escriba segunda nota"))
    c = Int(InputBox("Escriba tercera nota"))
    d = Int(InputBox("Escriba cuarta nota"))
    e = Int(InputBox("Escriba quinta nota"))
    f = a + b + c + d + e
    j = f / 5
    If (j < 7) Then
        MsgBox "El estudiante reprobó con " & j & " como nota final "
    Else
        MsgBox "El estudiante aprobó con " & j & " como nota final "
    End If
End Sub
```


### Ejercicio en dartpad

```
void main() {
  
  double a, b, c, d, e, suma, promedio;
  
  a = 5.5; 
  b = 6.4;
  c = 7.9;
  d = 5.5;
  e = 8.5;
  
  suma = a + b + c + d + e;
  promedio + suma / 5; 
  
  if (promedio > 7){
     print("aprobo");
  }else{
     print("reprobo");  
   } 

}
```