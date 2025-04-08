# 2.1 DEFINICIONES BÁSICAS

## 🌐 **Amenaza**
Una **amenaza** es cualquier circunstancia o evento potencial que puede dañar la integridad, disponibilidad o confidencialidad de un sistema informático o los datos que maneja. Las amenazas pueden provenir de diversas fuentes, tanto internas como externas, y pueden manifestarse de distintas formas, tales como ciberataques, desastres naturales, errores humanos, fallos tecnológicos o mal uso de los sistemas. Las amenazas pueden ser intencionadas, como un ataque cibernético, o no intencionadas, como un fallo de hardware.

## 🛡️ **Vulnerabilidad**
Una **vulnerabilidad** es una debilidad o fallo en un sistema, red o aplicación que puede ser aprovechada por una amenaza para comprometer la seguridad. Estas vulnerabilidades pueden estar presentes en el software, en la configuración del sistema, en las redes, en el comportamiento de los usuarios o en la infraestructura física. Las vulnerabilidades pueden ser causadas por defectos en el diseño del sistema, implementación incorrecta de software, falta de actualizaciones de seguridad o falta de formación de los usuarios.

## ⚠️ **Riesgo**
El **riesgo** es la probabilidad de que una amenaza explote una vulnerabilidad y cause un impacto negativo en los activos de la organización. El riesgo se evalúa considerando dos factores clave: la probabilidad de que ocurra un ataque y el impacto que este tendría si se materializa. Las organizaciones gestionan el riesgo mediante el control de las vulnerabilidades y la protección frente a las amenazas, implementando medidas de seguridad adecuadas para reducir tanto la probabilidad como el impacto.

## 🖤 **Caja negra**
El análisis de **caja negra** se refiere a un enfoque de pruebas de seguridad en el que el evaluador no tiene conocimiento previo sobre el sistema, red o aplicación que está siendo evaluado. Este enfoque simula un ataque de un hacker externo que no posee información interna sobre la infraestructura, lo que representa cómo un atacante real podría intentar explotar las vulnerabilidades del sistema sin acceso a detalles internos. Las pruebas de caja negra se realizan sin ningún acceso a los códigos fuente o arquitectura de la red.

## 🤍 **Caja blanca**
En contraste con la **caja negra**, el análisis de **caja blanca** es un enfoque en el que el evaluador tiene acceso completo a toda la información interna del sistema, red o aplicación, incluyendo códigos fuente, configuraciones y arquitectura. Este enfoque permite a los evaluadores realizar un análisis profundo del sistema y detectar vulnerabilidades que podrían no ser evidentes en un análisis externo, ya que tienen visibilidad completa de los posibles puntos débiles dentro del código y las configuraciones internas.

## ⚪ **Caja gris**
El análisis de **caja gris** es un enfoque intermedio entre la caja negra y la caja blanca. En este tipo de pruebas, el evaluador tiene un acceso limitado a información interna del sistema, pero no tiene conocimiento total, como en el caso de la caja blanca. Este enfoque simula un atacante que puede tener algunos conocimientos o accesos, pero no la visibilidad completa del sistema, como podría ser un empleado con privilegios limitados o un atacante que ha logrado obtener información parcial.

# 2.2 TIPOS DE ANÁLISIS DE SEGURIDAD

## 🔍 **Ethical Hacking**
El **ethical hacking** o hacking ético es la práctica de realizar pruebas de seguridad en sistemas informáticos de manera autorizada para identificar y corregir vulnerabilidades antes de que puedan ser explotadas por atacantes malintencionados. Los hackers éticos son profesionales que utilizan las mismas herramientas y técnicas que los atacantes, pero con el objetivo de mejorar la seguridad de la organización y protegerla de posibles amenazas. Estas pruebas se realizan siempre con el consentimiento explícito de la organización propietaria del sistema.

## 🔐 **Penetration Testing (Pentesting)**
El **penetration testing** o **pentesting** es un tipo de prueba de seguridad controlada y autorizada que simula un ataque cibernético real con el fin de identificar las vulnerabilidades en los sistemas. A diferencia del ethical hacking, el pentesting se centra en un conjunto específico de objetivos (como una red, una aplicación web o un sistema) y tiene un alcance definido, buscando explotar vulnerabilidades para evaluar la seguridad del sistema desde la perspectiva de un atacante.

## 💥 **Red Teaming**
El **Red Teaming** es un enfoque de pruebas de seguridad que va más allá del pentesting, al simular un ataque real y continuo contra la organización utilizando múltiples vectores de ataque (tecnológicos, humanos y físicos). Los equipos de **Red Team** se comportan como atacantes reales y buscan vulnerabilidades en todo el entorno organizacional, desde los sistemas informáticos hasta los procedimientos de seguridad física, para evaluar la capacidad defensiva de la organización frente a ataques sofisticados y avanzados.

## 📝 **Análisis de vulnerabilidades**
El **análisis de vulnerabilidades** es el proceso de escanear, identificar y evaluar posibles vulnerabilidades en los sistemas, redes o aplicaciones. Utilizando herramientas automatizadas y técnicas manuales, el análisis busca detectar puntos débiles que puedan ser explotados por atacantes. El objetivo es proporcionar a la organización una lista detallada de las vulnerabilidades encontradas, clasificadas por su gravedad, para poder implementar medidas correctivas y mejorar la seguridad general.

## 🧐 **Auditoría de seguridad**
La **auditoría de seguridad** es una revisión detallada y estructurada de los controles de seguridad implementados en una organización. A través de una auditoría de seguridad, se evalúan las políticas, procedimientos y prácticas de seguridad para garantizar que se están cumpliendo los estándares y normativas vigentes. Esta auditoría también busca identificar brechas en la seguridad que puedan permitir ataques o filtraciones de datos, así como proponer medidas correctivas para mitigar esos riesgos.

# 2.3 TIPOS DE PENTESTING

## 🌐 **Network**
El **pentesting de Network** se enfoca en evaluar la seguridad de las redes de comunicación, tanto internas como externas, buscando vulnerabilidades que permitan a un atacante infiltrarse en los sistemas de la organización o interceptar la comunicación entre dispositivos. Las pruebas de pentesting de red incluyen la exploración de puertos, análisis de tráfico y la evaluación de la seguridad de los dispositivos de red.

## 💻 **Client-Side**
El **Client-Side Pentesting** se centra en evaluar las vulnerabilidades en los dispositivos cliente, como ordenadores de escritorio, laptops, dispositivos móviles y otros puntos finales. Este tipo de pentesting se enfoca en la seguridad de las aplicaciones, sistemas operativos y configuraciones de usuario en los dispositivos utilizados por las personas dentro de la organización.

## 🌍 **Web**
El **pentesting web** se enfoca en probar las aplicaciones web y sus infraestructuras para identificar vulnerabilidades comunes, como inyecciones SQL, Cross-Site Scripting (XSS), Cross-Site Request Forgery (CSRF), y problemas de autenticación. El objetivo es garantizar que las aplicaciones web sean seguras y protejan los datos sensibles que los usuarios transmiten a través de ellas.

## 📶 **Wireless**
El **pentesting wireless** implica la evaluación de las redes inalámbricas, como las conexiones Wi-Fi, para identificar vulnerabilidades en su configuración, como contraseñas débiles, falta de cifrado adecuado o redes mal configuradas. El objetivo es proteger las comunicaciones inalámbricas y garantizar que los atacantes no puedan interceptar o manipular los datos transmitidos.

## 🎭 **Ingeniería social**
El **pentesting de ingeniería social** se enfoca en evaluar las defensas humanas de la organización, simulando técnicas de manipulación psicológica utilizadas por los atacantes para obtener acceso a información confidencial. Esto puede incluir ataques de phishing, pretexting (suplantación de identidad) o técnicas de manipulación telefónica.

## 🏢 **Físico**
El **pentesting físico** pone a prueba la seguridad física de la organización, evaluando la capacidad de los atacantes para acceder a las instalaciones, robar equipos o manipular dispositivos de hardware para obtener acceso no autorizado a los sistemas. Las pruebas incluyen la revisión de controles de acceso, cerraduras, sistemas de cámaras de seguridad y otros mecanismos de seguridad física.

# 2.4 METODOLOGÍAS

## 📝 **Penetration Testing Execution Standard (PTES)**
El **Penetration Testing Execution Standard (PTES)** es un marco de trabajo para la realización de pruebas de penetración. Define una serie de pasos estandarizados para llevar a cabo un pentest, desde la planificación y el reconocimiento hasta el análisis y la presentación de resultados. El PTES proporciona una guía detallada para garantizar que las pruebas sean efectivas y completas.

## 🛡️ **OWASP Testing Guide**
La **OWASP Testing Guide** es un conjunto de directrices de pruebas de seguridad específicamente orientadas a aplicaciones web, desarrollado por la Open Web Application Security Project (OWASP). La guía establece un enfoque estructurado para identificar y evaluar vulnerabilidades en aplicaciones web, y proporciona recomendaciones sobre cómo protegerlas de amenazas comunes.

# 2.5 FASES DE UN PENTEST

## 🔍 **Fase de preparación**
La **fase de preparación** es la etapa inicial del pentest, en la que se define el alcance de la prueba, se identifican los objetivos, se obtienen los permisos necesarios y se establecen los métodos y herramientas que se utilizarán en el análisis. También se lleva a cabo una recopilación preliminar de información.

## ⚙️ **Fase de ejecución**
Durante la **fase de ejecución**, los pentesters realizan las pruebas y técnicas de explotación para identificar y explotar vulnerabilidades en el sistema objetivo. Esta fase puede incluir escaneos de red, ataques de ingeniería social, pruebas de aplicaciones web, entre otros métodos.

## 📊 **Fase de presentación de resultados**
La **fase de presentación de resultados** involucra la preparación de un informe detallado que describe las vulnerabilidades encontradas, su gravedad, las técnicas utilizadas para explotarlas y las recomendaciones para remediarlas. El informe suele incluir un resumen ejecutivo y una lista priorizada de las vulnerabilidades que requieren atención inmediata.