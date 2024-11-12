# Sniffing
Registrador de teclas para teclados inalámbricos y de cableado. Solo para uso éticos. Úsalo bajo tu responsabilidad. No me hago responsable del mal uso de esta herramienta 

asegurate de tener loa elementos necesarios para utilizar esta herramienta.
Para instalar el código en tu Arduino, sigue estos pasos:

*Requisitos previos*

1. Arduino IDE (versión 1.8.x o superior)
2. Arduino Mega o Arduino Uno
3. Bibliotecas necesarias (ver más abajo)

*Instalación de bibliotecas*

1. Abre el Arduino IDE.
2. Ve a "Sketch" > "Incluir biblioteca" > "Gestionar bibliotecas".
3. Busca y selecciona las siguientes bibliotecas:
- Keyboard
- BluetoothSerial
- RF24
1. Haz clic en "Instalar" para cada biblioteca.

*Carga del código*

1. Abre el Arduino IDE.
2. Crea un nuevo proyecto (Archivo > Nuevo).
3. Pega el código en el editor.
4. Selecciona el tipo de placa (Arduino Mega o Arduino Uno) en "Herramientas" > "Placa".
5. Selecciona el puerto de comunicación (USB) en "Herramientas" > "Puerto".
6. Haz clic en "Subir" para cargar el código en tu Arduino.

*Configuración del hardware*

1. Conecta el módulo Bluetooth al pin TX (2) y RX (3) de tu Arduino.
2. Conecta el módulo RF al pin CE (7) y CSN (8) de tu Arduino.
3. Conecta el teclado inalámbrico Bluetooth y el teclado cableado USB.

*Verificación*

1. Abre el Monitor Serie (Herramientas > Monitor Serie).
2. Verifica que el código esté funcionando correctamente.
3. Prueba presionar teclas en el teclado inalámbrico y cableado.

*Nota*: Asegúrate de que el teclado inalámbrico Bluetooth esté emparejado con el módulo Bluetooth y que el teclado cableado USB esté conectado correctamente.

muchos existos.
