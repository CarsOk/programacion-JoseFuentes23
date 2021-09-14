# Septiembre 09 de 2021

En la clase de hoy seguimos trabajando la programación en los diferentes escenarios, aprendimos como hacer un programa que realice cálculos básicos. También aprendimos a cómo realizar o utilizar una nueva opción para el diagrama de flujo  "Manual input".

## Ejemplo Visual Basic

```
Sub ejemplo()
    a = InputBox("Digite primer numero")
    b = InputBox("Digite segundo numero")
    c = a + b
    MsgBox "La suma es " & c
End Sub
```

### Ejercicio en excel

```
Sub promedio()
    a = InputBox("Digite primer número")
    b = InputBox("Digite segundo número")
    c = InputBox("Digite tercer número")
    d = InputBox("Digite cuarto número")
    e = InputBox("Digite quinto número")
    f = Int(a) + Int(b) + Int(c) + Int(d) + Int(e)
    MsgBox "El promedio es " & f / 5
End Sub
```

#### Diagrama de flujo imagen

<img src="img/diagrama de flujo promedio.jpg" width="110">