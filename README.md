# Trabajo-Extra

<div align="center">

# UNIVERSIDAD DE LAS FUERZAS ARMADAS ESPE
  
![image](https://user-images.githubusercontent.com/84430867/132457003-33aea563-56cd-4d01-9eaa-ef155aec6496.png)

NOMBRE

Aimacaña Cruz Alex Jhosue

NRC
  
5418

INGENIERO

Ing. Darwin Omar Alulema Flores

# Ejemplo para simular una red IoT con CupCarbon
  
</div>

# 1.OBJETIVOS

Objetivos Generales

Proponer un estudio del modelo smart city que sirva como base para futuros proyectos en la ciudad, con el fin de establecer una fuente de investigación que impulse a la investigación, desarrollo de soluciones y aplicativos smart para el bienestar de sus habitantes, a través de una demostración de una red de sensores utilizando el software CupCarbon. 

Objetivos Específicos

- Definir propiamente el concepto de una ciudad smart.
- Concientizar sobre los beneficios y ventajas del modelo smart.
- Implementación y demostración de la red de sensores por medio delsoftware CupCarbon. 

# 2. MARCO TEORICO

<div align="center">
  
**CupCarbon**
  
![image](https://user-images.githubusercontent.com/84430867/132935514-e74168b7-feb2-47c7-81f2-6ac230d422ec.png)

</div>

**2.1. ¿Qué es CupCarbon?**

CupCarbon es un sensor inalámbrico de Smart City e Internet de las cosas (IoT) Simulador de red (SCI-WSN). Su objetivo es diseñar, visualizar, depurar y validar algoritmos distribuidos para monitoreo, recopilación de datos ambientales, etc., y para crear escenarios como incendios, gas, móviles y, en general, dentro de proyectos educativos y científicos. No solo puede ayudar a visualizar explicar los conceptos básicos de las redes de sensores y cómo funcionan; también puede ayudar a los científicos a probar sus topologías inalámbricas, protocolos, etc.

CupCarbon ofrece dos entornos de simulación.

- El primero es el entorno de simulación permite el diseño de escenarios de movilidad. y la generación de eventos naturales como incendios y gas así como la simulación de móviles como vehículos y vuelos objetos (por ejemplo, vehículos aéreos no tripulados, insectos, etc.).
- El segundo entorno de simulación representa una simulación de eventos discretos de redes de sensores que tienen en cuenta el escenario diseñado sobre la base del primer entorno.

Las redes se pueden diseñar y crear prototipos mediante una interfaz ergonómica y fácil de usar utilizando OpenStreetMap (OSM) marco para desplegar sensores directamente en el mapa. Incluye un script llamado SenScript, que permite programar y programar configurar cada nodo sensor individualmente. A partir de este script, también es posible generar códigos para plataformas de hardware como como Arduino / XBee. Esta parte no está completamente implementada en CupCarbon, permite generar códigos para redes simples y algoritmos.

**Partes del CupCarbon**

<div align="center">
  
![image](https://user-images.githubusercontent.com/84430867/133011509-f44dde2b-c313-4d07-8505-66de53ecff0b.png)

</div>

La interfaz gráfica de usuario (GUI) de CupCarbon se compone de las siguientes seis partes:

1. El mapa (en el centro)
2. La barra de menú (en la parte superior)
3. La barra de herramientas (debajo del menú)
4. El menú de parámetros (a la izquierda)
5. La barra de estado (en la parte inferior)
6. La consola

**2.2 ¿Qué es el IoT?**

Internet of Things (IoT) describe la red de objetos físicos (cosas) que incorporan sensores, software y otras tecnologías con el fin de conectar e intercambiar datos con otros dispositivos y sistemas a través de Internet. Estos dispositivos van desde objetos domésticos comunes hasta herramientas industriales sofisticadas. Con más de 7 mil millones de dispositivos IoT conectados en la actualidad, los expertos prevén que este número aumente a 10 mil millones para 2020 y 22 mil millones para 2025. Oracle cuenta con una red de partners de dispositivos.

La implementación de varios nodos de IoT es muy difícil, costosa, demorada y puede ser imposible cuando los nodos tienen que ser reprogramados frecuentemente o cuando los nodos se implementan en lugares distantes, por ejemplo, en diferentes ciudades o países.

Así, el uso de software para simular la implementación, reconfiguración y monitoreo de los algoritmos de comunicación de esas redes son muy prácticos y útiles en determinadas fases de un proyecto. La plataforma “CupCarbon” fue desarrollado para este propósito.

**2.3 ¿Qué es una ciudad smart?**

Son aquellas en las que se aplican las tecnologías de la información y de la comunicación (TIC) con el objetivo de proveerlas de infraestructuras que garanticen:

- Un desarrollo sostenible.
- Un incremento de la calidad de vida de los ciudadanos.
- Una mayor eficacia de los recursos disponibles.
- Una participación ciudadana activa.
 
La Smart City nace de la necesidad de mantener una armonía entre todos estos aspectos.

Se prevé que en el 2050 un 85% de la población mundial viva en ciudades. Este hecho hace que en las siguientes décadas los núcleos urbanos tengan que afrontar un número creciente de problemas ligados a este hecho, como:

- El abastecimiento energético.
- Las emisiones de CO2.
- La planificación del tráfico automovilístico.
- La provisión de bienes y materias primas.
- La prestación de servicios sanitarios y de seguridad a todos quienes residan en estos enormes y masificados centros de población.

# 3. DESARROLLO

Para iniciar con nuestra simulación vamos a iniciar descargandonos **CupCarbon**, es un simulador para smartcities y una red de sensores (WSN). Una versión gratuita del simulador está disponible en línea; el software se ha desarrollado en JAVA y no necesita instalación. Sólo tienes que descomprimir el archivo ZIP a una carpeta que prefieras y abrir el archivo “cupcarbon.jar”. Por supuesto, para eso necesita una versión de JAVA instalada.

Link: de descarga: http://cupcarbon.com/

![image](https://user-images.githubusercontent.com/84430867/132935499-8f7ca10a-418a-4052-90cb-b296ae5195ff.png)

**- SIMULACIÓN DE SENSORES**

Vamos a simular una red Ad-Hoc Vehicular donde existen una comunicación entre varios sensores.

Una red ad-hoc vehicular, habitualmente referida por su acrónimo en inglés VANET, es un tipo de red de comunicación que utiliza a los vehículos como nodos de la red. Dado el reducido alcance del canal de comunicación, la conectividad se establece de forma esporádica.

1. Creamos un nuevo proyecto

![image](https://user-images.githubusercontent.com/84430867/133003873-e8d5d7aa-c21a-4ae9-b27b-a06397107ef2.png)

2. Agregamos sensores IOT

![image](https://user-images.githubusercontent.com/84430867/133003925-f24d94e3-066d-4c51-90e4-ce2b02eda92d.png)

En este caso vamos agregar 4 sensores subscriptores y 1 publicador.

3. Creamos un Script

![image](https://user-images.githubusercontent.com/84430867/133004060-ebc9a096-fbcd-43fb-a88c-19c3974c3b5f.png)

Aquí generamos los códigos para el:

- Publicador

<div align="center">
  
![image](https://user-images.githubusercontent.com/84430867/133004088-0317895e-7bd7-4f61-ba54-d4610aa82d69.png)

</div>

El cual nos dice que cada 2 segundos el sensor va a quedar activado y desactivado es decir va a cambiar de color verde a azul, este código puede ser modificable.

- Suscriptor

<div align="center">
    
![image](https://user-images.githubusercontent.com/84430867/133004109-885a458e-ef15-4108-a724-953867b0e56f.png)

</div>

Aquí llamamos al sensor de la misma manera cada 1 segundo va a enviar la información al publicador.

4. Agregamos los sensores 

- Suscriptores

<div align="center">
  
![image](https://user-images.githubusercontent.com/84430867/133004210-15458396-3772-4d4b-828c-4bfff12a4df4.png)

![image](https://user-images.githubusercontent.com/84430867/133004238-84abda91-e4d5-4299-acdb-69f8b60dbcc4.png)

![image](https://user-images.githubusercontent.com/84430867/133004258-b6e74517-6834-40e6-a2cf-2c57672e5a8e.png)

</div>

- Publicador

<div align="center">
  
![image](https://user-images.githubusercontent.com/84430867/133004270-93e34ba2-3e60-41f2-bb66-951a79b5a9ad.png)

![image](https://user-images.githubusercontent.com/84430867/133004277-1d85108c-2a28-4626-ba4b-4a26c99983f0.png)

![image](https://user-images.githubusercontent.com/84430867/133004283-75ddf21c-2e88-4cb6-86dc-7003e7e160d7.png)

</div>

5. Ejecutamos

![image](https://user-images.githubusercontent.com/84430867/133004313-6b178dca-be85-460b-afef-b164628e60da.png)

Cada 2 segundo se apagan y se prenden los sensores, los que se prenden son los subscriptores. 

Incluso podemos tener nuestro **Broken** para poder realizar la conexión mediante MQTT, donde nos piden Usuario y Contraseña.

<div align="center">
  
![image](https://user-images.githubusercontent.com/84430867/133004460-4918ffdb-e6cc-4006-8aa6-278e5d95e393.png)

</div>

# 4. VIDEO

# 5. CONCLUSIONES

- Las Redes VANET son redes inalámbricas creadas con el propósito de establecer comunicación en tiempo real entre vehículos con el fin de prevenir accidentes de tránsito y de mejorar la seguridad de los usuarios. La creación de redes Ad-Hoc Vehiculares logran una alta confiabilidad, escalabilidad y seguridad, por lo que se presenta a esta tecnología como una nueva técnica a ser estudiada.
- La simulación de CupCarbon se basa en la capa de aplicación de los nodos. Esto lo convierte en un verdadero complemento de los simuladores. No simula todas las capas de protocolo debido a la naturaleza compleja de las redes urbanas que necesitan incorporar otra información compleja y que consume recursos, como edificios, carreteras, movilidad, señales, etc.
- Se presenta un simulador, CupCarbon, para el diseño y estudio de redes de sensores inalámbricos. El objetivo principal de este simulador es educativo. Demuestra el uso de sensores inalámbricos en casi las mismas condiciones que en el mundo real. El simulador también se puede usar para calcular el diagrama de energía de cada sensor.
- CupCarbon es un software relativamente nuevo, así que el alcance total aún no está determinado; debido a esto, este programa es parte del proyecto de investigación PERSEPTEUR siendo respaldado y financiado por la French Agence Nationale de la Recherche ANR bajo la referencia ANR-14-CE24-0017- 01, pero aún no se tiene un manual de usuario lo suficientemente robusto para el programa, aparte de que es bastante inestable.

# 6. BIBLIOGRAFÍAS

endesa. (s.f.). Obtenido de Smart Cities: https://www.fundacionendesa.org/es/recursos/a201908-smart city#:~:text=Son%20aquellas%20en%20las%20que,eficacia%20de%20los%20recursos%20disponibles.

ORACLE. (s.f.). Obtenido de ¿Qué es Internet of Things (IoT)?: https://www.oracle.com/mx/internet-of-things/what-is-iot/

