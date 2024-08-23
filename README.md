# Medición de calidad de energía de un inversor sincronizado con la línea comercial
Para este proyecto se realiza el diseño e implementación de un  inversor sincronizado con la línea comercial.

__Aplicaciones:__  
* Fuente de poder ininterrumpida.  
* Red de energía.  
* Paneles solares.

## Como características funcionales de este proyecto se tienen:

* __Inversor__
    * Vo = 9 VRMS  ± 2%
    * Fo = 60 Hz ± 5%
    * Po = 15W
* __Sincronización__
    * Enganche Fo = 60 Hz ± 5% (57 Hz – 63 Hz)
* __Medición de calidad__
    * Medición con módulo de adquisición
    * Acondicionamiento  de entrada de voltaje y corriente.
    * Rango dinámico de 80 dB
    * Variables a medir Vo (RMS), Io (RMS) y THD para estas.

## Equipo electrónico utilizado en este proyecto

<p align="center">
<img src="Git_Images/Multimeter.png" alt="Multimeter" width="300"/>  
<img src="Git_Images/Power Supply.png" alt="Power Supply" width="300"/>
</p>

<p align="center">
<img src="Git_Images/WaveGen.jpg" alt="WaveGen" width="300"/>
<img src="Git_Images/Oscilloscope.jpg" alt="Oscilloscope" width="300"/>
</p>

## Diagrama Bloques proyecto
<p align="center">
<img src="Git_Images/DiBloques.png" alt="DiBloques" width="800"/>  
</p>

## Acondicionamiento línea comercial  
Reducir el voltaje de 120 VRMS AC de la línea a un voltaje no mayor a 9 VRMS AC.
Proporcionar la señal cuadrada al PLL para que este funcione correctamente.

## Circuito Inversor Esquemático  
<p align="center">
<img src="Git_Images/Inversor_DC_AC.png" alt="Inversor_DC_AC" width="500"/>  
</p>

## Circuito PLL  
Debe sincronizar la salida del inversor con la línea comercial acondicionada.  
Capacidad de enganchar una señal a la línea en un rango de +- 3 Hz.

<p align="center">
<img src="Git_Images/CircuitoPLLProtoboard.png" alt="CircuitoPLLProtoboard" width="500"/>  
<img src="Git_Images/CtoPLL.png" alt="CtoPLL" width="500"/>  
</p>

## Circuito VCO - Generador onda seno  
<p align="center">
<img src="Git_Images/VCO_Gen Sen.png" alt="VCO_Gen Sen" width="800"/>  
</p>

## PCB del Proyecto  

<p align="center">
<img src="Git_Images/PCB_Top.jpg" alt="PCB_Top" width="380"/>  
<img src="Git_Images/PCB_Bott.jpg" alt="PCB_Bott" width="380"/>  
</p>
