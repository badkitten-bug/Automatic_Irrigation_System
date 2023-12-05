---
layout: ../../layouts/MarkdownPostLayout.astro
title: 'Documentacion'
pubDate: 2023-11-28
description: 'En este documento revisaremos todo el trabajo realizado en el proyecto de "Sistema de Riego Automático" utilizando Tinkercad y Arduino.'
author: 'Steve Gomez'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Documentacion.'
tags: ["Tinkercad", "Arduino", "Sistema", "Riego", "Automático"]
---


# Indice
1. [Introducción](#introducción)
2. [Planteamiento del problema](#planteamiento-del-problema)
3. [Objetivos](#objetivos)

    3.1 [Objetivo general](#objetivo-general)

    3.2 [Objetivos específicos](#objetivos-específicos)
    
4. [Fundamentos teóricos](#fundamentos-teóricos)

   4.1 [Gestión de Sistema de Riego Automático](#gestión-de-sistema-de-riego-automático)

   4.2 [Internet de las cosas (IoT)](#internet-de-las-cosas-iot)

5. [Diseño](#diseño)

   5.1 [Diseño electrónico](#diseño-electrónico)

   5.2 [Diseño de software de transmisores y actuadores](#diseño-de-software-de-transmisores-y-actuadores)

   5.3 [Diseño de software de aplicación web/móviles](#diseño-de-software-de-aplicación-webmóviles)
6. [Implementación](#implementación)

   6.1 [Implementación de sensores](#implementación-de-sensores)

   6.2 [Implementación de software de sensores y actuadores](#implementación-de-software-de-sensores-y-actuadores)

   6.3 [Implementación de aplicación web/móvil](#implementación-de-aplicación-webmóvil)
7. [Costos](#costos)
8. [Resultados](#resultados)
9. [Conclusiones](#conclusiones)
10. [Referencias](#referencias)

<br>
<br>
<br>

# TÍTULO: SISTEMA DE RIEGO AUTOMÁTICO

## Introducción

El presente proyecto establece un enfoque innovador para abordar los desafíos actuales en la agricultura mediante la creación de un "Sistema de Riego Automático" utilizando Tinkercad y Arduino.

## Planteamiento del problema

Este proyecto presenta un enfoque innovador para abordar los desafíos actuales en la agricultura mediante la creación de un "Sistema de Riego Automático" utilizando Tinkercad y Arduino.

### Problemas climáticos:

- **Cambio de estaciones:** Las variaciones estacionales pueden desafiar la capacidad de los agricultores para adaptarse a diferentes condiciones climáticas.
- **Eventos Meteorológicos Extremos:** Los eventos climáticos extremos, como tornados, ciclones y tormentas, pueden causar daños significativos a los cultivos y la infraestructura agrícola.
- **Pérdida de Suelo por Erosión:** La erosión del suelo debida a fuertes lluvias y vientos puede disminuir la calidad del suelo y reducir la capacidad de retención de nutrientes, afectando negativamente a los cultivos.

### Problemas de riego:

- **Contaminación del Agua:** La contaminación del agua utilizada para el riego, ya sea por productos químicos agrícolas o contaminantes industriales, puede perjudicar la salud de las plantas y la calidad de los cultivos.
- **Gestión de Residuos de Riego:** La acumulación de sales y minerales en el suelo debido al riego excesivo puede degradar la calidad del suelo y afectar negativamente a los cultivos.
- **Riego en Zonas Áridas:** En regiones áridas, el riego eficiente y la conservación del agua son especialmente críticos, ya que el suministro de agua es escaso y valioso.

### Problema en el uso de recursos:

- **Desperdicio de Recursos Hídricos:** La falta de un riego preciso y la pérdida de agua pueden agotar los recursos hídricos y aumentar los costos de producción.
- **Humedad de Tierra Ineficiente:** La disposición eficiente de humedad en los cultivos en el terreno agrícola puede dar lugar a una baja producción y un uso ineficaz de la tierra.

## Objetivos

### Objetivo general

Diseñar, desarrollar y poner en funcionamiento un Sistema de Riego Automático utilizando Tinkercad y Arduino, con el propósito de mejorar la eficiencia, la sostenibilidad y la productividad en la agricultura.

### Objetivos específicos:

1. Implementar sensores y actuadores para el control de los problemas de humedad en la tierra de los cultivos.
2. Implementar sensores y actuadores para verificar si el nivel de humedad cambia en la tierra de los cultivos.
3. Implementar sensores y actuadores para prevenir los problemas de sequía y muerte de los cultivos.
4. Implementar sensores y actuadores para reducir la carga de trabajo del personal.
5. Implementar sensores y actuadores para automatizar y sostener los procesos de riego de los cultivos.
6. Desarrollar aplicaciones web para el registro, presentación gráfica y monitoreo de los datos de los sensores y actuadores en servidores y bases de datos propios y/o en la nube.
7. Desarrollar interfaces de usuario amigables en aplicaciones móviles como parte de un sistema de monitoreo remoto que permita gestionar los cultivos.
8. Integrar todas las aplicaciones en un sistema llave en mano que permita a los administradores controlarlo y gestionarlo remotamente.

## Fundamentos teóricos

### Gestión de Sistema de Riego Automático

### a) Espacios con Áreas Verdes

Tenemos un campo de riego el cual se conforma de una extensa área la cual es trabajada por los agricultores; es importante el cuidado de la tierra para los sembríos por lo tanto mantener el cuidado de la tierra para que los cultivos no perezcan o de poca cosecha. Como ventaja tiene que al ser de manera automática no quiere una supervisión constante, para este caso en el campo agrícola, permite un continuo riego el cual.

### b) Elementos de un campo agricultor

#### Estructura:

- **Base:** La estructura en la que se apoya el sistema de riego automático

#### Cubierta:

- **Malla de sombreado:** Recubre los sembrados protegiéndolos del ambiente.

#### Sistema de ventilación:

- **Ventanas y puertas:** Para permitir la entrada y salida de aire.
- **Ventiladores:** Para proporcionar circulación de aire, especialmente en invernaderos grandes.

#### Sistema de ventilación:

- **Tuberías y conductos:** Para la distribuir el agua de riego de manera automatizada.
- **Aspersores o goteros:** Dispositivos para distribuir el agua de manera uniforme sobre las plantas de forma automatizada.

#### Control de clima:

- **Termostatos:** Para controlar la temperatura dentro del área de riego automático.

#### Bancos o estantes:

- Para colocar plantas y que proporcionan espacio para cultivar plantas en macetas o bandejas.

#### Iluminación:

- **Luces naturales:** Proporcionada por el sol de forma natural.

#### Sistema de drenaje:

- **Canalones o tubos de drenaje:** Para poder eliminar el excedente de agua y poder evitar inundaciones en el área de riego.

#### Equipos de protección:

- **Mallas antipájaros:** Para evitar que las aves entren y dañen las plantas.
- **Mallas anti insectos:** Para proteger las plantas de insectos y plagas.

#### Sistema de Fertilización:

- **Inyectores de Fertilizantes:** Para proporcionar nutrientes a las plantas a través del sistema de riego.

#### Sistema de Control Automatizado:

- **Sensores:** Para medir la temperatura, humedad y otros parámetros.
- **Controladores:** Automatizan los sistemas de calefacción, refrigeración, riego y ventilación basados en las lecturas de los sensores.

## Gestión de un Campo Agricultor

La gestión de un campo agricultor implica una serie de actividades y decisiones que van desde la planificación y el cultivo de plantas hasta el mantenimiento del invernadero y la comercialización de los productos y comprende:

### Planificación:

- **Selección de Cultivos:** Decidir qué tipo de plantas cultivar basándose en la demanda del mercado y las condiciones climáticas locales.
- **Diseño del Invernadero:** Planificar la disposición de las plantas, sistemas de riego, ventilación y otras infraestructuras dentro del invernadero.
- **Presupuesto:** Establecer un presupuesto para la construcción, operación y mantenimiento del invernadero.

### Cultivo:

- **Preparación del Suelo:** Asegurar que el suelo esté adecuadamente preparado y enriquecido con nutrientes.
- **Siembra o Trasplante:** Sembrar semillas o trasplantar plántulas en los bancos o camas del invernadero.
- **Riego y Nutrición:** Implementar un sistema de riego eficiente y proporcionar nutrientes adecuados a las plantas.
- **Control de Plagas y Enfermedades:** Monitorear y controlar las plagas y enfermedades para mantener las plantas sanas.

### Mantenimiento:

- **Podas y Entutorado:** Realizar podas regulares y proporcionar soportes para las plantas que lo necesiten.
- **Control de Clima:** Ajustar la temperatura, humedad y ventilación según las necesidades de las plantas y las condiciones climáticas externas.
- **Mantenimiento del Invernadero:** Realizar inspecciones regulares para reparar cualquier daño en la estructura, sistemas de riego o ventilación.
- **Limpieza:** Mantener el invernadero limpio para evitar la acumulación de plagas y enfermedades.

### Gestión Operativa:

- **Registro y Monitoreo:** Mantener registros detallados sobre los cultivos, el riego, las condiciones climáticas y las ventas.
- **Inventario:** Gestionar el inventario de semillas, plántulas, sustratos y otros suministros necesarios para el cultivo.
- **Gestión del Personal:** Si hay trabajadores, coordinar las tareas, los turnos y el entrenamiento necesario.
- **Gestión de Residuos:** Disponer adecuadamente de los residuos orgánicos y no orgánicos generados en el invernadero.

### Comercialización:

- **Mercadeo:** Desarrollar estrategias de marketing para promover los productos del invernadero.
- **Ventas:** Establecer canales de venta, ya sea a través de mercados locales, tiendas, restaurantes o directamente al consumidor.
- **Relaciones con Clientes:** Mantener una buena relación con los clientes para establecer la confianza y fomentar la lealtad.

### Mejora Continua:

- **Evaluación de Rendimiento:** Analizar regularmente los resultados para identificar áreas de mejora.
- **Investigación y Desarrollo:** Estar al tanto de las nuevas tecnologías, prácticas agrícolas y tendencias del mercado para mejorar la producción y diversificar los cultivos.

# Internet de las cosas (IoT)

## Características

La IoT se está utilizando de manera extensa en sectores como la agricultura (agricultura de precisión), la salud (monitoreo remoto y dispositivos médicos), la industria (industria 4.0) y el transporte (vehículos autónomos), entre otros. A medida que la IoT sigue creciendo, también se enfrenta a desafíos significativos, especialmente en términos de seguridad y privacidad. La protección de datos y la seguridad cibernética son áreas de enfoque clave para la futura expansión de la IoT. La IoT sigue siendo un campo de rápido desarrollo con un potencial significativo para transformar numerosos aspectos de nuestras vidas y la forma en que interactuamos con el mundo que nos rodea.

## Elementos de la IoT

1. **Dispositivos Físicos:**
   - Son objetos del mundo real equipados con sensores, actuadores y tecnología de conectividad para recopilar datos y comunicarse a través de la red.

2. **Sensores:**
   - Capturan datos del entorno, como temperatura, humedad, luz, movimiento, etc.

3. **Actuadores:**
   - Realizan acciones en respuesta a las señales enviadas desde otros dispositivos o sistemas.

4. **Conectividad:**
   - Los dispositivos IoT necesitan algún tipo de conexión para comunicarse, como Wi-Fi, Bluetooth, Zigbee, LPWAN, 4G/5G, etc.

5. **Plataformas de gestión de dispositivos:**
   - Sistemas de software que permiten registrar, autenticar, configurar y gestionar dispositivos IoT a gran escala.

6. **Middleware:**
   - Software que actúa como intermediario entre los dispositivos y las aplicaciones, facilitando la comunicación, la gestión de datos y la seguridad.

7. **Almacenamiento de Datos:**
   - Sistemas robustos para gestionar las enormes cantidades de datos generados por los dispositivos IoT.

8. **Análisis de Datos:**
   - Esencial para extraer información valiosa de los datos recopilados, utilizando técnicas de big data, aprendizaje automático y análisis predictivo.

9. **Seguridad y Privacidad:**
   - Áreas críticas que incluyen autenticación de dispositivos, cifrado de datos y protección contra ataques.

10. **Interfaces de Usuario (UI) y Experiencia del Usuario (UX):**
    - Aplicaciones y interfaces de usuario que permiten a las personas interactuar con los dispositivos IoT de manera intuitiva.

11. **Integración de Aplicaciones y Sistemas Empresariales:**
    - Fundamentales para aprovechar al máximo los datos generados por los dispositivos IoT en procesos empresariales.

12. **Energía Eficiente y Gestión de Energía:**
    - Esencial para dispositivos IoT, especialmente los que funcionan con baterías.

13. **Blockchain para Seguridad:**
    - Utilizado en ciertas aplicaciones IoT para garantizar la integridad y seguridad de los datos.

14. **Interoperabilidad:**
    - La capacidad de los dispositivos IoT y las aplicaciones para comunicarse y trabajar juntos de manera efectiva.

15. **Realidad Aumentada (AR) y Realidad Virtual (VR):**
    - Integradas con dispositivos IoT para proporcionar experiencias inmersivas y visualización de datos en tiempo real.

16. **Robótica IoT:**
    - Integración de IoT con la robótica para el control y monitoreo remotos de robots.

17. **Computación Cuántica:**
    - Exploración de aplicaciones de IoT que aprovechan la potencia computacional masiva de la computación cuántica.

18. **Automatización y Machine Learning:**
    - Utilización de la automatización y técnicas de machine learning para la toma de decisiones autónoma basada en datos recopilados por dispositivos IoT.

19. **Gestión de Flotas y Logística:**
    - Utilización de dispositivos IoT para rastrear vehículos, monitorear la carga y optimizar operaciones en tiempo real.

20. **Banda Estrecha IoT (NB-IoT) y LTE-M:**
    - Tecnologías de red inalámbrica diseñadas para dispositivos IoT que proporcionan conectividad de baja potencia y bajo costo.

21. **Holografía y Comunicación 5G:**
    - Utilización de tecnologías avanzadas de comunicación para transmitir datos e imágenes tridimensionales en tiempo real.

## Clasificación de los sensores

### Sensores de variables ambientales

- Sensor de temperatura: DS18B20, LM35, DHT11, DHT22.
- Sensor de humedad: DHT11, DHT22, HIH6130, HTU21D.
- Sensor de luz: LDR (Resistor Dependiente de la Luz), TSL2561, BH1750.
- Sensor de presión atmosférica: BMP180, BMP280, BMP388.
- Sensor de calidad del aire: MQ Series (por ejemplo, MQ-7 para CO, MQ-135 para NH3, CO2, etc.), CCS811.
- Sensor de gas: MQ Series (varios para diferentes gases), MiCS-5524.
- Sensor de sonido (Micrófono): MAX4466, KY-038, LM386.
- Sensor de radiación UV: SI1145, GYML8511.

### Sensores de variables físicas

- Sensor de movimiento (Acelerómetro): MPU6050, ADXL345, MMA8452Q.
- Sensor de inclinación (Giroscopio): MPU6050, L3GD20, ITG-3200.
- Sensor de fuerza: FSR (Resistor de fuerza sensible), Flexiforce.
- Sensor de presión: MPX5100, MPX5700, MS5803.
- Sensor de velocidad: Sensor de efecto Hall, Encoder.
- Sensor de proximidad: Sensor de proximidad infrarrojo (por ejemplo, SHARP GP2Y0A21YK).
- Sensor Magnético (Magnetómetro): HMC5883L, MAG3110, QMC5883L.

### Sensores de variables biológicas y de salud

- Sensor de ritmo cardíaco: Sensor de Pulso y Oxígeno en Sangre (por ejemplo, MAX30100).
- Sensor de oxígeno en sangre (Pulsioxímetro): MAX30100, MAX30102.
- Sensor de glucosa: No invasivo - actualmente en desarrollo.
- Sensor de electroencefalograma (EEG): Muse Headband, NeuroSky MindWave.
- Sensor de electromiografía (EMG): MyoWare Muscle Sensor, Grove - Muscle Sensor V3.
- Sensor de temperatura corporal: DS18B20 (también usado para temperatura ambiente).
- Sensor de sudor (GSR): Grove - GSR Sensor.

### Sensores de variables químicas

- Sensor de pH: Sensor de pH analógico o digital.
- Sensor de Conductividad: Sensor de Conductividad.
- Sensor de Redox: Electrodo de Redox.

### Sensores de variables de posición y ubicación

- Sensor de GPS: Módulos GPS como el UBlox NEO-6M.
- Sensor de Posición (Acelerómetro y Giroscopio): MPU6050, LSM9DS0.

### Sensores de variables de movimiento y objetos

- Sensor de peso: Celdas de carga (por ejemplo, HX711 se usa para la interfaz).
- Sensor de vibración: Sensor de Vibración (por ejemplo, SW-420).
- Sensor de objetos (Ultrasonido): HC-SR04, JSN-SR04T.

## Clasificación de los actuadores

### Actuadores Eléctricos

- Motores eléctricos: Controlan el movimiento lineal o rotativo de dispositivos.
- Solenoide: Dispositivo electromagnético que convierte energía eléctrica en movimiento mecánico lineal.
- Relés: Interruptores electromagnéticos utilizados para controlar dispositivos de alto voltaje con señales de bajo voltaje.

### Actuadores electrónicos

- Transistores: Componentes semiconductores esenciales para el control y la amplificación de señales eléctricas.
- Interruptores de estado sólido (SSR): Dispositivo de conmutación electrónico que utiliza componentes semiconductores para realizar funciones de un relé tradicional sin partes móviles.
- Triacs: Dispositivos electrónicos de control de potencia para corriente alterna (AC).

### Actuadores mecánicos

- Válvulas: Controlan el flujo de líquidos o gases en sistemas.
- Bombas: Generan flujo en sistemas de fluidos.
- Ventiladores: Controlan la circulación de aire en sistemas de refrigeración o calefacción.

### Actuadores piezoeléctricos

- Piezoeléctricos: Generan movimiento cuando se aplica voltaje, utilizados en micrófonos, altavoces y dispositivos de enfoque automático.

## Actuadores neumáticos/hidráulicos

- **Cilindros Neumáticos:**
  - Generan movimiento lineal utilizando aire comprimido.

- **Cilindros Hidráulicos:**
  - Generan movimiento lineal utilizando fluido hidráulico a alta presión.

- **Válvulas Neumáticas/Hidráulicas:**
  - Controlan el flujo de aire o fluido en sistemas neumáticos o hidráulicos.

## Actuadores ópticos

- **Moduladores ópticos:**
  - Controlan la intensidad, fase o polarización de la luz para aplicaciones en comunicaciones ópticas y sensores.

- **Interruptores ópticos:**
  - Permiten el paso o bloqueo de luz para aplicaciones en sensores y sistemas de detección.

## Actuadores biológicos (Bio Actuadores)

- **Músculos artificiales:**
  - Dispositivos que imitan el funcionamiento de los músculos humanos para aplicaciones en robótica y prótesis.

- **Bioestimuladores:**
  - Dispositivos que interfieren con señales eléctricas en el cuerpo humano para aplicaciones médicas.

## Actuadores robóticos

- **Servomotores:**
  - Motores de alta precisión utilizados en robótica para controlar posición y velocidad.

- **Actuadores lineales:**
  - Generan movimiento lineal en aplicaciones robóticas y de automatización.

## Actuadores inteligentes

- **Actuadores MEMS (Sistemas microelectromecánicos):**
  - Dispositivos miniaturizados que integran componentes mecánicos y electrónicos en un chip, utilizados en aplicaciones como acelerómetros y micromirrors.

## Actuadores Químicos

- **Celdas Electroquímicas:**
  - Generan energía a través de reacciones químicas, utilizadas en baterías y pilas de combustible.

- **Actuadores a Base de Polímeros:**
  - Cambian de forma en respuesta a estímulos químicos, utilizados en dispositivos biomédicos y sensores.
