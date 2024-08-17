# **Arquitectura de Software**

### **Visión General**

La arquitectura de nuestro sistema está diseñada para ser escalable, modular y adaptable, con el objetivo de facilitar la gestión de grants abstrayendose del ecosistema. La arquitectura es capaz de integrarse con múltiples blockchains, lo que permite a nuestra plataforma expandirse de manera eficiente a otros ecosistemas en futuras iteraciones. Aquí se presenta una descripción detallada de cada componente de la arquitectura del MVP, donde nos integraremos con el ecosistema de Polkadot.

### **Descripción General de la Arquitectura**

El sistema se basa en una arquitectura de microservicios desacoplada, donde cada componente tiene responsabilidades específicas y se comunica con los demás a través de APIs REST. El **Frontend Web** construido con **React/Next.js** interactúa con un **Middlend** que centraliza la lógica de negocio y las solicitudes de los usuarios. El Middlend luego se comunica con una serie de APIs especializadas que gestionan diferentes aspectos de la aplicación, como usuarios, comunidades, grants, interacción con la blockchain de Polkadot, y almacenamiento descentralizado.

Este diseño modular permite que cada componente funcione de manera independiente, facilitando su escalabilidad y el mantenimiento del sistema. La arquitectura está pensada para ser extensible, lo que significa que podemos integrar nuevas blockchains y tecnologías de almacenamiento descentralizado a medida que evolucionan las necesidades del producto.

![imagen](https://github.com/user-attachments/assets/35870a82-e631-405b-bed0-3c8356970982)

## **Frontend Web**

**Tecnología Utilizada:**

- **Framework:** React.js/Next.js
- **Lenguaje:** JavaScript/TypeScript

**Descripción:**

- El Frontend es la parte del sistema con la que el usuario interactúa directamente, diseñada para ofrecer una interfaz de usuario intuitiva y amigable.
- Se encarga de mostrar la información al usuario y de manejar las interacciones con el sistema, como la creación de cuentas, la gestión de grants, y la conexión de wallets.
- Todo este sistema será implementado siguiendo al detalle el [diseño realizado en Figma](https://www.figma.com/design/YGSJZ8mZAEDub3MOxKoCrE/glocal.xyz?node-id=0-1&t=MbkAVRg5shmPWiCg-1).
- Este frontend será una aplicación web responsive accesible desde cualquier dispositivo (celular o computadora) sin necesidad de descargar una app para garantizar la mayor accesibilidad a nuestros usuarios.
- En el MVP la aplicación estará disponible en español, pero contará con soporte multidioma para dar acceso a múltiples comunidades globales.

**Interacción con el Sistema:**

- **Middlend:** El Frontend se comunica con el Middlend. Todas las solicitudes del usuario, como el login, la gestión de grants, o la creación de comunidades, son enviadas al Middlend, que se encarga de procesarlas. Todas las comunicaciones del frontend con otras partes del sistema se realizan a través del middlend, ninguna comunicación con otro sistema se realiza directamente desde el frontend.

## **Middlend**

**Tecnología Utilizada:**

- **Framework:** Node.js (Express o NestJS)
- **Lenguaje:** JavaScript/TypeScript

**Descripción:**

- El Middlend es el núcleo de la lógica de negocio del sistema.
- Este componente centraliza todas las operaciones y se encarga de orquestar las interacciones entre el Frontend y las diversas APIs especializadas. También maneja la autenticación de usuarios y la validación de datos antes de que las solicitudes sean procesadas por las APIs correspondientes.

**Interacción con el Sistema:**

- **Interfaces de Comunicación:** El Middlend expone una API REST que es consumida por el Frontend. A su vez, se comunica con las APIs (también REST) de Usuarios, Comunidades, Grants, Blockchain y Almacenamiento Descentralizado, gestionando las solicitudes y respuestas de manera eficiente.

## **Users API**

**Tecnología Utilizada:**

- **Framework:** Node.js
- **Base de Datos:** SQL (MySQL o PostgreSQL)

**Descripción:**

- La Users API gestiona toda la información relacionada con los usuarios, incluyendo su perfil, autenticación, y conexión de wallets. Esta API es responsable de mantener y proteger los datos de usuario, garantizando la integridad y seguridad de la información.
- Hemos diagramado implementar esta API desde cero con una base de datos SQL, pero perfectamente podría utilizarse un sistema de terceros como Firebase Authentication o Auth0 para evitar reimplementar lógica genérica de gestión de cuentas de usuarios y roles.

**Interacción con el Sistema:**

- **Interfaces de Comunicación:** Expone una API REST que es consumida por el Middlend para realizar operaciones como la creación de cuentas, actualización de perfiles, y manejo de sesiones. A su vez, consume una base de datos relacional exclusiva para esta API.

![imagen](https://github.com/user-attachments/assets/3e6289d2-6fd2-4ca4-948a-616744c1f5ca)

## **Communities API**

**Tecnología Utilizada:**

- **Framework:** Node.js
- **Base de Datos:** SQL (MySQL o PostgreSQL)

**Descripción:**

- La Communities API se encarga de gestionar la creación, administración y participación en comunidades dentro de la plataforma. Este componente permite a los usuarios unirse a comunidades existentes o crear nuevas, y manejar roles y permisos dentro de ellas.

**Interacción con el Sistema:**

- **Interfaces de Comunicación:** Expone una API REST que es utilizada por el Middlend para gestionar las operaciones relacionadas con las comunidades, como la creación de nuevas comunidades, la gestión de miembros, y la administración de roles. A su vez, consume una base de datos relacional exclusiva para esta API.

![imagen.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/dc177202-8f3c-48e3-85d9-f53074e75f06/ea6369d8-b4da-4502-a6bb-a2c917d24827/imagen.png)

## **Grants API**

**Tecnología Utilizada:**

- **Framework:** Node.js
- **Base de Datos:** SQL (MySQL o PostgreSQL)

**Descripción:**

- La Grants API es el componente encargado de manejar todo el ciclo de vida propuestas y grants, desde la creación de la propuesta hasta su aprobación o rechazo y creación del grant offchain. Este servicio gestiona las solicitudes de grants, permite a los usuarios ver el estado de sus solicitudes y facilita la interacción con los curators que evalúan los proyectos.

**Interacción con el Sistema:**

- **Interfaces de Comunicación:** Expone una API REST que permite al Middlend realizar operaciones como la creación de propuestas, la actualización de su estado, y la gestión de los comentarios y evaluaciones realizados por los curators.

## **Blockchain API**

**Tecnología Utilizada:**

- **Framework:** Node.js con librería https://www.npmjs.com/package/@polkadot/api
- **Blockchain:** Polkadot

**Descripción:**

- La Blockchain API gestiona las interacciones con la blockchain de Polkadot, incluyendo el registro de actividades importantes, como la creación de grants y su estado de aprobación. Esta API asegura que todas las operaciones críticas sean registradas de manera transparente y trazable en la blockchain.
- Esta API tiene cierto nivel de redundancia con la API de Grants.
- En el MVP, esta API se integra con la API de Polkadot, pero en futuras integraciones, se podrá remplazar este módulo por uno que realice la integración con otra blockchain como Optimism, zkSync, etc. de forma transparente.

**Interacción con el Sistema:**

- **Interfaces de Comunicación:** Expone una API REST que permite al middlend interactuar de forma indirecta con contratos inteligentes en Polkadot, permitiendo al Middlend realizar y verificar transacciones, así como registrar eventos importantes en la blockchain.

## **Decentralized Storage API**

**Tecnología Utilizada:**

- **Framework:** Node.js
- **Almacenamiento:** CESS

**Descripción:**

- La Decentralized Storage API es responsable del almacenamiento descentralizado de documentos y datos relacionados con las propuestas.
- Utiliza tecnologías de almacenamiento descentralizado para asegurar que los datos sean accesibles, inmutables y descentralizados, proporcionando un registro público y transparente de las propuestas y documentos asociados.

**Interacción con el Sistema:**

- **Interfaces de Comunicación:** Expone una API REST que permite al Middlend almacenar y recuperar archivos del almacenamiento. Los hashes de estos archivos pueden ser registrados en la blockchain a través de la Blockchain API para garantizar su trazabilidad.
