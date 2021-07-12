# Módulo 1: Descripción de los conceptos básicos de Azure
##  Introducción a los aspectos básicos de Azure

---

**¿Por que son importantes los aspectos básicos?**  
Esta seccion es la que proporciona el inicio y la base fundamental para trabajar con la nube y una total
comprensión de Azure. 

---

### ☁️ Informática en la nube
La informática en la nube es la entrega de servicios informáticos a través de Internet, lo que se conoce como la nube. Ofrece
una innovación más rápida, recursos flexibles y economías de escala.

La ventaja de la nube radica en la prestación de servicios por medio de **Internet** donde se paga en base al **uso**, teniendo los servicios _a la mano_ y con la posibilidad de cambiar y adaptarse en base a las necesidades y evitando el uso de una infraestructura de gran costo, es decir, nos ayuda a reducir _costos operativos_. 

---

En otras palabras, la **informática en la nube** es una forma de **alquilar** servicios de un centro de datos de terceros, donde al finalizar el uso de dichos servicios, se *devuelven* y se cobra solo por su **uso**.

---

Ademas de contar con una rapidez sorprendente, la nube proporciona **innovación**, la cual ayuda a realizar tareas con un proposito en particular y resolver diversas situaciones que antes no se podia, un ejemplo de esto son las aplicaciones de la Inteligencia Artificial 🤖 y el Internet de las Cosas 📱🏘️

### Azure
Azure es una plataforma de **informatica en la nube** con un conjunto de servicios que se amplia continuamente para ayudarle a crear soluciones que satisfagan los objetivos empresariales. Proporciona una gran cantidad de servicios basados en la nube, ademas de nuevas funcionalidades como Inteligencia Artificial (IA) e Internet de las Cosas (IoT). Ayuda a la organización a cumplir los desafíos empresariales, tanto actuales como futuros.

#### ✅ Ventajas

 - ##### Innovación
Como se menciono anteriormente, una ventaja que proporciona la nube es tener servicios con un gran grado de innovación, Azure esta **preparado para el futuro**, es decir, Microsoft ofrece una innovación continua para apoyar el desarrollo de proyectos futuros.

 - ##### Variedad de opciones
Admite codigo abieto, todos los lenguajes y marcos, donde se puede compilar e implementar como y donde el usuario desee.

- ##### Entorno Híbrido
El usuario puede operar en un entorno local, en la nube o en un entorno perimetral, ofreciendo herramientas y servicios diseñados para trabajar con una nube híbrida.

- ##### Confianza y Seguridad
Azure proporciona seguridad respaldada por un equipo de expertos y un cumplimiento proactivo de confianza para empresas y gobiernos.

- ##### Servicios
Azure proporciona más de 100 servicios que permiten hacer diversas tareas, donde se incluyen servicios del area de computo, base de datos, almacenamiento, redes, IA e IoT.

#### ⚙️Funcionamiento

Azure utiliza una tecnologia conocida como [virtualización](https://github.com/SofiaGaytan/RetoMaster/blob/main/ContenidoAdicional/Glosario.md#virtualizaci%C3%B3n), el cual se encarga de separar el estrecho acoplamiento existente entre el hardware de un equipo,
donde asume esta tecnología y la repite a gran esacala en centros de datos de Microsoft en todo el mundo que tiene servidores y cada servidor tiene un [hipervisor](./ContenidoAdicional/Glosario.md#hipervisor)
para ejecutar varias máquinas virtuales. Todos estos servidores se conectan por medio de un [conmutador](https://github.com/SofiaGaytan/RetoMaster/blob/main/ContenidoAdicional/Glosario.md#conmutador), donde cada servidor ejecuta un [controlador de tejido](https://github.com/SofiaGaytan/RetoMaster/blob/main/ContenidoAdicional/Glosario.md#controlador-de-tejido),
estos a su vez se conectan a un [orquestador](https://github.com/SofiaGaytan/RetoMaster/blob/main/ContenidoAdicional/Glosario.md#orquestador).

Cuando un usuario realiza una solicitud para crear una [máquina virtual](https://github.com/SofiaGaytan/RetoMaster/blob/main/ContenidoAdicional/Glosario.md#m%C3%A1quina-virtual), el orquestador es el responsable de empaquetar todo lo que es necesario eligiendo el mejor [bastidor](https://github.com/SofiaGaytan/RetoMaster/blob/main/ContenidoAdicional/Glosario.md#bastidor) de servidores,
para despues enviar dicho paquete y la solicitud al controlador de tejido, donde el controlador de tejido sera el encargado de crear la VM. Una vez creada la VM, el usuario podra conectarse.

---


⏯️ La información anterior fue recopilada del [video sobre funcionamiento de Azure](https://www.microsoft.com/es-es/videoplayer/embed/RWlzQ6?postJsllMsg=true&autoCaptions=es-es).

---

### Azure Portal

Es la manera gráfica de administrar la subscripción de Azure. Esta diseñado para proporcionar resistencia y disponibilidad continua, ya que mantiene una presencia en todos los centros de datos de Azure, ademas de que se encuentra en constante actualización e implementa una forma continua, ya que no requiere tiempo de inactividad para el mantenimiento.

### Azure Marketplace

Es la conexión entre los usuarios y los partners de Microsoft, proveedores de software independientes y nuevas empresas que ofrecen sus soluciones y servicios certificados para ejecutarse en Azure. Proporciona un catalogo de soluciones que abarcan diversas categorias.

---

**Enlace al módulo del Challenge**  
[Introducción a los aspectos básicos de Azure](https://docs.microsoft.com/es-es/learn/modules/intro-to-azure-fundamentals/?WT.mc_id=cloudskillschallenge_9d729b5a-9842-4f33-a7e7-7e9c106005e1&ns-enrollment-type=Collection&ns-enrollment-id=ddkzhjzxppdk)

---

&nbsp;

◀️ Anterior: [Inicio](https://github.com/SofiaGaytan/RetoMaster#reto-master-)  
▶️ Siguiente: [Descripción de los componentes principales de la arquitectura de la arquitectura de Azure](./Modulo1/Modulo1_2.md)

📍 [Inicio](https://github.com/SofiaGaytan/RetoMaster#reto-master-)  
🗃️ [Glosario](./ContenidoAdicional/Glosario.md)
