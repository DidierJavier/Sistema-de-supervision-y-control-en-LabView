# Sistema-de-supervision-y-control-en-LabView
Desarrollar en el software Labview una interfaz gráfica que permita simular el llenado/vaciado de un tanque, incluya, titulo denominado subproceso_1, nombre del autor, incluir un indicador numérico tipo tanque que simulara el nivel de almacenamiento del producto con un rango de 0-50 kilo-litros y dos controles numéricos booleanos uno para marcha y otro para parada. 
Realizar algoritmo de programación implementando técnica por
máquina de estado.
El sistema de supervisión permitirá visualizar al operador el
incremento de nivel al interior del silo como resultado del
suministro en la etapa de recepción, el nivel debe iniciar con 0kilolitros
y realizar incrementos por unidad hasta llegar a 50 kilo-litros.
Cuando el nivel del silo llegue a la capacidad máxima 50 kilo-litros,
se activará un sistema para descargue del producto. El incremento
inicia con 50 kilo-litros y decremento por unidad hasta llegar a
0kilo-litros, silo vacío.
Defina los siguientes estados para realizar el algoritmo:
Estado_1: Inicio
Estado_2: Nivel ascendente
Estado_3: Nivel descendente
Estado_4: Final
Una vez finaliza la secuencia reinicializa y continua de forma
cíclica.
