# PrintPCBs

Se trata de piezas imprimibles que permiten crear circuitos sencillos.

La primera vez que vi esta idea en un [diseño del maestro @obijuan](https://github.com/Obijuan/3D-parts/tree/master/2016-10-11-printable-led-pcb)

![pcb led](https://github.com/Obijuan/3D-parts/blob/master/2016-10-11-printable-led-pcb/images/pcb-led-1.png?raw=true)

y en otro diseño [más elaborado](https://github.com/FPGAwars/alhambra-led)

![alhambra-led](https://github.com/FPGAwars/alhambra-led/blob/master/wiki/alhambra-led-1.png?raw=true)

A partir de aquí han sido varias las propuestas como el [PCBPrint semáforo](https://github.com/movilujo/designs_3D/tree/master/PCBprint) de @Movilujo (Inventor del nombre PCBPrint)

![pcbprint](https://github.com/movilujo/designs_3D/blob/master/PCBprint/images/PCBprint_Semaforo_iso1.jpeg?raw=true)

y algún otro que no tengo localizado en github

Estas son mis aportaciones

## [PrintPCB ProtoBoard](./PCBPProtoPrint/)

Primera versión de una PCB imprimible para hacer pruebas

[Diseño](./PCBPProtoPrint/PCBPrint_protoboard.fcstd)


![Diseño](./images/PCBPrint Protoboard.png)

Se pueden elegir el número de filas, columnas y de pines.
Basta con cambiar el número en la hoja de cálculo incluida en el diseño


![Parámetros](./images/Configuracion.png)


## [PCBPrint LED (BC547)](PCBPProtoPrint/README.md)

Un diseño alternativo al Alhambra led para transistores de otro patillaje

![PCBPrint top](https://lh3.googleusercontent.com/faS4u0jSnPc2ternjIO0dI98AgeIof-VYvwydO_39pRlzklZmNVJVevmMY9PZ4FkgxjcqfSFqsM=w1073-h936-no)

## [PCBPrint LDR](PCBPrint_ldr/README.md)

Sensor luminoso analógico

![a](https://lh3.googleusercontent.com/26gFsAEfURvQOTPk-pSBdqHTtw5iUMiUMRKyBG1VacKKsArQVctltIio2KhcOqpLYgqwoGKWx3s=w807-h935-no)

## [PCBPrint Pulsador](PCBPrint_button/README.md)

Pulsador con conexión Pull Down

![a](https://lh3.googleusercontent.com/vTEPZUCdk6lisei_uNa5GlQSCNVYprbPvmiwcR6VBZw6Xqr7tKk2wf-3JtS8dFbteqAKWz6LdjY=w772-h936-no)


## Próximamente

* Led sin transistor (con 3 pines)
* Driver de motores (L293D)
* Detector de infrarrojos para mando a distancia
* LED RGB
* Siguelineas
  * Versión simple con los Led IR
  * Utilizando un opamp (LM358)
* Buzzer simple (conexión directa al pin)
* Buzzer amplificado por un transistor
* Shield básico que permite conectar cables de 3 pines


![CC](./images/Licencia CC.png)
