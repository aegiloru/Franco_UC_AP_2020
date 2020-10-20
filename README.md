# Franco_UC_AP_2020
Trabajo Final de Grado de Jesus Franco. Universidad Católica - Sede Alto Paraná - 2020 </br>

<b>Detección de carriles para la navegación de un vehículo Autonómo utilizando Visión Computacional</b></br>

<b>Resumen</b></br>
La detección del carril es un problema desafiante y juega un papel fundamental tanto en los vehículos autónomos como en los sistemas avanzados de asistencia a la conducción (ADAS).</br>

Para presentar una solución al problema, se han propuesto dos algoritmos basados en procesamiento de imágenes.</br>
Ambas propuestas consisten en: modelar linealmente los carriles y extraer las características de los carriles a través de un análisis del gradiente de intensidades.</br> 

Los algoritmos utilizados para la posterior comprensión de estas características fueron, la transformada probabilística progresiva de Hough para la detección de líneas y el RANSAC (RANdom SAmple Consensus) para una estimación robusta del modelo.</br>

Ambos algoritmos fueron evaluados de forma offline en dos datasets, TuSimple y Hernandarias (elaborado para el presente proyecto).</br>

Finalmente, se han implementado ambos algoritmos como medio de percepción del entorno para mantener al vehículo en su respectivo carril, en el simulador CARLA.</br>

<b>Palabras clave</b></br>
ADAS. Detección de carriles. RANSAC. Transformada de Hough. Vehículos autónomos.</br>

DataSet Hernandarias: https://bit.ly/31qbZh4 </br>
