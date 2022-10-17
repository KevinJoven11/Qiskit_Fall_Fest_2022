# Qiskit Fall Fest [Español]

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

## Referencias:
Libreria de mitigación: https://qiskit.org/documentation/stable/0.26/tutorials/noise/3_measurement_error_mitigation.html  
Libreria de modelos de ruido: https://qiskit.org/documentation/tutorials/simulators/3_building_noise_models.html  
Libro error correction: https://link.springer.com/chapter/10.1007/978-3-030-63689-0_9  
GHZ circuito usando qiskit: https://quantum-computing.ibm.com/lab/docs/iqx/example-circuits/ghz  

# Qiskit Fall Fest [English]

Evaluation of different error mitigation techniques in the Greenberger–Horne–Zeilinger (GHZ) state using a T1/T2 thermal relaxation noise model.

## Description:

The GHZ circuit was used to evaluate two different techniques to mitigate bit-flip (T1) and phase-flip (T2) errors caused by a thermal relaxation noise model in conjunction with Qiskit's Qasm simulator. In addition, a circuit was built to correct the previously described errors, following reference [1]. It was concluded that the two mitigation techniques are effective for T1 relaxation times less than 50 us, since the Hellinger fidelity decreases below 0.99 and less.

## Members:

### Kevin Joven 
- Undergraduate: Universidad del Valle, Cali, Colombia

### Juan Giraldo
- Undergraduate: Universidad Icesi, Cali, Colombia
- Graduate: University of Victoria, Victoria, Canada

### Jose Ossorio
- Undergraduate: Universidad Icesi, Cali, Colombia
- Graduate: University of Victoria, Victoria, Canada

## References:
Mitigation library: https://qiskit.org/documentation/stable/0.26/tutorials/noise/3_measurement_error_mitigation.html  
Noise models library: https://qiskit.org/documentation/tutorials/simulators/3_building_noise_models.html  
Error correction book: https://link.springer.com/chapter/10.1007/978-3-030-63689-0_9  
GHZ circuit using Qiskit: https://quantum-computing.ibm.com/lab/docs/iqx/example-circuits/ghz
