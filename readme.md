Exposicion de la Universidad Industrial de Santander UIS

# CISCO PACKET TRACER
**Simulador de redes**

### ¿Qué es CISCO PACKET TRACER?
Es una potente herramienta para la simulación de redes de computadoras basada en los productos de CISCO y con gran cantidad de opciones, ideal para el aprendizaje y testeo de forma interactiva

![image](https://user-images.githubusercontent.com/114038362/214124442-5dd0657e-3ace-4dfe-9a80-8e16cbe451ac.png)

### ¿Por qué usarlo?
A pesar de ser una aplicación con una interfaz de manejo sencilla, posee el respaldo de CISCO y con ello un certificado de calidad, lo que garantiza una mayor cercanía entre la simulación y la realidad al poder crear diferentes situaciones para nuestras redes 

#### Funcionalidades
- Soporte para Windows y Linux
- Configuraciones multiusuario y colaborativas en tiempo real
- Soporte para IPv6 OSPF multiárea, redistribución de rutas, RSTP, SSH y Switchs multicapa

#### PROTOCOLOS SOPORTADOS
- HTTP, Telnet, SSH, TFTP, DHCP y DNS. 
- TCP/UDP, IPv4, IPv6, ICMPv4 e ICMPv6
- RIP, EIGRP, OSPF, enrutamiento estático y redistribución de rutas
- Ethernet 802.3 y 802.11, HDLC, Frame Relay y PPP
- ARP, CDP, STP, RSTP, 802.1q, VTP, DTP y PAgP

#### LA INTERFAZ
Packet Tracer cuenta con una sencilla interfaz de usuario  y un escenario, que nos permite trabajar de forma de didáctica incluyendo la opción de arrastrar y soltar para la inclusión de los elementos de nuestra red

![image](https://user-images.githubusercontent.com/114038362/214125142-0439d40d-d33d-456c-b2b4-5f5d3199be53.png)

#### A - INTERFAZ STANDARD

![image](https://user-images.githubusercontent.com/114038362/214125295-2e3dba06-532d-4423-a70a-b581d12354d7.png)

1. Nuevo / Abrir / Guardar / Imprimir / Asistente para actividades
2. Copiar / Pegar / Deshacer
3. Aumentar Zoom / Tamaño original / Reducir Zoom
4. Dibujar figuras (cuadrados, círculos y líneas)
5. Panel de Dispositivos Personalizados: Sirve para agregar o quitar dispositivos personalizados

#### B - HERRAMIENTAS

1) Puntero. Sirve para seleccionar cualquier item o área en el escenario
2) Sirve para mover el escenario
3) Sirve para hacer anotaciones en el escenario
4) Borrar del escenario un item
5) Muestra las tablas del dispositivo (enrutamiento, NAT, ARP, MAC, etc.)
6) Inyecta tráfico simple (ping) de dispositivo a dispositivo
7) Inyecta tráfico complejo (IP destino, TTL, intervalos, HTTP, Telnet, SNMP)

#### C - DISPOSITIVOS

![image](https://user-images.githubusercontent.com/114038362/214125736-e3a4e172-bc0b-42cf-9c64-41277c0dc722.png)

1) Routers: Muestra en el panel los modelos de routers disponibles
2) Switchs: Muestra en el panel los modelos de switchs disponibles
3) Hubs: Muestra en el panel los modelos de hubs disponibles
4) Dispositivos Wireless: Muestra en el panel los modelos de dispositivos Wireless disponibles
5) Medios: Muestra en el panel los medios (serial, fibra, consola, etc) disponibles

![image](https://user-images.githubusercontent.com/114038362/214125803-b5ccee15-9dbf-497c-a931-9efa45a8d566.png)

6) Dispositivos Finales: Muestra en el panel los dispositivos finales (impresora, host, server, etc.) disponibles
7) Emulación WAN: Muestra en el panel las diferentes emulaciones WAN (DSL, módem, cable, etc.) disponibles
8) Dispositivos Personalizados: Muestra en el panel los diferentes dispositivos personalizados disponibles
9) Panel de Dispositivos Seleccionados: Muestra los dispositivos disponibles según nuestra selección para utilizar en la topología. Se hace click en el dispositivo que deseamos utilizar y luego click en la parte del escenario que queremos ubicar nuestro dispositivo

#### D - TRÁFICO

![image](https://user-images.githubusercontent.com/114038362/214125974-0dc5ddd3-fdcc-4d67-bf29-ccd09655cf9c.png)

1) Crea escenarios para las diferentes PDU.
2) Muestra los resultados de las diferentes PDU.
3) Abre una ventana que muestra las transacciones de diferentes PDU en tiempo real. 

#### E – ESPACIO DE TRABAJO
![image](https://user-images.githubusercontent.com/114038362/214126091-39e705b3-d768-429e-a8f3-28096fabd8d6.png)

1) Selección de espacio de trabajo:
  - Lógico: Un espacio en blanco para montar una red 	sencilla
  - Físico: Es un plano mas elaborado en el que se ubican las 	redes dentro de un contexto (Ciudad, Edificio, etc.)

2) Accesos rápidos: en este espacio se nos muestran diferentes opciones de acuerdo a la acción que estemos realizando en el momento

#### CREACIÓN DE UNA RED
![image](https://user-images.githubusercontent.com/114038362/214126656-123af19a-6791-4380-9dbb-6eb9840e1e37.png)

#### INSERTAR DISPOSITIVOS

Básicamente es arrastrar y colocar los diferentes dispositivos a usar en la red (Routers, Switches, PCs, Servidores, etc..)

Hay de dos tipos:
- Genéricos: poseen variedad de puertos predefinidos, por lo cual no hay necesidad de insertar interfaces manualmente
- Referencia: son modelos predefinidos de los dispositivos, generalmente de CISCO. Poseen las configuraciones de fabrica predefinidas y normalmente necesitan la inserción manual de interfaces

#### ESQUEMA GENERAL
![image](https://user-images.githubusercontent.com/114038362/214126770-74503db0-740d-412b-9e16-8da3121ecd4c.png)

#### REFERENCIA
![image](https://user-images.githubusercontent.com/114038362/214126800-56f90d07-2043-484a-94fe-2945a99f996e.png)
![image](https://user-images.githubusercontent.com/114038362/214126830-3195adc9-8dc3-465c-ade7-52dea2047657.png)
Al momento de insertar una interfaz en cualquier tipo de dispositivo, es necesario que este se encuentre apagado físicamente (simulando la realidad) posteriormente debe volverse a encender

#### GENÉRICO
![image](https://user-images.githubusercontent.com/114038362/214126891-1af24edc-5a2a-4044-946c-a016b1540a3e.png)

#### INTERCONEXIÓN
Tal como una red tangible, es necesario utilizar el tipo de cableado adecuado de acuerdo a su función

- Serial (DCE y DTE) Consola
- UTP (directo y cruzado)
- Fibra
- Telefónico 
- Coaxial
- Serial (DCE y DTE)
![image](https://user-images.githubusercontent.com/114038362/214127111-0a9490d3-4760-4261-9377-02a72b3d8528.png)

Opcionalmente también existe un conector universal, el cual elige automáticamente el tipo de cable necesario y la interfaz a conectar
![image](https://user-images.githubusercontent.com/114038362/214127169-30e0d9c3-b7c3-4f2a-b15c-4192172fc441.png)

![image](https://user-images.githubusercontent.com/114038362/214127179-9b82fc16-f7c0-4737-8392-0796831d48de.png)

Se selecciona la conexión, luego el dispositivo de donde conecta (Router 2811) y posteriormente el dispositivo a conectar (Router genérico)

> Nota: al router 2811 se le agregó una interfaz WIC-1T para poder realizar la conexión serial

Luego de realizar todas las conexiones deberíamos tener lista nuestra red para ingresar las direcciones y configuraciones necesarias para ponerla en marcha
![image](https://user-images.githubusercontent.com/114038362/214127266-a51d3b5d-0dde-49b9-90e7-a981a1263e8b.png)

![image](https://user-images.githubusercontent.com/114038362/214127278-0a38c800-bbe4-4a23-8010-50d99f5ec952.png)

Opciones de configuración del Router y su respectivo comando para realizarlo en CLI (emulando el IOS de CISCO)

![This is an image](https://user-images.githubusercontent.com/114038362/214127535-a53c762a-eb06-4df6-9ca1-404472812a47.png) Router 2811.
![image](https://user-images.githubusercontent.com/114038362/214127936-0d758903-0112-45bf-9c44-433e4667b00e.png) Router Genérico

Al ingresar todas las configuraciones, deberíamos tener una red completamente funcional y que podemos hacer interactuar entre sí
![image](https://user-images.githubusercontent.com/114038362/214128009-4b498ff9-4a9d-4941-bf39-f2692a2250e4.png)}

#### ADMINISTRACIÓN
Se puede administrar el router 2811 usando el PC conectado directamente a la consola a través de una sesión de Terminal
![image](https://user-images.githubusercontent.com/114038362/214128069-e80351f7-0eb3-4236-841a-e938dca74f56.png)
#### ENVÍO DE PAQUETES

![image](https://user-images.githubusercontent.com/114038362/214128166-c83cae38-b806-4831-b356-b6914a77055c.png)

1) Registro: muestra los paquetes enviados y su estado

 2) Selección de modo:
- Realtime: permite seleccionar una PDU y realizar un ping manualmente

- Simulation: se configuran los paquetes a transitar y automáticamente simula el tráfico de la red

3) PDU compuesta: envía una PDU específica de acuerdo a lo seleccionado

4) PDU simple: envía un paquete ICMP por defecto

### CONCLUSIÓN
Packet Tracer es una herramienta con mucha potencia tanto didáctica como técnica que nos brinda la posibilidad de experimentar en vivo, cómo funcionan las tecnologías en redes de datos y realizar actividades de forma ilustrada para suplir nuestras necesidades.
