# Ingeniería electrónica

Esta tesis tuvo como objetivo diseñar, implementar y evaluar un sistema de estabilización y control en variable de estado para un gimbal de dos ejes de dinámica desacoplada. El sistema de control debe calcular un conjunto óptimo de salidas de control para estabilizar la plataforma en la posición en que se desee. Se construyó un prototipo experimental y se evaluaron los resultados obtenidos, comparándolos con simulaciones.

El diseño del sistema consideró limitaciones de implementación, incluidos los requisitos de procesamiento computacional y las limitaciones en oferta y costo de hardware. Actualmente, en la Argentina hay muchos problemas con las importaciones, razón por la cual hay muy poca oferta y variedad de productos electromecánicos. A su vez, los costos de productos especializados son muy elevados.

Se buscó lograr un desarrollo compacto con pocos puntos de soldadura, con alta estabilidad mecánica, gran capacidad de cómputo y bajo costo utilizando un DSC de doble núcleo.
Se modelizó el funcionamiento del sistema, obteniendo su espacio de estados, e implementando un control óptimo (LQR). Se comprobó el funcionamiento del filtro de Kalman y su eficacia para minimizar el ruido de las mediciones. Se comparó su desempeño con el del filtro complementario.

## Abstract

This thesis aimed to design, implement, and evaluate a state variable stabilization and control system for a two-axis gimbal with decoupled dynamics. The control system must compute optimal control outputs to stabilize the platform in the desired position. An experimental prototype was built and the results obtained were evaluated and compared with simulations.

The system design considered implementation constraints, including computational processing requirements and limitations in hardware supply and cost. Currently, there are many problems with imports in Argentina, which is why there is very little supply and variety of electromechanical products. At the same time, the costs of specialized products are very high. 

The aim was to achieve a compact design with few solder points, high mechanical stability, great computational capacity, and low cost using a dual-core DSC. The system dynamics were modeled, its state space was obtained, and an optimal control algorithm(LQR) was implemented. The performance of the Kalman filter and its effectiveness in minimizing measurement noise was tested. Its performance was compared with that of the complementary filter.
