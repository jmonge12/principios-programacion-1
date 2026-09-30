# Principios de Programación 1

Repositorio con las soluciones de los ejercicios desarrollados en clase.

## Contenido del repositorio

- `ejercicios/`: soluciones realizadas durante las clases.
- `README.md`: descripción del repositorio y de los temas vistos.

## Temas vistos en clase

### Constantes
Una constante es un valor que se guarda con un nombre y que no debería cambiar mientras el programa se ejecuta. Por convención se escriben en mayúsculas, como `IVA_CR` o `PI`. En `constantes.py` guardé el IVA de Costa Rica (0.13) y el de Panamá (0.07), y con el de Costa Rica calculé el impuesto de un producto cuyo precio el usuario ingresa por teclado.

### Operadores
En `operadores.py` practiqué tres tipos de operadores con las variables `a` y `b`:
- **Aritméticos:** suma, resta, multiplicación, división, división entera, módulo (residuo) y potencia.
- **De comparación:** igual, diferente, mayor, menor, mayor o igual y menor o igual. El resultado es `True` o `False`.
- **Lógicos:** `and`, `or` y `not`, que combinan o invierten valores verdaderos y falsos.

### Condicionales y operadores lógicos
En `condicionales-operadores-logicos.py` usé `if`, `elif` y `else` para clasificar a una persona según su edad (bebé, infante o adolescente), combinando comparaciones con el operador `and`. Después agregué condicionales anidados: si es infante, el programa pregunta si tiene acompañante, y si es adolescente, pregunta si trae permiso, para decidir si puede participar.

### Práctica de la semana 2
En `practica-semana2.py` hice un programa que calcula el total de una compra. El usuario ingresa el nombre del producto, la cantidad de artículos, el precio unitario y, si aplica, el porcentaje de descuento. El programa multiplica precio por cantidad para obtener el total, le resta el descuento y muestra una factura con el detalle y el monto final. Practiqué la entrada de datos con `input()`, la conversión a `int` y `float`, las operaciones aritméticas y el uso de f-strings para mostrar los resultados.

### Control de acceso a un evento
En `control-acceso-evento.py` resolví una situación de control de acceso siguiendo el orden de un diagrama de flujo. El programa pide si la persona tiene entrada válida, su edad, si pertenece a la institución y la hora de llegada. Con condicionales `if`, `elif` y `else` evalúa las condiciones en orden: primero la entrada, luego la edad, después la pertenencia a la institución y por último la hora. Según eso, el resultado puede ser acceso denegado, acceso general o acceso preferencial.

## Autor
Josue Monge — Universidad Cenfotec