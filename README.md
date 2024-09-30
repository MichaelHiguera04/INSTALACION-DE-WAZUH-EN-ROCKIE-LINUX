# INSTALACION-DE-WAZUH-EN-ROCKIE-LINUX
a continuacion enseñare la instalacion correcta de Wazuh en un servidor Rockie linux.
instalaremos Wazuh-indexer, Wazuh-manager y Wazuh-dashboard desde cero haciendolo paso a paso con cada uno de los comandos activos y actualizacos

¿ Que es Wazuh ? 

Wazuh es una plataforma de seguridad informática de código abierto que ofrece detección, visibilidad y respuesta a amenazas. Se basa en la integración de tres componentes:
1) un agente que se instala en los sistemas a proteger.
2) un servidor que recibe y procesa los datos enviados por los agentes
3) una interfaz web que permite visualizar y gestionar la información.

¿ Como funciona ?

El agente de Wazuh se encarga de recopilar información de los sistemas a proteger, como el registro de eventos, información de procesos, estado de los servicios y archivos modificados.
Estos datos se envían al servidor de Wazuh, donde se procesan y se comparan con las políticas de seguridad definidas.
Si se detecta una posible amenaza, Wazuh envía una alerta al administrador del sistema,
quien puede tomar medidas para mitigar el problema. Además, Wazuh cuenta con un sistema de correlación de eventos que permite identificar patrones de comportamiento anómalos, 
lo que facilita la detección de amenazas que podrían pasar desapercibidas en una inspección manual.

REQUISITOS BASICOS PARA REALIZAR ESTA INSTALACION...}


