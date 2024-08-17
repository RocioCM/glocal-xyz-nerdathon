# Glocal.xyz: Plataforma Abierta de Gestión de Grants en Polkadot

Glocal.xyz is your gateway to bridging the gap between cutting-edge global Web3 technologies and vibrant local communities. Our platform empowers local innovators, educators, and event organizers by providing access to blockchain-based grants and resources. Join us in federalizing tech education and bringing transparency, accessibility, and ease to the decentralized world.

### Contexto general

El ecosistema de Polkadot está en crecimiento y con ello crecen también las propuestas de creadores de contenido y organizadores de eventos, que necesitan financiamiento para poder llevarse a cabo. La comunidad de Polkadot cuenta con un sistema de financiamiento mediante Grants para estas iniciativas, sin embargo, el acceso a este es un desafío, especialmente para aquellos que no tienen contactos dentro de la red de Polkadot o no están muy familiarizados con tecnología. 

Actualmente, el proceso de solicitud de grants se hace a través de un canal de Discord al cual se puede ingresar únicamente mediante invitación exclusiva. A su vez, dentro del canal de Discord, la información no tiene un orden preciso y el usuario puede perderse si intenta presentar un Grant sin guía de otra persona que ya tenga experiencia. A su vez, todo el proceso de gestión del grant se realiza a través de Discord y otros canales de comunicación informales, por lo que este proceso de asignación de fondos carece de transparencia y trazabilidad en la blockchain. Este enfoque limita la participación y excluye a muchos potenciales contribuyentes que podrían aportar valor significativo al ecosistema.

### **Problema a Solucionar**

El problema principal que nuestro producto busca abordar es la falta de acceso equitativo y formalizado al financiamiento dentro del ecosistema Polkadot, particularmente para creadores de contenido y organizadores de eventos en la comunidad hispanohablante. La dependencia de canales privados y la ausencia de un registro descentralizado y transparente dificulta que nuevos usuarios accedan a grants, limita la difusión de oportunidades y crea un entorno excluyente donde solo los miembros mejor conectados tienen éxito.

### **Solución Planteada**

Nuestro equipo propone una **plataforma abierta de gestión de grants descentralizada** que facilita el acceso a financiamiento para creadores de contenido y organizadores de eventos en la comunidad de Polkadot, con un enfoque especial en la comunidad de habla hispana. Esta plataforma está diseñada para democratizar el acceso a los recursos, asegurar la transparencia en todo el proceso de solicitud y evaluación, y registrar todas las actividades en la blockchain para garantizar la trazabilidad.

**Componentes Clave de la Solución:**

- **Centralización del Proceso de Grants:** La plataforma centraliza la creación, evaluación y distribución de grants, eliminando la necesidad de depender de canales privados como Discord.
- **Transparencia y Trazabilidad:** Todos los cambios en las propuestas son registrados en la blockchain, garantizando la transparencia y la capacidad de auditoría.
- **Interfaz de Usuario Amigable:** La plataforma ofrece una interfaz simple y guiada para que los usuarios puedan crear y gestionar sus solicitudes de grants de manera intuitiva.
- **Escalabilidad:** La solución está diseñada para ser escalable y adaptable a otros idiomas y comunidades dentro del ecosistema Polkadot y otros ecosistemas.

## **Descripción Detallada de las Funcionalidades del Producto**

### **Registro y Autenticación**

- **Login con Email/OTP o Google:** Los usuarios pueden registrarse e iniciar sesión utilizando su correo electrónico con un sistema de autenticación basado en OTP (One-Time Password) o mediante su cuenta de Google.

| 1 | 2 | 3 | 4 |
| --- | --- | --- | --- |
| ![imagen](https://github.com/user-attachments/assets/936a3e7d-57c2-4626-8f60-84b83f8899bb) | ![imagen](https://github.com/user-attachments/assets/64e7a729-c641-4cef-9bff-1489d7969285) | ![imagen](https://github.com/user-attachments/assets/622e35b2-042c-4ddd-9b70-0f3d63675fd4) | ![imagen](https://github.com/user-attachments/assets/c7d99874-6be0-4a9c-8667-04991082b101) |

- **Conexión de Wallet:** Los usuarios pueden conectar su wallet de Polkadot, como MetaMask o Talisman o Polkadot.js, para asociar sus cuentas con una dirección de wallet específica. Esta conexión es necesaria al presentar una propuesta de Grant para gestionar los fondos y realizar transacciones en la plataforma.

### **Gestión de Comunidades**

- **Creación de Comunidades:** Los usuarios pueden crear nuevas comunidades dentro de la plataforma, enfocadas en intereses específicos como la creación de contenido o la organización de eventos en Polkadot.

| 1 |
| --- | 
| ![imagen](https://github.com/user-attachments/assets/ddf90a1f-0425-4c51-9a5d-dece8ea31abc) |

- **Unión a Comunidades:** Los usuarios pueden solicitar unirse a comunidades existentes. Las solicitudes deben ser aprobadas por los administradores de la comunidad, quienes pueden asignar roles dentro de la misma.
- **Roles y Permisos:** Los administradores de las comunidades pueden asignar roles específicos a los miembros, como otros administradores, para facilitar la gestión interna.
- **Reputación de comunidades**: La reputación de las comunidades se calcula a partir de la reputación de todos sus participantes, fomentando comportamientos responsables en los usuarios para no perjudicar a su comunidad.

### **Solicitud y Gestión de Grants**

- **Proceso Guiado de Creación de Grants:** La plataforma ofrece un proceso paso a paso para que los usuarios puedan crear solicitudes de grants, proporcionando detalles como el objetivo del proyecto, el presupuesto requerido y el cronograma de ejecución.

| 1 | 2 | 3 | 4 |
| --- | --- | --- | --- |
| ![imagen](https://github.com/user-attachments/assets/b3e23cd0-538e-40c0-9b61-452414315476) | ![imagen](https://github.com/user-attachments/assets/82773b31-a906-4120-896f-50e621004871) | ![imagen](https://github.com/user-attachments/assets/5df048fe-baeb-41f4-ab85-09def48f0343) | ![imagen](https://github.com/user-attachments/assets/3792cb95-be28-4eb5-b684-948448a23d67) |

- **Exploración de Grants:** Los usuarios pueden explorar una lista de grants disponibles, filtrando por categoría, comunidad o estado del grant.
- **Historial de Grants:** Los usuarios pueden acceder a un historial de sus solicitudes de grants, ver su estado actual (en revisión, aprobado, rechazado) y recibir notificaciones sobre cualquier actualización.

### **Curación y Evaluación de Grants**

- **Centro de Evaluación:** Los curators tienen acceso a un panel donde pueden revisar las solicitudes de grants, dejar comentarios, solicitar modificaciones y finalmente aprobar o rechazar las solicitudes.
- **Sistema de Reputación:** Los curators pueden otorgar puntuaciones y comentarios a los usuarios, que influyen en la reputación de estos dentro de la plataforma. Esta reputación es pública y contribuye a la credibilidad de los solicitantes y las comunidades.
- **Interacción abierta**: Todos los usuarios pueden agregar comentarios y sugerencias en las propuestas abiertas actualmente, para fomentar el compromiso y colaboración en la comunidad.

### **Transparencia y Trazabilidad en Blockchain**

- **Registro en Blockchain:** Todas las acciones críticas, como la creación, modificación y aprobación de grants, son registradas en la blockchain de Polkadot, asegurando que cualquier usuario pueda auditar las actividades.
- **Desbloqueo Automático de Fondos:** Los fondos aprobados para los grants se manejan a través de contratos inteligentes que liberan los recursos en función de hitos específicos alcanzados por los proyectos.

### **Almacenamiento Descentralizado**

- **Almacenamiento de Propuestas:** Las propuestas y documentos relacionados con las solicitudes de grants se almacenan de manera descentralizada utilizando CESS, una plataforma de almacenamiento descentralizado del ecosistema de Polkadot. Esto garantiza la disponibilidad y la inmutabilidad de las propuestas y grants, permitiendo que cualquier miembro de la comunidad acceda a los mismos datos confiables en cualquier momento.
- **Acceso Público a Documentos:** Todos los documentos almacenados en el almacenamiento están accesibles públicamente, promoviendo la transparencia y permitiendo la colaboración abierta dentro de la comunidad.

### **Notificaciones y Comunicación**

- **Notificaciones en Tiempo Real:** Los usuarios reciben notificaciones en tiempo real sobre actualizaciones importantes, como cambios en el estado de sus grants, nuevos comentarios o la aceptación en una comunidad. Los curators reciben notificaciones sobre nuevas propuestas cargadas o modificaciones en las propuestas a las que están dando seguimiento.

# Arch Nerdathon

Problema: los medios para acceder a financiamiento (grants) en el ecosistema de Polkadot son informales y difíciles de acceder para personas o grupos que no pertenezcan ya a este círculo.

Todo el proceso se ejecuta de forma informal y sin registro trazable en la blockchain.

Problema: el discord es privado, sin libre acceso, sino por invitación exclusiva de administradores.

Problema: la UX del discord es complicada

Contexto técnico - en Polkadot:

- Se usa un canal de Discord para presentar propuestas
- Las propuestas pueden pertenecer a X distintas categorías
- Se debe llenar un formulario y presentar un GoogleDocs.
- Te ponés en contacto directamente con el Curator? O por discord? Y te pide modificaciones.
- La propuesta se aprueba, queda registro en Discord y se procede a bloquear los fondos en…. ???
- Son pocos curators, no hay mucha difusión, siempre el mismo grupo consigue grants? Difícil entrar?

Plataforma para gestión de grants para comunidades web3. Inicialmente nos enfocaremos en la comunidad de Polkadot, pero es sistema está diseñado para poder ser fácilmente escalado a distintas blockchains y ecosistemas en iteraciones futuras.

Bloques:

- Landing web - Facilita el acceso. Opciones: Framer o Next.js
- Plataforma web: gestión de grants con buena UX. Tecnología: Next.js
- Backend: se guarda en DB tradicional la información de grants presentados y todas sus interacciones. Opciones: Node.js o Golang
- Almacenamiento descentralizado - Estilo IPFS

Scoring individual y comunidad

Onboarding y proceso cómodo de formulario

Landing

Loguea con email

Al registrarse decide unirse a una comunidad o crear comunidad

Conecta una wallet personal

Crea un bounty en un proceso paso a paso.

Ver bounties en curso

A los curators les llega una difusión cada vez que se crea un bounty

Nos enfocaremos exclusivamente en esta etapa en la asignación de grants para eventos y creadores de contenido en español. Queremos hacer:

- Una landing introductoria
- Con login con email (con OTP) o con google
- Tendremos varias entidades: comunidades, community user, grants requests y curators.
- Los usuarios crean y pertenecen a comunidades. Múltiples usuarios pueden pertenecer a una comunidad. Cualquier usuario puede solicitar unirse a una comunidad. Su solicitud debe ser aprobada por algún administrador de la comunidad. Los usuarios pueden tener distintos roles en la comunidad.
- Cada usuario tiene un puntaje, asignado en base a la reputación otorgada por otros usuarios y curators. El puntaje de la comunidad se obtiene como un promedio de las puntuaciones de todos sus participantes.
- La funcionalidad core de la app es que el usuario puede generar una solicitud de grant mediante un flujo amigable y guiado paso a paso.
- El usuario puede consultar la lista de sus grants históricos y en curso.
- Todos los usuarios tienen libre acceso a visualizar y comentar en otros grants. Todas las solicitudes de grants son públicas

# **Glocal.xyz: Plataforma Abierta de Gestión de Grants en Polkadot**

### Contexto general

El ecosistema de Polkadot está en crecimiento y con ello crecen también las propuestas de creadores de contenido y organizadores de eventos, que necesitan financiamiento para poder llevarse a cabo. La comunidad de Polkadot cuenta con un sistema de financiamiento mediante Grants para estas iniciativas, sin embargo, el acceso a este es un desafío, especialmente para aquellos que no tienen contactos dentro de la red de Polkadot o no están muy familiarizados con tecnología. 

Actualmente, el proceso de solicitud de grants se hace a través de un canal de Discord al cual se puede ingresar únicamente mediante invitación exclusiva. A su vez, dentro del canal de Discord, la información no tiene un orden preciso y el usuario puede perderse si intenta presentar un Grant sin guía de otra persona que ya tenga experiencia. A su vez, todo el proceso de gestión del grant se realiza a través de Discord y otros canales de comunicación informales, por lo que este proceso de asignación de fondos carece de transparencia y trazabilidad en la blockchain. Este enfoque limita la participación y excluye a muchos potenciales contribuyentes que podrían aportar valor significativo al ecosistema.

### **Problema a Solucionar**

El problema principal que nuestro producto busca abordar es la falta de acceso equitativo y formalizado al financiamiento dentro del ecosistema Polkadot, particularmente para creadores de contenido y organizadores de eventos en la comunidad hispanohablante. La dependencia de canales privados y la ausencia de un registro descentralizado y transparente dificulta que nuevos usuarios accedan a grants, limita la difusión de oportunidades y crea un entorno excluyente donde solo los miembros mejor conectados tienen éxito.

### **Solución Planteada**

Nuestro equipo propone una **plataforma abierta de gestión de grants descentralizada** que facilita el acceso a financiamiento para creadores de contenido y organizadores de eventos en la comunidad de Polkadot, con un enfoque especial en la comunidad de habla hispana. Esta plataforma está diseñada para democratizar el acceso a los recursos, asegurar la transparencia en todo el proceso de solicitud y evaluación, y registrar todas las actividades en la blockchain para garantizar la trazabilidad.

**Componentes Clave de la Solución:**

- **Centralización del Proceso de Grants:** La plataforma centraliza la creación, evaluación y distribución de grants, eliminando la necesidad de depender de canales privados como Discord.
- **Transparencia y Trazabilidad:** Todos los cambios en las propuestas son registrados en la blockchain, garantizando la transparencia y la capacidad de auditoría.
- **Interfaz de Usuario Amigable:** La plataforma ofrece una interfaz simple y guiada para que los usuarios puedan crear y gestionar sus solicitudes de grants de manera intuitiva.
- **Escalabilidad:** La solución está diseñada para ser escalable y adaptable a otros idiomas y comunidades dentro del ecosistema Polkadot y otros ecosistemas.

## **Descripción Detallada de las Funcionalidades del Producto**

### **Registro y Autenticación**

- **Login con Email/OTP o Google:** Los usuarios pueden registrarse e iniciar sesión utilizando su correo electrónico con un sistema de autenticación basado en OTP (One-Time Password) o mediante su cuenta de Google.

![imagen.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/dc177202-8f3c-48e3-85d9-f53074e75f06/2dcda43c-436a-426f-86a9-a4ebc3210cf0/imagen.png)

![imagen.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/dc177202-8f3c-48e3-85d9-f53074e75f06/1f5a7ec1-6911-4e76-a4f5-8e31a8f2a004/imagen.png)

![imagen.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/dc177202-8f3c-48e3-85d9-f53074e75f06/da16974a-4964-44b5-a72d-967033856dde/imagen.png)

![imagen.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/dc177202-8f3c-48e3-85d9-f53074e75f06/43fa1ba3-5721-4981-bd56-067beea1f76f/imagen.png)

- **Conexión de Wallet:** Los usuarios pueden conectar su wallet de Polkadot, como MetaMask o Talisman o Polkadot.js, para asociar sus cuentas con una dirección de wallet específica. Esta conexión es necesaria al presentar una propuesta de Grant para gestionar los fondos y realizar transacciones en la plataforma.

### **Gestión de Comunidades**

- **Creación de Comunidades:** Los usuarios pueden crear nuevas comunidades dentro de la plataforma, enfocadas en intereses específicos como la creación de contenido o la organización de eventos en Polkadot.

![imagen.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/dc177202-8f3c-48e3-85d9-f53074e75f06/4c50b7cc-7008-460d-b570-718b37dd9d9d/imagen.png)

- **Unión a Comunidades:** Los usuarios pueden solicitar unirse a comunidades existentes. Las solicitudes deben ser aprobadas por los administradores de la comunidad, quienes pueden asignar roles dentro de la misma.
- **Roles y Permisos:** Los administradores de las comunidades pueden asignar roles específicos a los miembros, como otros administradores, para facilitar la gestión interna.
- **Reputación de comunidades**: La reputación de las comunidades se calcula a partir de la reputación de todos sus participantes, fomentando comportamientos responsables en los usuarios para no perjudicar a su comunidad.

### **Solicitud y Gestión de Grants**

- **Proceso Guiado de Creación de Grants:** La plataforma ofrece un proceso paso a paso para que los usuarios puedan crear solicitudes de grants, proporcionando detalles como el objetivo del proyecto, el presupuesto requerido y el cronograma de ejecución.

![imagen.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/dc177202-8f3c-48e3-85d9-f53074e75f06/eeb88516-0d29-49bc-80fd-ef9b450d3684/imagen.png)

![imagen.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/dc177202-8f3c-48e3-85d9-f53074e75f06/4eb70ddf-16bf-4f61-8607-6fc02a8976f3/imagen.png)

![imagen.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/dc177202-8f3c-48e3-85d9-f53074e75f06/930c744d-b6c7-47ce-9a4f-f55d40cbdeab/imagen.png)

![imagen.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/dc177202-8f3c-48e3-85d9-f53074e75f06/d9ef30e6-b04d-4522-b92c-c724394a7088/imagen.png)

- **Exploración de Grants:** Los usuarios pueden explorar una lista de grants disponibles, filtrando por categoría, comunidad o estado del grant.
- **Historial de Grants:** Los usuarios pueden acceder a un historial de sus solicitudes de grants, ver su estado actual (en revisión, aprobado, rechazado) y recibir notificaciones sobre cualquier actualización.

### **Curación y Evaluación de Grants**

- **Centro de Evaluación:** Los curators tienen acceso a un panel donde pueden revisar las solicitudes de grants, dejar comentarios, solicitar modificaciones y finalmente aprobar o rechazar las solicitudes.
- **Sistema de Reputación:** Los curators pueden otorgar puntuaciones y comentarios a los usuarios, que influyen en la reputación de estos dentro de la plataforma. Esta reputación es pública y contribuye a la credibilidad de los solicitantes y las comunidades.
- **Interacción abierta**: Todos los usuarios pueden agregar comentarios y sugerencias en las propuestas abiertas actualmente, para fomentar el compromiso y colaboración en la comunidad.

### **Transparencia y Trazabilidad en Blockchain**

- **Registro en Blockchain:** Todas las acciones críticas, como la creación, modificación y aprobación de grants, son registradas en la blockchain de Polkadot, asegurando que cualquier usuario pueda auditar las actividades.
- **Desbloqueo Automático de Fondos:** Los fondos aprobados para los grants se manejan a través de contratos inteligentes que liberan los recursos en función de hitos específicos alcanzados por los proyectos.

### **Almacenamiento Descentralizado**

- **Almacenamiento de Propuestas:** Las propuestas y documentos relacionados con las solicitudes de grants se almacenan de manera descentralizada utilizando CESS, una plataforma de almacenamiento descentralizado del ecosistema de Polkadot. Esto garantiza la disponibilidad y la inmutabilidad de las propuestas y grants, permitiendo que cualquier miembro de la comunidad acceda a los mismos datos confiables en cualquier momento.
- **Acceso Público a Documentos:** Todos los documentos almacenados en el almacenamiento están accesibles públicamente, promoviendo la transparencia y permitiendo la colaboración abierta dentro de la comunidad.

### **Notificaciones y Comunicación**

- **Notificaciones en Tiempo Real:** Los usuarios reciben notificaciones en tiempo real sobre actualizaciones importantes, como cambios en el estado de sus grants, nuevos comentarios o la aceptación en una comunidad. Los curators reciben notificaciones sobre nuevas propuestas cargadas o modificaciones en las propuestas a las que están dando seguimiento.

### **Estructura de la Landing Page:**

1. **Hero Section (Encabezado Principal):**
    - **Headline:** "Financiamiento para Creadores de Contenido y Eventos en Polkadot"
    - **Subheadline:** "Obtén el apoyo que necesitas para llevar tus ideas al siguiente nivel. Grants disponibles para la comunidad en español."
    - **Call to Action:** "Solicita tu Grant" / "Empieza Ahora"
    - **Visuales:** Imágenes o gráficos representativos de eventos y creadores de contenido (micrófonos, cámaras, escenarios), con un fondo que refleje la identidad visual de Polkadot.
2. **About Section (Acerca de):**
    - **Título:** "Apoyando a la Comunidad de Habla Hispana en Polkadot"
    - **Descripción:** "Nuestra plataforma está dedicada a facilitar el acceso a financiamiento para creadores de contenido y organizadores de eventos que desean hacer crecer la comunidad de Polkadot en español. Simplificamos el proceso de solicitud de grants, permitiéndote enfocarte en lo que mejor haces: crear y conectar."
    - **Visuales:** Un esquema visual que muestre cómo la plataforma conecta a los creadores con los recursos financieros necesarios para sus proyectos.
3. **How It Works Section (Cómo Funciona):**
    - **Título:** "Cómo Funciona"
    - **Paso 1:** "Regístrate y Únete a la Comunidad"
    - **Paso 2:** "Solicita un Grant"
    - **Paso 3:** "Recibe Feedback y Mejora tu Propuesta"
    - **Paso 4:** "Obtén Financiamiento y Realiza tu Proyecto"
    - **Visuales:** Ilustraciones que representen cada paso, con íconos de contenido como cámaras, micrófonos, y escenarios.
4. **Features Section (Características Principales):**
    - **Título:** "Características Clave para Creadores"
    - **Características:**
        - **Foco en la Comunidad Hispana**
        - **Proceso Guiado**
        - **Reputación Comunitaria**
        - **Transparencia y Acceso Abierto**
    - **Visuales:** Capturas de pantalla de la interfaz de la plataforma o íconos específicos de cada característica.
5. **Testimonials Section (Testimonios):**
    - **Título:** "Historias de Éxito en la Comunidad"
    - **Testimonios:** Incluye citas y nombres de usuarios que han logrado financiamiento gracias a la plataforma.
    - **Visuales:** Fotos de usuarios o representaciones gráficas.
6. **Call to Action (Llamado a la Acción):**
    - **Título:** "¿Listo para Hacer Crecer tu Proyecto?"
    - **Botón Principal:** "Solicita tu Grant Ahora"
    - **Botón Secundario:** "Explora Proyectos Financiados"
    - **Visuales:** Un botón destacado, con colores que contrasten para atraer la atención.
7. **Footer (Pie de Página):**
    - **Enlaces:** "Sobre nosotros", "Contacto", "Términos de Uso", "Política de Privacidad"
    - **Redes Sociales:** Íconos que enlacen a las redes sociales activas de la plataforma.
    - **Visuales:** Diseño limpio y ordenado.

## **Roadmap Futuro**

Nuestro MVP se centra inicialmente en proporcionar una solución específica para **creadores de contenido y organizadores de eventos** en el **ecosistema de Polkadot**, con un enfoque particular en la comunidad hispanohablante. Este enfoque nos permite abordar un nicho claramente definido y asegurar que nuestra plataforma cumpla con las necesidades específicas de estos usuarios desde el principio.

Nuestro roadmap está orientado a expandir el alcance de la plataforma a lo largo del tiempo, comenzando con un enfoque específico en un nicho de Polkadot, para luego generalizar a todo su ecosistema y, finalmente, escalar hacia otros entornos blockchain, convirtiendo nuestra plataforma en una solución robusta y versátil para la gestión de grants en el mundo web3.

### **Fase 1: MVP para Creadores de Contenido en Polkadot**

- **Objetivo:** Desarrollar y lanzar una plataforma que facilite el acceso a grants para creadores de contenido y organizadores de eventos en Polkadot.
- **Funcionalidades Clave:** Gestión de grants, creación y unión a comunidades, curación y evaluación de proyectos, y registro de actividades en la blockchain de Polkadot.
- **Resultados Esperados:** Validar la propuesta de valor y obtener retroalimentación de los usuarios para iterar y mejorar el producto.

### **Fase 2: Expansión a Todos los Tipos de Grants en Polkadot**

- **Objetivo:** Generalizar la plataforma para que no solo se oriente a creadores de contenido, sino que abarque todos los tipos de grants disponibles en Polkadot, incluyendo desarrollo de software, investigación, infraestructura, y más.
- **Funcionalidades Clave:** Ampliación del sistema de categorías de grants, integración de nuevas funcionalidades específicas para otros tipos de proyectos y mejora de las herramientas de evaluación y seguimiento.
- **Resultados Esperados:** Atraer un público más amplio dentro del ecosistema de Polkadot, consolidando la plataforma como el lugar centralizado para la gestión de grants.

### **Fase 3: Expansión a Otros Ecosistemas Blockchain**

- **Objetivo:** Escalar nuestra plataforma más allá de Polkadot, integrando otros ecosistemas blockchain para facilitar la gestión de grants de manera descentralizada y cross-chain.
- **Funcionalidades Clave:** Implementación de conectores para múltiples blockchains, adaptabilidad de contratos inteligentes a diferentes redes, y soporte para nuevas comunidades y tipos de proyectos en estos ecosistemas.
- **Resultados Esperados:** Convertir la plataforma en una solución global y descentralizada para la gestión de grants, facilitando el acceso a financiamiento a nivel multi-chain y permitiendo la interoperabilidad entre diferentes redes.
