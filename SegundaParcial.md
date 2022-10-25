# Barajas Cortes Carlos Alejandro, Facultad de Ingenieria Mecanica y Electrica, carrera: Ingenieria en Computacion Inteligente, 1 semestre grupo B, Universidad de Colima (UDC)
## Problemas resueltos en clase con Diagramas de Flujo de Datos y sus correspondientes pseudocodigos
### Ejercicio 1. Contar del 1 hasta el numero 10 y sumar los valores en la forma for, while y do while
#### Forma For
[![1-ER-PROBLEMA-FOR.jpg](https://i.postimg.cc/tJnG84j4/1-ER-PROBLEMA-FOR.jpg)](https://postimg.cc/D4hNXF09)
#### Forma While
[![1-ER-PRBLEMA-WHILE.jpg](https://i.postimg.cc/ZYvqGTjN/1-ER-PRBLEMA-WHILE.jpg)](https://postimg.cc/Rq99fxkC)
#### Forma Do while
[![1-ER-PROBLEMA-DOWHILE.jpg](https://i.postimg.cc/hGGDpgff/1-ER-PROBLEMA-DOWHILE.jpg)](https://postimg.cc/PCBn5gbj)
#### Prueba de escritorio del diagrama en la forma for
[![prueba-1-for.jpg](https://i.postimg.cc/8CdRBRf1/prueba-1-for.jpg)](https://postimg.cc/wtvR9skP)
#### Prueba de escritorio de la forma while
[![Prueba-1-while.jpg](https://i.postimg.cc/hjdf1g5V/Prueba-1-while.jpg)](https://postimg.cc/XGnjVM3v)
#### Prueba de escritorio de la forma do while
[![PRUEBA-1-DO-WHILE.jpg](https://i.postimg.cc/tgnQmgtv/PRUEBA-1-DO-WHILE.jpg)](https://postimg.cc/2qYK1rtn)
#### Pseudocodigo en forma for
```dart
// Contar del 1 hasta el 10 y sumar los valores.

void main(List<String> args) {
  int s = 0;
  for (var i = 1; i <= 10; i++) {
    s += i;
  }
  print("La suma de los valores es: $s");
}//for
```
#### Pseudocodigo en forma while
```dart
// Contar del 1 hasta el 10 y sumar los valores.
void main(List<String> args) {
  int s = 0, c = 1;

  while (c <= 10) {
    s += c;
    c++;
  }
  print("El resultado de la suma de los valores es:$s");
} //while
```
#### Pseudocodigo en forma Do while
```dart
// Contar del 1 hasta el 10 y sumar los valores.
void main(List<String> args) {
  int s = 0, c = 1;

  do {
    s += c;
    c++;
  } while (c <= 10);
  print("El resultado de la suma de los valores es:$s");
}//Do while
```
### Ejercicio 2. Obtenga la suma de los primeros 5 numeros pares 
#### Forma For
[![2-DO-PROBLEMA-FOR.jpg](https://i.postimg.cc/rwVtWD24/2-DO-PROBLEMA-FOR.jpg)](https://postimg.cc/xcZCVTCj)
#### Forma while
[![2-DO-PROBLEMA-WHILE.jpg](https://i.postimg.cc/1zNRNSX6/2-DO-PROBLEMA-WHILE.jpg)](https://postimg.cc/XZ46TTw7)
#### Forma do while
[![2-DO-PROBLEMA-DO-WHILE.jpg](https://i.postimg.cc/GmwX1JYC/2-DO-PROBLEMA-DO-WHILE.jpg)](https://postimg.cc/hfsLLmpy)
#### Prueba de escritorio de la forma for
[![prueba-2-for.jpg](https://i.postimg.cc/FKjyg2nd/prueba-2-for.jpg)](https://postimg.cc/SXxYmt4k)
#### Prueba de escritorio de la forma while
[![prueba-2-forma-while.jpg](https://i.postimg.cc/T3yRf2jg/prueba-2-forma-while.jpg)](https://postimg.cc/MnSkYSFp)
#### Prueba de escritorio en la forma do while
[![prueba-2-do-while.jpg](https://i.postimg.cc/MHx7Jrhf/prueba-2-do-while.jpg)](https://postimg.cc/cg9gQT1d)
#### Pseudocodigo en la forma for
```dart
void main(List<String> args) {
  int s = 0;
  for (var i = 2; i <= 10; i = i + 2) {
    s = s + i;
  }
  print("resultado de la suma de numeros pares es:$s");
} //For
```
#### Pseudocodigo de la forma while
```dart
void main(List<String> args) {
  int s = 0, c = 1;
  while (c <= 5) {
    s = s + c * 2;
    c = c + 1;
  }
  print("resultado de la suma de numeros pares:$s");
} //While
```
#### Pseudocodigo en forma do while
```dart

void main(List<String> args) {
  int s = 0, c = 1;

  do {
    s = s + c * 2;
    c = c + 1;
  } while (c <= 5);
  print("la suma de numeros pares es:$s");
} //Do While
```
### Ejercicio 3. Almacene en un array el numero n leeido del teclado, el array es de tamaño 10
#### Diagrama de flujo en forma for
[![3-ER-PROBLEMA-FOR.jpg](https://i.postimg.cc/rFz6r8nm/3-ER-PROBLEMA-FOR.jpg)](https://postimg.cc/hfF3FqqW)
#### Diagrama de flujo en la forma while
[![3-ER-PROBLEMA-WHILE.jpg](https://i.postimg.cc/W45C3CGr/3-ER-PROBLEMA-WHILE.jpg)](https://postimg.cc/06JcXtH2)
#### Diagrama de flujo en forma Do while
[![3-ER-PROBLEMA-DOWHILE.jpg](https://i.postimg.cc/HnDqD50P/3-ER-PROBLEMA-DOWHILE.jpg)](https://postimg.cc/sQm65MNp)
#### Prueba de escritorio del diagrama en forma for
[![prueba-3-forma-for.jpg](https://i.postimg.cc/SQcsXfPR/prueba-3-forma-for.jpg)](https://postimg.cc/yWYBtcsC)
#### Prueba de escritorio del diagrama en forma while
[![prueba-3-forma-while.jpg](https://i.postimg.cc/YS4FTmCF/prueba-3-forma-while.jpg)](https://postimg.cc/CZgdq5DM)
#### Prueba de escritorio del diagrama en forma do-while
[![prueba-3-en-forma-do-while.jpg](https://i.postimg.cc/tJ9N0CfH/prueba-3-en-forma-do-while.jpg)](https://postimg.cc/FdnL3mNP)
#### Pseudocodigo en el lenguaje de programacion dart en la forma for
```dart
import 'dart:io';

//Leer 10 numeros del teclado y ponerlos en una lista.
void main() {
  var arra = new List.filled(10, 0);
  stdout.write("Dame diez numeros\n ");
  stdout.write("----------\n");
  for (var i = 0; i <= 9; i++) {
    String? s = stdin.readLineSync();
    if (s != null) {
      int n = int.parse(s);
      arra[i] = n;
    }
  }
  stdout.write("aqui esta la lista, $arra");
}
```
#### Pseudocodigo en el lenguaje de programacion dart en la forma while
```dart
import 'dart:io';

//Leer 10 numeros del teclado y ponerlos en una lista.
void main() {
  var arra = new List.filled(10, 0);
  stdout.write("Dame diez numeros\n ");
  stdout.write("----------\n");
  int i = 0;
  while (i <= 9) {
    String? s = stdin.readLineSync();
    if (s != null) {
      int ner = int.parse(s);
      arra[i] = ner;
    }
    i++;
  }
  stdout.write("Tu lista es, $arra ");
}
```
#### Pseudocodigo en lenguaje de programacion dart en forma do-while
```dart
import 'dart:io';

void main() {
  var arra = new List.filled(10, 0);
  stdout.write("Dame diez numeros\n ");
  stdout.write("----------\n");
  int i = 0;
  do {
    String? s = stdin.readLineSync();
    if (s != null) {
      int n = int.parse(s);
      arra[i] = n;
      i++;
    }
  } while (i <= 9);
  stdout.write("Tu lista es $arra ");
}
```
### Ejercicio 4. Almacene los n numeros leeidos del teclado en un vector de 10 elementos
#### Diagrama de flujo en la forma for
[![4-TP-PROBLEMA-FOR.jpg](https://i.postimg.cc/d0CJpGgg/4-TP-PROBLEMA-FOR.jpg)](https://postimg.cc/5HxcFQ4m)
#### Diagrama de flujo en la forma while
[![4-TP-PROBLEMA-WHILE.jpg](https://i.postimg.cc/3RKJGdb6/4-TP-PROBLEMA-WHILE.jpg)](https://postimg.cc/PLRjsrHz)
#### Diagrama de flujo en la forma do-while
[![4-TP-PROBLEMA-DOWHILE.jpg](https://i.postimg.cc/x8mfDMkX/4-TP-PROBLEMA-DOWHILE.jpg)](https://postimg.cc/RJM5w3Lm)
#### Prueba de escritorio del diagrama de flujo en forma for
[![prueba-4-forma-for.jpg](https://i.postimg.cc/5Nkhq6jG/prueba-4-forma-for.jpg)](https://postimg.cc/D8Lp7frd)
#### Prueba de escritorio del diagrama de flujo en la forma while
[![prueba-4-forma-while.jpg](https://i.postimg.cc/tTSkQV0G/prueba-4-forma-while.jpg)](https://postimg.cc/CB8kb5Lc)
#### Prueba de escritorio del diagrama de flujo de la forma do-while
[![prueba-4-forma-do-while.jpg](https://i.postimg.cc/ry5bRfLD/prueba-4-forma-do-while.jpg)](https://postimg.cc/0r2ZLdjv)
#### Pseudocodigo del diagrama de flujo en forma for en lenguaje dart
```dart
import 'dart:io';
dart
//Leer 10 numeros del teclado y ponerlos en una lista.
void main() {
  var arra = new List.filled(10, 0);
  stdout.write("Dame diez numeros\n ");
  stdout.write("----------\n");
  for (var i = 0; i <= 9; i++) {
    String? s = stdin.readLineSync();
    if (s != null) {
      int n = int.parse(s);
      arra[i] = n;
    }
  }
  stdout.write("aqui esta la lista, $arra");
}
```
#### Pseudocodigo del diagrama de flujo en forma while en lenguaje dart
```dar
import 'dart:io';

//Leer 10 numeros del teclado y ponerlos en una lista.
void main() {
  var arra = new List.filled(10, 0);
  stdout.write("Dame diez numeros\n ");
  stdout.write("----------\n");
  int i = 0;
  while (i <= 9) {
    String? s = stdin.readLineSync();
    if (s != null) {
      int ner = int.parse(s);
      arra[i] = ner;
    }
    i++;
  }
  stdout.write("Tu lista es, $arra ");
}
```
#### Pseudocodigo del diagrama de flujo en lenguaje dart en la forma do-while
```dart
import 'dart:io';

void main() {
  var arra = new List.filled(10, 0);
  stdout.write("Dame diez numeros\n ");
  stdout.write("----------\n");
  int i = 0;
  do {
    String? s = stdin.readLineSync();
    if (s != null) {
      int n = int.parse(s);
      arra[i] = n;
      i++;
    }
  } while (i <= 9);
  stdout.write("Tu lista es $arra ");
}
```
### Ejercicio 5. Almacene un contador negativo en un vector. El conteo es de 10 a 0
#### Diagrama de flujo con el ciclo for
[![5-TO-PROBLEMA-FOR.jpg](https://i.postimg.cc/qqDYkMFW/5-TO-PROBLEMA-FOR.jpg)](https://postimg.cc/MfRt5xqY)
#### Diagrama de flujo con el ciclo while
[![5-TO-PROBLEMA-WHILE.jpg](https://i.postimg.cc/3JPS96Qj/5-TO-PROBLEMA-WHILE.jpg)](https://postimg.cc/ykyy8LdW)
#### Diagrama de flujo con el ciclo do-while
[![5-TO-PROBLEMA-DOWHILE.jpg](https://i.postimg.cc/Pf09FNm8/5-TO-PROBLEMA-DOWHILE.jpg)](https://postimg.cc/mhNmPLpb)
#### Prueba de escritorio del diagrama con ciclo for
[![prueba-5-for.jpg](https://i.postimg.cc/KzbcSJXC/prueba-5-for.jpg)](https://postimg.cc/Tykvnj3c)
#### Prueba de escritorio del diagrama con ciclo while
[![prueba-5-forma-while.jpg](https://i.postimg.cc/cLfVyZs4/prueba-5-forma-while.jpg)](https://postimg.cc/BjQhHrLd)
#### Prueba de escritorio del diagrama con ciclo do-while
[![prueba-5-forma-do-while.jpg](https://i.postimg.cc/26dQrc1W/prueba-5-forma-do-while.jpg)](https://postimg.cc/8J5JbbBk)
#### Pseudocodigo del diagrama de flujo en lenguaje dart con ciclo for
```dart
//Almacene un contador negativo en un vector, el conteo es de 10 a 0.

void main() {
  var arr = <int>[0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
  for (var i = 10; i >= 0; i--) {
    arr[10 - i] = i;
  }
  print(arr);
}//For
```
#### Pseudocodigo del diagrama de flujo en lenguaje dart con ciclo while
```dart
//Almacene un contador negativo en un vector, el conteo es de 10 a 0.
void main() {
  var arr = <int>[0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
  int c = 10;
  while (c >= 0) {
    arr[10 - c] = c;
    c = c - 1;
  }
  print(arr);
}//While
```
#### Pseudocodigo del diagrama de flujo en lenguaje dart en ciclo do-while
```dart
//Almacene un contador negativo en un vector, el conteo es de 10 a 0.
void main() {
  var arr = <int>[0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
  int c = 10;
  do {
    arr[10 - c] = c;
    c = c - 1;
  } while (c >= 0);
  print(arr);
}//dowhile
```
### Ejercicio 6. Almacene en un vector de tamaño 10 todos los numeros pares capturados hasta completar 10
#### Diagrama de flujo con el ciclo for
[![6-TO-PROBLEMA-FOR.jpg](https://i.postimg.cc/zGZqg8pT/6-TO-PROBLEMA-FOR.jpg)](https://postimg.cc/LnDdddcs)
#### Diagrama de flujo con el ciclo while
[![6-TO-PROBLEMA-WHILE.jpg](https://i.postimg.cc/7bvr0n1q/6-TO-PROBLEMA-WHILE.jpg)](https://postimg.cc/N2xnwTPn)
#### Diagrama de flujo con el ciclo do-while
[![6-TO-PROBLEMA-DOWHILE.jpg](https://i.postimg.cc/hG4vXKPp/6-TO-PROBLEMA-DOWHILE.jpg)](https://postimg.cc/Mn4q42BQ)
#### Prueba de escritorio del diagrama de flujo con el ciclo for
[![prueba-6-for.jpg](https://i.postimg.cc/fT64JsDm/prueba-6-for.jpg)](https://postimg.cc/PPzVRBL5)
#### Prueba de escritorio del diagrama de flujo con el ciclo while
[![prueba-6-while.jpg](https://i.postimg.cc/wvVC4sKd/prueba-6-while.jpg)](https://postimg.cc/Q9FYHCx6)
#### Prueba de escritorio del diagrama de flujo con el ciclo do-while
[![prueba-6-dowhile.jpg](https://i.postimg.cc/v8XzTtLs/prueba-6-dowhile.jpg)](https://postimg.cc/WtFrfrHW)
#### Pseudocodigo del siagrama con el ciclo for en lenguaje python
```python
#almacenar en un vector de tamaño 10 todos los numeros pares hasta completar todos
numeros = [2, 4, 6, 8, 10, 12, 14, 16, 18, 20]



def extraer_pares(lista):
    pares = []

    for n in lista:
        if n % 2 == 0:
            pares.append👎

    return pares

print()

resultado = extraer_pares(numeros)

print("Contenido de la variable`resultado`:", resultado)
print("Cantidad de elementos en la lista `resultado`:", len(resultado))
```
#### Pseudocodigo del diagrama de flujo con el ciclo while en lenguaje python
```python
numeros = [2, 4, 6, 8, 10, 12, 14, 16, 18, 20]

print("Contenido de la variable`numeros`:", numeros)
print("Cantidad de elementos en la lista `numeros`:", len(numeros))

def extraer_pares(lista):
    pares = []

    while(true):
        if n % 2 == 0:
            pares.append👎

    return pares

print()



print("Contenido de la variable`resultado`:", resultado)
print("Cantidad de elementos en la lista `resultado`:", len(resultado))
```
#### Pseudocodigo del diagrama de flujo con ciclo simulado de do-while en lenguaje dart
```dart
//Almacene en un vector de tamaño 10 todos los numeros pares capturados hasta completar todos DoWhile
import 'dart:io';
import 'dart:async';

void main() {
  var array = [];
  var c = 0;
  do {
    int n = int.parse(stdin.readLineSync()!);

    if (n % 2 == 0) {
      array.add(n);
      c = c + 1;
    }
  } while (c <= 9);
  print(array);
}
```
### Ejercicio 7. Obten el promedio de las calificaciones aprobatorias y la cantidad de alumnos reprobados. La calificacion entre 0 y 10 y el maximo de alumnos es de 15
#### Diagrama de flujo con el ciclo for
[![7-MO-PROBLEMA-FOR.jpg](https://i.postimg.cc/4dtXw1Z2/7-MO-PROBLEMA-FOR.jpg)](https://postimg.cc/phWNLzmK)
#### Diagrama de flujo con el ciclo while
[![7-MO-PROBLEMA-WHILE.jpg](https://i.postimg.cc/qMFZMH2n/7-MO-PROBLEMA-WHILE.jpg)](https://postimg.cc/4mz1BMLN)
#### Diagrama de flujo con el ciclo do-while
[![7-MO-PROBLEMA-DOWHILE.jpg](https://i.postimg.cc/6pNnhHXg/7-MO-PROBLEMA-DOWHILE.jpg)](https://postimg.cc/bs3Zy9d9)
#### Prueba de escritorio del diagrama de flujo con ciclo for
[![prueba7-for.jpg](https://i.postimg.cc/jSVYScgS/prueba7-for.jpg)](https://postimg.cc/qzG5msHP)
#### Prueba de escritorio del diagrama de flujo con ciclo while
[![prueba-7-while.jpg](https://i.postimg.cc/FKXf3wpd/prueba-7-while.jpg)](https://postimg.cc/QFSxr4Rh)
#### Prueba de escritorio del diagrama de flujo con ciclo do-while
[![PRUEBA-7-DOWHILE.jpg](https://i.postimg.cc/pVmq0Fxf/PRUEBA-7-DOWHILE.jpg)](https://postimg.cc/23fQy31y)
#### Pseudocodigo del diagframa de flujo en lenguaje de prorgamacion python con cliclo for
```python
alumnos = list(range(15))
p_aprobados = 0
j = 0

for i in alumnos: 
    while(True):
        calificacion = int(input("Ingresa la calificación >>"))
        if (calificacion >= 0 and calificacion <= 10):
            break
        else:
            print("Calificación fuera de rango. Intenta de nuevo")
 
    if (calificacion < 6):
     alumnos[i] = "R"
    else:
     p_aprobados = calificacion + p_aprobados
     j = j + 1
     alumnos[i] = "A"

print("\033[33;1m",alumnos,"\033[39m")
print("El promedio de calificación de los aprobados es de >>",round(p_aprobados/j,2))
print("El total de aprobados fueron >> ",j)
print("El total de reprobados fueron >> ",(len(alumnos)-j))
```
#### Pseudocodigo del diagrama de flujo en lenguaje de programacion python usando el ciclo while
```python
alumnos = list(range(15))
p_aprobados = 0
j = 0

for i in alumnos: 
    while(True):
        calificacion = int(input("Ingresa la calificación >>"))
        if (calificacion >= 0 and calificacion <= 10):
            break
        else:
            print("Calificación fuera de rango. Intenta de nuevo")
 
    if (calificacion < 6):
     alumnos[i] = "R"
    else:
     p_aprobados = calificacion + p_aprobados
     j = j + 1
     alumnos[i] = "A"

print("\033[33;1m",alumnos,"\033[39m")
print("El promedio de calificación de los aprobados es de >>",round(p_aprobados/j,2))
print("El total de aprobados fueron >> ",j)
print("El total de reprobados fueron >> ",(len(alumnos)-j))
```
#### Pseudocodigo del diagrama de flujo en lenguaje de programacion dart usando un cilo do-while
```dart
//calcule calificaciones de maximo 15 alumnos, saque promedio de aprobados, cuantos reprobaron y la calificacion mas alta. Dowhile
import 'dart:io';
import 'dart:async';

void main() {
  double PromA = 0;
  var contr = 0;
  double sumaA = 0;
  double contA = 0;
  double cal1 = 0;
  double cal2 = 1;
  var cont = 0;
  stdout.write("Dame las calificaciones\n ");
  stdout.write("----------\n");
  do {
    double c = double.parse(stdin.readLineSync()!);
    cont = cont +1;
    if (c > 10) {
      print('La calificacion no puede ser mayor a 10');
      cont = cont - 1;
    }
    if (c < 0) {
      print('La calificacion no puede ser menor a 0');
      cont = cont - 1;
    }
    if (c < 6 && c > 0) {
      contr = contr + 1;
    }
    if (c <= 10 && c >= 6) {
      cal1 = c;
      sumaA = sumaA + cal1;
      contA++;
    }
    if (cal1 > cal2) {
      cal2 = cal1;
    }
  } while (cont <= 14);
  PromA = sumaA / contA;
  print('El promedio de aprobados es $PromA');
  print('La calificacion mas alta es $cal2');
  print('La cantidad de reprobados son $contr');
}
```
### Ejercicio 8. Capture n numeros en el rango[Li,Ls], donde Li sea el limite inferior y Ls el limite superior para Li<Ls y Li>0. Obtenga cantidad de numeros pares y promedio, cantidad de impares y su promedio y que promedio es mayor
#### Diagrama en de flujo con ciclo for
[![8-For.jpg](https://i.postimg.cc/gk4g0FVD/8-For.jpg)](https://postimg.cc/9rRdxkNR)
#### Diagrama de flujo con ciclo while
[![Whats-App-Image-2022-10-23-at-10-38-33-PM.jpg](https://i.postimg.cc/L5LGWywW/Whats-App-Image-2022-10-23-at-10-38-33-PM.jpg)](https://postimg.cc/N2GN9xg8)
#### Diagrama de flujo con cliclo do-while
[![Whats-App-Image-2022-10-23-at-10-38-33-PM-1.jpg](https://i.postimg.cc/vmTky8Cf/Whats-App-Image-2022-10-23-at-10-38-33-PM-1.jpg)](https://postimg.cc/67sYLKWp)
#### Prueba de escritorio del diagrama de flujo con ciclo for
[![PRUEBA-8-FORMA-FOR.jpg](https://i.postimg.cc/CM4jYCYT/PRUEBA-8-FORMA-FOR.jpg)](https://postimg.cc/G9HBxyHq)
#### Prueba de escritorio del diagrama de flujo con ciclo while
[![prueba-8-while.jpg](https://i.postimg.cc/HLCwd6Jm/prueba-8-while.jpg)](https://postimg.cc/MndMYbb3)
#### Prueba de escritorio del diagrama de flujo con el ciclo do-while
[![PRUEBA-8-DOWHILE.jpg](https://i.postimg.cc/BvrQdzt5/PRUEBA-8-DOWHILE.jpg)](https://postimg.cc/Tyc6bCVh)
#### Pseudocodigo del diagrama de flujo en lenguaje python usando el ciclo for
```python
p=0
cp=0
pp=0
si=0
ci=0
pi=0
li=-1
ls=-1
n=-1
num=-1

while(li<0):
    li = int(input("Limite inferior: "))
    
    if(li<0):
        print("Tiene que ser mayor a 0")
        
while(ls<li):
    ls = int(input("Limite superior: "))
    
    if(ls<li):
        print("Tiene que ser mayor que el limite inferior")
        
while(n<0):
    n = int(input("¿Cuantos numeros? "))
    
    if(n<0):
        print("Tiene que ser mayor a 0")
    
for i in range(n): 
    while(num<=li or num>=ls):
        num = int(input("Dame un numero de LI y LS: "))
        
        if(num<=li or num>=ls):
            print("Tiene que estar dentro del LI al LS")

    if(num%2==0):
        sp=sp+num
        cp=cp+1
    else:
        si=si+num
        ci=ci+1
        
    num=-1       
         
if(sp==0 or cp==0):
    pp=0
else:
    pp=sp/cp
    
if(si==0 or ci==0):
    pi=0
else:
    pi=si/ci
    
if(pp>pi):
    print("El PP es mayor que el PI")
else:
    print("El PI es mayor que el PP")
```
#### Pseudocodigo del diagrama de flujo en lenguaje python utilizando un ciclo en while
```python
# Capture n números en el rango [Li,Ls] donde: 
# -Li = Limite inferior
# -Ls limite superior para li<ls y li>0
#                  Obtenga:
# - Cantidad de números pares y su promedio
# - Cantidad de números impares y su promedio
# - ¿Qué promedio es mayor?

print("Dame Límite inferior: ")
Li = int(input())
while Li<0:
    print("El límite inferior debe ser mayor a 0")
    print("Dame Límite inferior: ")
    Li = int(input())

print("Dame límite superior: ")
Ls = int(input())
while Ls<=Li:
    print("El límite superior no puede ser menor o igual al limite inferior")
    print("Dame límite superior: ")
    Ls = int(input())

pares = 0
impares = 0

lista=[]
for x in range(10):
    valor=int(input("Ingrese un valor entero: "))
    lista.append(valor)
print(lista)

for a in lista:
    if a % 2 == 0:
        pares = pares + a
    else:
        impares = impares + a
print("La suma de los números pares es: ",pares)
print("La suma de los números impares es: ",impares)

prom_pares = pares / a
prom_impares = impares / a

print("El promedio de los números pares es: ",prom_pares)
print("El promedio de los números impares es: ",prom_impares)

if prom_pares > prom_impares:
    print("El promedio de los pares es mayor que el promedio de los impares.")
else:
    print("El promedio de los números impares es mayor que el promedio de los pares.")
```
#### Pseudocodico del diagrama de flujo en lengauje de programacion dart utilizando un ciclo do-while
```dart
/*capture N numeros en el rango [Li,Ls] donde:
Li=Limite inferior
Ls=Limite superior para Li<Ls y Li>0
obtenga:
-cantidad de numeros pares y su promedio
-cantidad de numeros impares y su promedio
-que promedio es mayo?*/

import 'dart:io';

void main() {
  double sumap = 0;
  double sumai = 0;
  var contp = 0;
  var conti = 0;
  double promp = 0;
  double promi = 0;
  print('Introduce el limite inferior, mayor a 0');
  var li = int.parse(stdin.readLineSync()!);
  if (li < 0) {
    print('tu limite inferior debe ser mayor a 0');
  }
  if (li > 0) {
    print('Ahora introduce un limite superior');
    var ls = int.parse(stdin.readLineSync()!);
    if (ls < li) {
      print('tu limite superior debe ser mayor a tu limite inferior');
    }
    var cont = li;
    do {
      if (cont <= ls) {
        sumai = sumai + cont;
        conti = conti + 1;
      }
      if (cont % 2 == 0) {
        sumap = sumap + cont;
        contp = contp + 1;
        sumai = sumai - cont;
        conti = conti - 1;
      }
      cont = cont + 1;
    } while (cont <= ls);

    promi = sumai / conti;
    print('los impares son $conti y su promedio es $promi');
    promp = sumap / contp;
    print('los pares son $contp y su promedio es $promp');
    if (promp < promi) {
      print('$promi es mayor');
    }
    if (promp > promi) {
      print('el promedio $promp es mayor');
    }
  }
}
```
### Ejercicio 9. Obtener la frecuencia de n calificaciones entre 1 y 10, indique la cantidad de aprobados, la cantidad de reprobados, el promedio de las calificaciones aprobadas y el promedio general
#### Diagrama de flujo utilizando el ciclo for
[![Whats-App-Image-2022-10-24-at-7-05-29-PM.jpg](https://i.postimg.cc/DfBmzBNh/Whats-App-Image-2022-10-24-at-7-05-29-PM.jpg)](https://postimg.cc/Z0vJ7FZs)
#### Diagrama de flujo utilizando el ciclo while
[![Whats-App-Image-2022-10-23-at-10-38-33-PM-2.jpg](https://i.postimg.cc/50H1NSQ4/Whats-App-Image-2022-10-23-at-10-38-33-PM-2.jpg)](https://postimg.cc/LYMGxfVw)
#### Diagrama de flujo utilizando un ciclo do-while
[![Whats-App-Image-2022-10-23-at-10-38-33-PM-3.jpg](https://i.postimg.cc/HWQR0NmG/Whats-App-Image-2022-10-23-at-10-38-33-PM-3.jpg)](https://postimg.cc/Z05w4V0j)
#### Prueba de escritorio del diagrama de flujo que utilizo un ciclo for
[![prueba-9-for.jpg](https://i.postimg.cc/T2sMQ4NC/prueba-9-for.jpg)](https://postimg.cc/dDGxV4Yy)
#### Prueba de escritorio del diagrama de flujo que utilizo un ciclo while
[![prueba-9-while.jpg](https://i.postimg.cc/P5Tj88Rj/prueba-9-while.jpg)](https://postimg.cc/4mLMDnGL)
#### Prueba de escritorio del diagrama de flujo que utilizo un ciclo do-while
[![prueba-9-do-while.jpg](https://i.postimg.cc/QtrkXhM0/prueba-9-do-while.jpg)](https://postimg.cc/7CmT9v02)
#### Pseudocodigo del diagrama de flujo en lenguaje python utilizando un ciclo for
```python
Calificaciones=int(input("Ingrese la cantidad de calificaciones"))
vec=[]
n=0

for i in range(1,Calificaciones+1):
    calificacion=int(input("Calificacion: "))
    n=n+calificacion
    vec.append(calificacion)

promedio=n/len(vec)

npromedio=0
for j in vec:
    if j>promedio:
        npromedio=npromedio+1

aprobado=0

#Primero inicializas el contador
promedioAprobados = 0
for h in vec:
    if h>5:
        aprobado=aprobado+1
        #Va sumando cada unas de las notas
        promedioAprobados = promedioAprobados + h

#Luego saca el promedio sumatoria / cantidad de aprobados 
promedioAprobados = promedioAprobados / aprobado

reprobado=0
for k in vec:
    if k<5:
        reprobado=reprobado+1

print("Max Calificacion", max(vec))
print("Min calificacion", min(vec))
print("Promedio:", promedio)
print("Superiores a promedio:", npromedio)
print("Cantidad de aprobados:", aprobado)
print("Promedio de aprobados:", promedioAprobados)
print("Desaprobados:", reprobado)
```
#### Pseudocodigo del diagrama de flujo en lenguaje python utilizando un ciclo while
```python
Calificaciones=int(input("Ingrese la cantidad de calificaciones"))
vec=[]
n=0
cont = 0
while(cont < Calificaciones):
    calificacion=int(input("Calificacion: "))
    n=n+calificacion
    vec.append(calificacion)
    cont += 1

promedio=n/len(vec)

npromedio=0
for j in vec:
    if j>promedio:
        npromedio=npromedio+1

aprobado=0

#Primero inicializas el contador
promedioAprobados = 0
for h in vec:
    if h>5:
        aprobado=aprobado+1
        #Va sumando cada unas de las notas
        promedioAprobados = promedioAprobados + h

#Luego saca el promedio sumatoria / cantidad de aprobados 
promedioAprobados = promedioAprobados / aprobado

reprobado=0
for k in vec:
    if k<5:
        reprobado=reprobado+1

print("Max Calificacion", max(vec))
print("Min calificacion", min(vec))
print("Promedio:", promedio)
print("Superiores a promedio:", npromedio)
print("Cantidad de aprobados:", aprobado)
print("Promedio de aprobados:", promedioAprobados)
print("Desaprobados:", reprobado)
```
#### Pseudocodigo del diagrama de flujo en lenguaje python simulando un ciclo do-while
```python
Calificaciones=int(input("Ingrese la cantidad de calificaciones"))
vec=[]
n=0

cont = 0
while(True):
    calificacion=int(input("Calificacion: "))
    n=n+calificacion
    vec.append(calificacion)
    cont += 1
    if(cont>=Calificaciones):
        break;

promedio=n/len(vec)

npromedio=0
for j in vec:
    if j>promedio:
        npromedio=npromedio+1

aprobado=0

#Primero inicializas el contador
promedioAprobados = 0
for h in vec:
    if h>=5:
        aprobado=aprobado+1
        #Va sumando cada unas de las notas
        promedioAprobados = promedioAprobados + h

#Luego saca el promedio sumatoria / cantidad de aprobados 
promedioAprobados = promedioAprobados / aprobado

reprobado=0
for k in vec:
    if k<=5:
        reprobado=reprobado+1

print("Max Calificacion", max(vec)) 
print("Min calificacion", min(vec))
print("Promedio:", promedio)
print("Superiores a promedio:", npromedio)
print("Cantidad de aprobados:", aprobado)
print("Promedio de aprobados:", promedioAprobados)
print("Desaprobados:", reprobado)
```
### Ejercicio 10. Capture 10 numeros enteros positivos y siga cual es mayor y cual es menor
#### Diagrama de flujo
[![Whats-App-Image-2022-10-24-at-4-32-26-PM.jpg](https://i.postimg.cc/FKnbL3GC/Whats-App-Image-2022-10-24-at-4-32-26-PM.jpg)](https://postimg.cc/McVjkcC1)
#### Prueba de escritorio
[![prueba-10.jpg](https://i.postimg.cc/PqN39tRc/prueba-10.jpg)](https://postimg.cc/cKyB8NZM)
#### Pseudocodigo del problema en lenguaje python
```python
lista = [10]
cant = int(input("¿Cuantos numeros desea capturar?"))
i=1
while i <= cant:
    n = int(input(f"{i} Ingrese un numero: "))
    lista.append(n)
    i+=1

print("Numero mayor es ",max(lista))
print("Numero menor es ",min(lista))
```
### Ejercicio 11. Obten la distancia mayor entre dos numeros consecutivos en una lista de 10
#### Diagrama de flujo
[![Whats-App-Image-2022-10-24-at-4-32-27-PM.jpg](https://i.postimg.cc/hvMVKmJ0/Whats-App-Image-2022-10-24-at-4-32-27-PM.jpg)](https://postimg.cc/8fJ7HjmF)
#### Prueba de escritorio
[![prueba-11.jpg](https://i.postimg.cc/qqLBYXtp/prueba-11.jpg)](https://postimg.cc/D4SK4GdN)
#### Pseudocodigo del diagrama de flujo en lenguaje de programacion dart
```dart
//Obtenga la distancia mayor entre dos numeros consecutivos
//en una lista de diez numeros

import 'dart:io';
import 'dart:core';

void main() {
  var Re = 0;
  var mayor = 0;
  stdout.write('Ingresa tus numeros \n');
  var lista = List.filled(10, 0);
  for (var i = 0; i <= 9; i++) {
    int Entrada = int.parse(stdin.readLineSync()!);
    lista[i] = Entrada;
  }
  var diferencias = List.filled(9, 0);
  for (var j = 0; j <= 8; j++) {
    diferencias[j] = (lista[j] - lista[j + 1]);
  }
  mayor = diferencias[0];
  for (var k = 0; k <= 8; k++) {
    if (mayor < diferencias[k]) {
      mayor = diferencias[k];
    } else {}
  }
  stdout.write("Tu lista es ");
  print(lista);
  stdout.write("y sus diferencias son ");
  print(diferencias);
  print('La diferencia mayor es ');
  print(mayor);
}
```
### Ejercicio 12. Almacene en un vector el resultado de una tabla de multiplicar (10 numeros)
#### Diagrama de flujo
[![Whats-App-Image-2022-10-24-at-4-32-27-PM-1.jpg](https://i.postimg.cc/Z5N25Ycd/Whats-App-Image-2022-10-24-at-4-32-27-PM-1.jpg)](https://postimg.cc/HrpBSgFY)
#### Prueba de escritorio del diagrama
[![prueba-12.jpg](https://i.postimg.cc/nhTRzsmM/prueba-12.jpg)](https://postimg.cc/ZWBFs5Vh)
#### Pseudocodigo del diagrama de flujo en lenguaje dart
```dart
import 'dart:io';

void main(List<String> args) {
  var array = [];
  int n = int.parse(stdin.readLineSync()!);
  for (var i = 0; i < 11; i++) {
    array.add(i);
    array[i] = n * i;
  }
  print('$array');
}
```
### Ejercicio 13. Imprimir un triangulo con asteriscos en un dfd
#### Diagrama de flujo
[![Whats-App-Image-2022-10-24-at-4-32-27-PM-2.jpg](https://i.postimg.cc/fLdfxkVc/Whats-App-Image-2022-10-24-at-4-32-27-PM-2.jpg)](https://postimg.cc/9RW92mt0)
#### Pseudocodigo del diagrama de flujo en lenguaje dart
```dart
import 'dart:io';

void main() {
  var n = 5;
  for (var i = 1; i <= 5; i++) {
    for (var j = 1; j <= i; j++) {
      stdout.write('*');
    }
    print('');
  }
}
```








