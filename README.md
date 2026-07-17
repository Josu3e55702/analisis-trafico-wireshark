# Proyecto: Análisis de Tráfico Web No Cifrado (HTTP) con Wireshark

# Objetivo
Simular la navegación en un sitio web sin cifrado SSL/TLS para capturar, filtrar y analizar paquetes de red en tiempo real, demostrando habilidades básicas de análisis forense digital y comprensión de protocolos de red.

 Herramientas Utilizadas
* **Wireshark:** Captura de tráfico en vivo sobre la interfaz de red local (Wi-Fi/Ethernet).
* **Filtros de visualización:** Uso del filtro `http` para aislar peticiones web específicas.

Metodología y Resultados
1. Se inició una captura de paquetes en vivo mientras se accedía a un sitio de pruebas no seguro (`http://neverssl.com`).
2. Se detuvo la captura y se aplicaron filtros para limpiar el "ruido" de la red.
3. Se logró identificar con éxito la petición de tipo `GET HTTP/1.1`, demostrando cómo la información viaja en texto plano cuando no se utiliza el protocolo seguro HTTPS.

*Nota: El archivo `.pcap` con la captura real del tráfico analizado se encuentra adjunto en este repositorio.*
