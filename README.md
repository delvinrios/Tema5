# Modelos probabilísticos de señales y sistemas
## Laboratorio 5: Tema 5
## Delvin Ríos Rodríguez, B76319

### Solución: 
Se pedía modificar el código P5_base, ya que la administración del servicio desea que el servicio no esté vacío (sin atender solicitudes) más del 10% del tiempo. 

Entonces: 

P(1 o más clientes en el sistema) = rho = lamda/v = 0.9.

Del enunciado se tenía que: lamda = 2

Entonces al despejar se tiene que: v = 2.2222

Modificando los parámetros en el código se logra ver en la figura y en los resultados que si se cumple la especificación del problema
