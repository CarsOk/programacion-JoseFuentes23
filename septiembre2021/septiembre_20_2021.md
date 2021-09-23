# Septiembre 20 de 2021

Funcion

## Ejercicio en VB

```
Private Sub btn_Registrar_Click()

        ActiveSheet.Cells(8, 1).Select
        Selection.EntireRow.Insert
           
            ActiveSheet.Cells(8, 1) = TextBox1
            ActiveSheet.Cells(8, 2) = TextBox2

            TextBox1 = Empty
            TextBox2 = Empty
            
            TextBox1.SetFocus
            
            Ordenar ' Esta es la llamada de nuestra macro para ordenar los registros
                         
End Sub
```

```
Private Sub btn_Finalizar_Click()
End
End Sub
```