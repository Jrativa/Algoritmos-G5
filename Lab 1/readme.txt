Laboratorio 1:

Calculo de complejidad teorica en tiempo: 

=O(1) + O(1) + O(1) + [O(n) * ( O(1) * [O(n)* ((O(1) * O(1)) + (O(1)* (O(1) + O(1) + O(1)))] + O(1)*[O(1) + O(1) + O(1)] + O(1))] + O(1)

= O(1)+[O(n) * ( O(1) * [O(n)* (O(1) + O(1))] + O(1)  * [O(1)] + O(1))]+ O(1) 

= O(1)+[O(n) * ( O(1) * [O(n)] + O(1) + O(1))]+ O(1)

= O(1)+[O(n) * ( [O(n)] + O(1))]+ O(1)

= O(1)+[O(n) *  [O(n)]]+ O(1)

= O(1)+[O(n^2)]+ O(1)

= O(n^2)


Tiempo en que demora en ejecutar la función (Una sola corrida)

	tiempo en que se ejecuta una función encontrar:
	0.011180047999999942


Ejecutando la función 10 veces:

		x= [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
		y = [0.011073038000000146, 0.00959963199999958, 0.0097027599999997, 0.009583425000000645, 0.009737829999999725, 
	    	0.00987013800000014, 0.009584945999999483, 0.009799057000000388, 0.009566309000000217, 0.009784082999999555]

	El promedio es:
	0.009830121799999958
