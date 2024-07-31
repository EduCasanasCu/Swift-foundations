# Swift-foundations
Bases del lenguaje swift para desarrollo de IOs
```swift
// Variables

// Variable que puede mutar o cambiar
var nombre = "educa"
// Variable que no se puede cambiar el valor
let sexo = "masculino"

// Tipo de datos

// Entero
var edad:Int = 30

// Double
var pi:Double = 3.1213141516
// 3.1213141516

// Float (ocupa menos espacio en memoria)
var radio:Float = 432.1213141516
// 432.1213

// Boolean
var esVerdad:Bool = true

// String
var apellido:String = "casanas"

// Interpolacion de cadenas
let name = "educa"
let age = 30
let greeting = "Buenas noches,"

// 1 forma
print(greeting, "Sr", name, "tienes", age, "años")

// 2 forma(recomendada)
print("\(greeting) Sr \(name), tienes \(age) años")

// Dato interesante: se puede almacenar en una variable
var mostrarSaludo = "\(greeting) Sr \(name), tienes \(age) años"
print(mostrarSaludo)

// Condicional - IF
var edadUser = 12
if(edadUser >= 18){
    print("Puede ingresar al bar!")
}else if(edadUser < 10){
    print("Necesitas llamar a tus padres")
}else{
    print("No tiene permiso para ingresar!")
}
```
