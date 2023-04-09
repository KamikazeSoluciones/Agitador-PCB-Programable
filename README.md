# Agitador-PCB-Programable

README 

Este proyecto consiste en un dispositivo que permite revelar o atacar con el 
cloruro férrico las láminas fenólicas para poder realizar nuestras PCB. Este 
dispositivo es controlado mediante un Arduino y cuenta con una serie de 
componentes como botones de programación, pantalla LCD, speaker, motor de 12VDC, 
fuente dual de 12VDC, rele y potenciómetro para el contraste de la pantalla.

FUNCIONALIDADES

✅ Control de tiempo: el dispositivo permite programar el tiempo de revelado 
    en horas, minutos y segundos mediante los botones de programación.
    
✅ Indicador de finalización: el speaker del dispositivo emite un sonido cuando 
    se completa el tiempo de revelado programado.
    
✅ Motor de agitación: el motor de 12VDC se encarga de agitar el cloruro férrico 
    para que el proceso de revelado sea uniforme.
    
✅ Pantalla LCD: la pantalla LCD de 16 x 2 caracteres muestra el tiempo programado, 
    el tiempo restante y otras información útil.

COMPONENTES

    👉🏼 Arduino: es la placa que controla todo el sistema.
    👉🏼 Botones de programación: permiten programar el tiempo de revelado.
    👉🏼 Pantalla LCD: muestra información del proceso.
    👉🏼 Speaker: emite un sonido cuando se completa el tiempo de revelado.
    👉🏼 Motor de 12VDC: se encarga de agitar el cloruro férrico.
    👉🏼 Fuente dual de 12VDC: alimenta al motor y al Arduino y la pantalla LCD.
    👉🏼 Rele: se utiliza para controlar el encendido y apagado del motor.
    👉🏼 Potenciómetro: se utiliza para ajustar el contraste de la pantalla LCD.

INSTALACIÓN

Para instalar el dispositivo, siga los siguientes pasos y conecte como se muestra en el diagrama:

    Conecte la fuente dual de 12VDC al Arduino y a la pantalla LCD.
    Conecte el motor de 12VDC al rele y a la fuente dual.
    Conecte el speaker al Arduino.
    Conecte los botones de programación al Arduino.
    Conecte el potenciómetro al Arduino y a la pantalla LCD.
    Conecte el cloruro férrico y las láminas fenólicas al dispositivo.
    Cargue el código en el Arduino y encienda el dispositivo.
    
![Diagram](https://user-images.githubusercontent.com/89432904/230784781-0e57c439-7b25-407e-b503-335530997e15.jpg)

USO

Para utilizar el dispositivo, siga los siguientes pasos:

    Ajuste el contraste de la pantalla LCD utilizando el potenciómetro.
    Utilice los botones de programación para ajustar el tiempo deseado.
    Presione el botón "Inicio" para iniciar el proceso de revelado.
    El speaker emitirá un sonido cuando se complete el tiempo de revelado programado.
    
CONCLUSIONES
    
El dispositivo "Agitador Programable con Arduino" es una herramienta útil para el proceso 
de revelado de láminas fenólicas para PCB. Con su capacidad de programar el tiempo de 
revelado y su motor de agitación, se asegura que el proceso de revelado sea uniforme y 
efectivo. La pantalla LCD y el speaker hacen que el dispositivo sea fácil de usar y 
monitorear, mientras que la fuente dual de 12VDC y el rele permiten un control seguro del 
motor.

![Agitator PCB_3](https://user-images.githubusercontent.com/89432904/230784877-05202138-1525-4ee2-a8c1-83ecd8ac3437.jpg)

Este proyecto puede ser utilizado tanto por profesionales como por aficionados en la 
creación de PCB, y ofrece una solución asequible y personalizada en comparación con opciones 
comerciales más costosas.

En resumen, el dispositivo "Agitador Programable con Arduino" es una excelente adición al
kit de herramientas de cualquier persona que trabaje en electrónica o PCB, y su diseño modular
permite una fácil personalización y actualización.
