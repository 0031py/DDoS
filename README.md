# DDoS

Herramienta de DDoS para realizar ataques en redes mediante el envío masivo de paquetes UDP a una dirección IP y puerto específicos.
![DDoS tool](https://files.catbox.moe/imyzxm.png) 
## Librerías utilizadas

- `socket` — Para la comunicación de red y envío de paquetes UDP.
- `threading` — Permite la ejecución concurrente mediante múltiples hilos.
- `random` — Para generar números aleatorios (puertos aleatorios si no se especifica uno fijo).
- `time` — Para medir intervalos y pausas de ejecución.
- `colorama` — Para dar color y formato a la salida en consola.
- `platform` — Para detectar el sistema operativo y ajustar comandos.
- `ctypes` — Para modificar el título de la consola en Windows.
- `subprocess` — (No utilizado en el código actual, pero importado).
- `os` — Para ejecutar comandos del sistema (limpiar pantalla).

## Características

- Envío configurable de paquetes UDP.
- Soporte para múltiples hilos para maximizar el tráfico generado.
- Visualización en tiempo real de la velocidad y el volumen de datos enviados.
- Opciones para personalizar puerto, cantidad de hilos y tamaño de los paquetes.

## Uso

> **Advertencia:** Esta herramienta es solo para fines educativos y de pruebas en entornos controlados y autorizados. El uso no autorizado puede ser ilegal.

## Instalación

- Python 3.x
- colorama (`pip install colorama`)

## Autor

0031py
