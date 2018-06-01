#Cuanto dinero billetes de 100 puede prestar un amigo y que cnatidad no puede prestar
## un amigo puede prestar billetes de 100 
va a decir cuanto dinero puede prestar y cuanto no puede prestar
un resultado va a ser numero y otro va a ser no puedo prestarte

##pseudocodigo 
inicio  
Leer y guardar dinero pedido en numeros enteros  
Guardar en Cantidad de billetes = dinero pedido /100 
Guardar en Cantidad no disponible = dinero pedido -(Cantidad de billetes+100) 
Imprimir en pantalla "Cantidad de Billetes disponibles para prestamo" = Cantidad de billetes
Imprimir en pantalla "Cantidad no disponible" = Cantidad no disponible
Fin

## corrida de escritorio 1
dinero pedido= 632  
Cantidad en billetes  =632/100= 6  
Cantidad no disponible =632 - (6*100)= 32

## corrida de escritorio 2
dinero pedido= 1300
Cantidad en billetes  =1300/100= 13 
Cantidad no disponible =1300 - (13*100)= 0

# corrida de escritorio 3
dinero pedido= 1500
Cantidad en billetes  =1500/100= 15 
Cantidad no disponible =1500 - (15*100)= 0



