# Simulacro_Redes
https://github.com/maritoo17/Simulacro_Redes/edit/main/README.md

#### Ejercicio 1: Modelos OSI y TCP/IP

- La primera diferencia entre ambos modelos es que el modelo OSI consta de 7 capas (física, enlace de    datos, red, transporte, sesión, presentación y aplicación) mientras que el modelo TCP/IP consta de 4   capas (acceso a red, Internet, transporte y aplicación.
- La segunda diferencia en cuanto a la orientación es que el modelo OSI tiene un modelo teórico con      capas bien definidas y el TCP/IP tiene un modelo práctido basado en protocolos usados en redes         reales.
- En cuanto al manejo de la capa de aplicación, la del modelo OSI separa la presentación y sesión y la   del modelo TCP/IP todo se maneja dentro de la capa de aplicación.

#### Ejercicio 2: Función de la capa de transporte

- La función principal de la capa de transporte es proporcionar comunicación confiable entre             dispositivos de red. Tendremos que diferenciar su función también dependiendo del modelo:
  - En OSI: asegura la entrega de datos sin errores en secuencia y sin duplicaciones.
  - En TCP/IP: se encarga de la transmisión de datos entre dispositivos, pero permite comunicación         confiable (TCP) o no confiable (UDP).

#### Ejercicio 3: TCP vs UDP

- En cuanto a terminos de orientación a conexión encontramos que el TCP es orientado a conexión mientras que el UDP no es orientado a conexión.
- El TCP es mucho mas fiable debido a que usa acuses de recibo retransmisiones mientras que el UDP no es confiable debido a que no usa acuses de recibo.
- En términos de velocidad y orden de entrega, el TCP es mucho mejor en cuanto al orden ya que garantiza que los datos llegan pero es más lento debido a que tiene un control de errores. El UDP en cambio, no garantiza el orden de llegada y es más rápido debido a      que no tiene un control de errores.

#### Ejercicio 4: Protocolo para Transferencia de archivos

- Para archivos en redes de TCP/IP el sistema de transferencia de achivos es el FTP (File Transfer Protocol) aunque también existen algunas alternativas como lo son el:
  - SFTP (Secure FTP): Transferencia segura a través de SSH.
  - TFTP (Trivial FTP): Versión simplificada sin autenticación.
 
#### Ejercicio 5: Resolución de nombres en DNS

- El trabajo del DNS (Domain Name System), es traducir nombres de dominio en direccioens IP. El proceso de            resolución se describe de la siguiente manera:
  - El usuario ingresa una URL en el navegador.
  - El sistema operativo consulta la caché DNS local.
  - Si no hay coincidencia, la solicitud se envía al servdior DNS configurado en la red.
  - El servidor DNS busca en su caché. En caso de no encontrar la respuesta, tiene que reenviar la solicitud a          servidores DNS raíz.
  - Los servidores raíz responden con el servidor de nombres del dominio.
  - El servidor DNS del dominio devuelve la dirección IP correspondiente.
  - El navegador establece una conexión con el servidor web usando la IP obtenida.  

#### Ejercicio 6: Comunicación en el modelo TCP/IP

- Para describir la comunicación el modelo TCP/IP, hay que mencionar las funcionalidades de cada capa del modelo      TCP/IP:
  - Capa de aplicación: la aplicación del usuario genera los datos y los pasa a la capa de transporte.
  - Capa de transporte:
    - Si usa TCP, establece una conexión.
    - Si usa UDP, envía los datos sin establecer conexión.
  - Capa de Internet: se asigna una dirección IP de origen y destino y se decide la mejor ruta.
  - Capa de acceso a red: se encapsulan los datos en tramas Ethernet o WiFi y se transmiten a través del medio          físico.
  - El dispositivo receptor procesa los datos y los envía a la aplicación destino.  
