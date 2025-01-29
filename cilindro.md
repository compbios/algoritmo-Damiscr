
Algoritmo Calcular_Volumen_y_Área_Cilindro
	Escribir "Ingrese el radio del cilindro:"
    Leer radio
    Escribir "Ingrese la altura del cilindro:"
    Leer altura
    constante_pi <- 3.1416
    volumen <- constante_pi * radio^2 * altura
    area <- 2 * constante_pi * radio * (radio + altura)
    Escribir "El volumen del cilindro es:", volumen
    Escribir "El área total del cilindro es:", area
FinAlgoritmo
