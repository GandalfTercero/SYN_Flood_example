# Simulación de Ataque SYN Flood

## Descripción
Este proyecto tiene como objetivo simular un ataque SYN Flood en un entorno controlado para entender su funcionamiento, impacto y mitigación. Utilizamos máquinas virtuales en VirtualBox, donde:
- **Debian** actúa como servidor víctima con Apache instalado.
- **Kali Linux** actúa como atacante utilizando la herramienta `hping3`.
- **Wireshark** se utiliza para capturar y analizar el tráfico de red durante el ataque.

El experimento también explora cómo las técnicas de mitigación, como **SYN Cookies**, protegen al servidor de ataques de denegación de servicio (DoS).

## Público Objetivo
Este proyecto está diseñado para:
- Estudiantes y profesionales interesados en ciberseguridad.
- Personas que deseen aprender sobre ataques de red y sus contramedidas.
- Cualquier persona curiosa sobre cómo funcionan los ataques SYN Flood en un entorno práctico.

## Herramientas y Tecnologías
- **VirtualBox**: Para crear un entorno virtualizado seguro.
- **Debian**: Servidor víctima con Apache instalado.
- **Kali Linux**: Máquina atacante con herramientas como `hping3`.
- **Wireshark**: Para capturar y analizar el tráfico de red.
- **SYN Cookies**: Técnica de mitigación implementada en el kernel de Linux.

## Contenido del Repositorio
- **Documentación**: Guía paso a paso para configurar el entorno, ejecutar el ataque y mitigarlo.
- **Imágenes**: Capturas de pantalla de Wireshark y otros resultados clave.
- **Scripts**: Comandos y scripts útiles para automatizar partes del proceso (opcional).

## Conclusión
Este proyecto demuestra cómo un ataque SYN Flood puede afectar a un servidor web y cómo las técnicas de mitigación pueden protegerlo. Es una excelente oportunidad para aprender sobre seguridad de redes y experimentar con herramientas de ciberseguridad en un entorno controlado.
