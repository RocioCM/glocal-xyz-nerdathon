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

- **Exploración de Propuestas:** Los usuarios pueden explorar una lista de propuestas abiertas o históricas, filtrando por categoría, comunidad o estado.

| 1 | 2 |
| --- | --- |
| ![imagen](https://github.com/user-attachments/assets/fd833be3-dfe7-4707-8300-e83c7b7bc51d) | ![imagen](https://github.com/user-attachments/assets/acacdb0a-35fa-455b-8e41-bedc5a6d6624) |

- **Pagos a Proveedores:** En el caso de grants para eventos, se desbloquea la opción de acceder a una rampa de pagos transparente que permite pagar a los proveedores de servicio en moneda FIAT en su cuenta bancaria.

| 1 |
| --- |
| ![imagen](https://github.com/user-attachments/assets/13e24978-63b0-448a-a77c-c4ef5b64b714) |

- **Historial de Grants:** Los usuarios pueden acceder a un historial de sus solicitudes de grants, ver su estado actual (en revisión, aprobado, rechazado) y recibir notificaciones sobre cualquier actualización.

### **Curación y Evaluación de Propuestas de Grants**

- **Centro de Evaluación:** Los curators tienen acceso a un panel donde pueden revisar las solicitudes de grants, dejar comentarios, solicitar modificaciones y finalmente aprobar o rechazar las solicitudes.
- **Evaluación asistida con IA:** Los curators pueden utilizar una herramienta de evaluación asistida por IA para analizar las propuestas y proporcionar recomendaciones basadas en criterios específicos como Factibilidad, Viabilidad, Deseabilidad y Utilidad.

| 1 | 2 |
| --- | --- |
| ![imagen](https://github.com/user-attachments/assets/dadf81b0-4a83-416d-86a3-4bccc4005f36) | ![imagen](https://github.com/user-attachments/assets/b472ab1d-25ee-49f1-9871-5f90ae7533be) |

- **Sistema de Reputación:** Los curators pueden otorgar puntuaciones y comentarios a los usuarios, que influyen en la reputación de estos dentro de la plataforma. Esta reputación es pública y contribuye a la credibilidad de los solicitantes y las comunidades.
- **Interacción abierta**: Todos los usuarios pueden agregar comentarios y sugerencias en las propuestas abiertas actualmente, para fomentar el compromiso y colaboración en la comunidad.

### **Transparencia y Trazabilidad en Blockchain**

- **Registro en Blockchain:** Todas las acciones críticas, como la creación, modificación y aprobación de grants, son registradas en la blockchain de Polkadot, asegurando que cualquier usuario pueda auditar las actividades.
- **Desbloqueo Automático de Fondos:** Los fondos aprobados para los grants se manejan a través de contratos inteligentes que liberan los recursos en función de hitos específicos alcanzados por los proyectos.
- **Pagos en FIAT**: Los pagos a proveedores en eventos se podrán realizar en moneda FIAT, por detrás usaremos una rampa de pagos que haga la conversión del token nativo de la red a FIAT, evitando que el usuario tenga que realizar el proceso de cambio manualmente por fuera del sistema.

### **Almacenamiento Descentralizado**

- **Almacenamiento de Propuestas:** Las propuestas y documentos relacionados con las solicitudes de grants se almacenan de manera descentralizada utilizando CESS, una plataforma de almacenamiento descentralizado del ecosistema de Polkadot. Esto garantiza la disponibilidad y la inmutabilidad de las propuestas y grants, permitiendo que cualquier miembro de la comunidad acceda a los mismos datos confiables en cualquier momento.
- **Acceso Público a Documentos:** Todos los documentos almacenados en el almacenamiento están accesibles públicamente, promoviendo la transparencia y permitiendo la colaboración abierta dentro de la comunidad.

### **Notificaciones y Comunicación**

- **Notificaciones en Tiempo Real:** Los usuarios reciben notificaciones en tiempo real sobre actualizaciones importantes, como cambios en el estado de sus grants, nuevos comentarios o la aceptación en una comunidad. Los curators reciben notificaciones sobre nuevas propuestas cargadas o modificaciones en las propuestas a las que están dando seguimiento.
