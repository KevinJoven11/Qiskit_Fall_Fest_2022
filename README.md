# Qiskit Fall Fest 

Evaluacion de diferentes tecnicas de mitigacion de errores en el estado Greenberger–Horne–Zeilinger (GHZ) utilizando un modelo de ruido de relajacion termica T1/T2.

## Descripcion:

Se utilizo el circuito GHZ para evaluear dos diferentes tecnicas para mitigar errores de tipo bit-flip (T1) y phase-flip (T2) causados por un modelo de ruido de relajacion termica en conjunto con el simulador Qasm de Qiskit. En adicion se construyo un circuito para la correccion de los errores previamente descritos, siguiendo la referencia [1]. Se logro concluir que las dos tecnicas de mitigacion son efectivas para tiempos de relajacion de T1 menores a 50 us, ya que la fidelidad de Hellinger decrese por debajo de 0.99 y menos.

## Integrantes:

### Kevin Joven 
- Pregrado: Universidad del Valle, Cali, Colombia

### Juan Giraldo
- Pregrado: Universidad Icesi, Cali, Colombia
- Posgrado: University of Victoria, Victoria, Canada

### Jose Ossorio
- Pregrado: Universidad Icesi, Cali, Colombia
- Posgrado: University of Victoria, Victoria, Canada
