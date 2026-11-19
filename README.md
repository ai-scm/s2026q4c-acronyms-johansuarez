# Conceptos de Ingeniería de Software

## RAG (Retrieval-Augmented Generation)

**Concepto:** Es una técnica de inteligencia artificial que combina modelos 
generativos con mecanismos de recuperación de información de fuentes externas, 
como bases de datos o documentos empresariales. Su objetivo es generar respuestas 
más precisas, actualizadas y contextualizadas, sin necesidad de volver a entrenar 
el modelo de inteligencia artificial.

**Caso de uso:** Un chatbot empresarial que consulta documentación interna 
para resolver dudas de los clientes, reduciendo los costos de atención y los 
tiempos de respuesta.

## CAP (Consistency, Availability, Partition Tolerance)

**Concepto:** Es un teorema de los sistemas distribuidos que establece que no 
es posible garantizar simultáneamente la consistencia, la disponibilidad y la 
tolerancia a particiones. Cuando ocurre una interrupción en la 
comunicación entre los nodos, el sistema debe priorizar entre mantener la 
consistencia de los datos o continuar respondiendo a las solicitudes.

**Caso de uso:** Una entidad bancaria que prioriza la consistencia sobre la 
disponibilidad para evitar inconsistencias en los saldos y pérdidas económicas.

## EDA (Event-Driven Architecture)

**Concepto:** Es un estilo de arquitectura de software en el que los componentes 
de un sistema se comunican mediante la producción y el consumo de eventos. Estos 
eventos representan acciones o cambios de estado que pueden desencadenar otros 
procesos, permitiendo una comunicación generalmente asíncrona y reduciendo el 
acoplamiento entre los componentes del sistema.

**Caso de uso:** Una tienda virtual que, al recibir una compra, activa 
automáticamente los procesos de facturación, inventario y envío, mejorando 
la eficiencia operativa.

## DDD (Domain-Driven Design)

**Concepto:** Es un enfoque de diseño de software que centra el desarrollo 
del sistema en el dominio del negocio, sus necesidades, procesos y reglas. 
Promueve la colaboración entre desarrolladores y expertos del negocio mediante 
un lenguaje común, permitiendo construir soluciones que representen de manera 
más adecuada la realidad de la organización.

**Caso de uso:** Una aseguradora que organiza su software según sus dominios 
de negocio, como pólizas y reclamaciones, facilitando la implementación de 
nuevos productos.

## BFF (Backend for Frontend)

**Concepto:** Es un patrón de arquitectura de software que propone implementar 
un backend específico para cada tipo de frontend. De esta manera, cada 
interfaz puede recibir únicamente la información y las funcionalidades que 
necesita, permitiendo optimizar la comunicación, el rendimiento y la 
experiencia de usuario en los diferentes canales.

**Caso de uso:** Un banco que utiliza backends independientes para su 
aplicación móvil y su portal web, mejorando la experiencia del cliente 
en cada canal.

## SOLID (Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, Dependency Inversion)

**Concepto:** Es un conjunto de cinco principios de diseño de software 
orientado a objetos que buscan mejorar la calidad y mantenibilidad del código. 
Estos principios promueven la separación de responsabilidades, la extensión 
de funcionalidades, la correcta sustitución de componentes, la definición 
de interfaces específicas y la reducción de dependencias entre clases.

**Caso de uso:** Una empresa de comercio electrónico que incorpora nuevos 
métodos de pago sin afectar los existentes, reduciendo los costos de 
desarrollo y mantenimiento.

## JWT (JSON Web Token)

**Concepto:** Es un estándar abierto que permite transmitir información 
entre diferentes sistemas mediante tokens compactos en formato JSON. Estos 
tokens pueden estar firmados digitalmente para verificar su autenticidad 
e integridad, y son utilizados principalmente en mecanismos de autenticación 
y autorización para controlar el acceso a los recursos de una aplicación.

**Caso de uso:** Una plataforma empresarial que permite a sus usuarios 
acceder a diferentes servicios mediante una misma sesión, simplificando 
la gestión de accesos y mejorando la experiencia de usuario.

## XSS (Cross-Site Scripting)

**Concepto:** Es una vulnerabilidad de seguridad presente en aplicaciones 
web que permite a un atacante inyectar y ejecutar scripts maliciosos en el 
navegador de otros usuarios. Generalmente ocurre cuando una aplicación 
procesa información no confiable sin aplicar mecanismos adecuados de 
validación, sanitización o codificación de salida, comprometiendo la 
seguridad de los usuarios.

**Caso de uso:** Una tienda virtual que implementa mecanismos de prevención 
contra XSS para proteger la información de sus clientes, evitando pérdidas 
económicas y daños reputacionales.
