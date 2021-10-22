# Movimiento-Browniano a partir de algoritmos de Monte Carlo


Este modelo describe el movimiento de una partícula suspendida en un fluido resultante de colisiones aleatorias con las moléculas rápidas del fluido (difusión). De manera más general, el movimiento browniano modela una caminata aleatoria en tiempo continuo, donde una partícula evoluciona en el espacio dando pasos aleatorios independientes en todas las direcciones.

El movimiento browniano $W(t)$ tiene varias propiedades importantes. Primero, da lugar a trayectorias continuas, además sus incrementos $W (t + \tau) - W (t)$ son independientes de los intervalos que no se superponen.Y por último, estos incrementos son variables aleatorias gaussianas. Más precisamente 
\begin{equation}
    W (t + \tau) - W (t)  \sim N(0,\tau) 
\end{equation}

Considerando $t, \tau >0 $; la densidad de $W (t)$ es una distribución normal con varianza $t$. 

El cambio en una variable $z$ que sigue un movimiento Browniano durante un intervalo de tiempo $dt$ se define como:

\begin{equation}
dz= \xi \sqrt dt
\end{equation}

donde $\xi$ es una variable aleatoria Gaussiana com media en cero y varianza $1$. Para $n$ intervalos sucesivos durante un tiempo t se tendra:

\begin{equation}
dt= \frac{t}{n} 
\end{equation} 
