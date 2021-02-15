# ProyectoFinal
CALCULO DE SEGURO
Programa que calcula de forma automática el precio de un seguro incluyendo recargos, en base a un costo base.  
Presenta como resultado del programa el nombre, cálculo de recargo, y precio total del seguro.

Parámetros de entrada
con los siguientes parámetros de entrada:
	• Nombre del Interesado
	• Edad del Interesado
	• Está casado (SI/NO)
		○ Si está casado, edad del conyugue
	• Tiene hijos (SI/NO)
		○ Si tiene hijos, cantidad de hijos.

Condiciones:
	1. PRECIO_BASE = 2000
	2. Cálculo de recargo por edad del interesado y de conyugue(si hay):  Hay una serie de rangos y dependiendo del rango, se aplicara un recargo al precio base.  
	Este recargo se guardara individualmente para interesado y para el conyugue si está casado.
	Rangos por edad en anos		Recargo en %
			(18-24)					10
			(25-49)					20
			>=50					30

Calculo por cantidad de hijos:  Se aplica un recargo de 20% por cada hijo que el interesado tenga.
