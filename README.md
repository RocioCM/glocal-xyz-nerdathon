# Glocal.xyz: Plataforma Abierta de Gestión de Grants en Polkadot

Glocal.xyz is your gateway to bridging the gap between cutting-edge global Web3 technologies and vibrant local communities. Our platform empowers local innovators, educators, and event organizers by providing access to blockchain-based grants and resources. Join us in federalizing tech education and bringing transparency, accessibility, and ease to the decentralized world.

### Contexto general

El ecosistema de Polkadot está en crecimiento y con ello crecen también las propuestas de creadores de contenido y organizadores de eventos, que necesitan financiamiento para poder llevarse a cabo. La comunidad de Polkadot cuenta con un sistema de financiamiento mediante Grants para estas iniciativas, sin embargo, el acceso a este es un desafío, especialmente para aquellos que no tienen contactos dentro de la red de Polkadot o no están muy familiarizados con tecnología. 

Actualmente, el proceso de solicitud de grants se hace a través de un canal de Discord al cual se puede ingresar únicamente mediante invitación exclusiva. A su vez, dentro del canal de Discord, la información no tiene un orden preciso y el usuario puede perderse si intenta presentar un Grant sin guía de otra persona que ya tenga experiencia. A su vez, todo el proceso de gestión del grant se realiza a través de Discord y otros canales de comunicación informales, por lo que este proceso de asignación de fondos carece de transparencia y trazabilidad en la blockchain. Incluso cuando el usuario obtiene un grant, los fondos se entregan en la moneda nativa de la red (DOT en este caso) y el usuario puede tener dificultad para usar esos fondos para pagar a sus proveedores (en caso de ser un evento) o para cualquier otro fin (en caso de crear contenido). Este enfoque limita la participación y excluye a muchos potenciales contribuyentes que podrían aportar valor significativo al ecosistema.

### **Problema a Solucionar**

El problema principal que nuestro producto busca abordar es la falta de acceso equitativo y formalizado al financiamiento dentro del ecosistema Polkadot, particularmente para creadores de contenido y organizadores de eventos en la comunidad hispanohablante. La dependencia de canales privados y la ausencia de un registro descentralizado y transparente dificulta que nuevos usuarios accedan a grants, limita la difusión de oportunidades y crea un entorno excluyente donde solo los miembros mejor conectados tienen éxito.

### **Solución Planteada**

Nuestro equipo propone una **plataforma abierta de gestión de grants descentralizada** que facilita el acceso a financiamiento para creadores de contenido y organizadores de eventos en la comunidad de Polkadot, con un enfoque especial en la comunidad de habla hispana. Esta plataforma está diseñada para democratizar el acceso a los recursos, asegurar la transparencia en todo el proceso de solicitud y evaluación, facilitar el proceso de pago y registrar todas las actividades en la blockchain para garantizar la trazabilidad.

**Componentes Clave de la Solución:**

- **Centralización del Proceso de Grants:** La plataforma centraliza la creación, evaluación y distribución de grants, eliminando la necesidad de depender de canales privados como Discord.
- **Gestión de Pagos en FIAT:** La plataforma permite pagar directamente en moneda local en una cuenta bancaria a partir de los fondos obtenidos del grant sin necesidad de conocimiento complejo del usuario.
- **Transparencia y Trazabilidad:** Todos los cambios en las propuestas son registrados en la blockchain, garantizando la transparencia y la capacidad de auditoría.
- **Interfaz de Usuario Amigable:** La plataforma ofrece una interfaz simple y guiada para que los usuarios puedan crear y gestionar sus solicitudes de grants de manera intuitiva.
- **Escalabilidad:** La solución está diseñada para ser escalable y adaptable a otros idiomas y comunidades dentro del ecosistema Polkadot y otros ecosistemas.

### Tecnologías

El sistema contará con:
- Una aplicación Frontend en Next.js
- Una serie de APIs REST en Node.js para gestionar la interacción entre las distintas entidades e integraciones del sistema
- Utilizará la red Polkadot como base de datos para seguimiento de las propuestas y grants
- Utilizará CESS como almacenamiento descentralizado para los archivos de las propuestas
- Utilizará la plataforma [Eluter](https://www.eluter.com/) como rampa de pagos para conversión entre crypto y FIAT.

## Más detalles

- Roadmap Futuro: [ROADMAP.md](./ROADMAP.md)
- Descripción de funcionalidades: [FEATURES.md](./FEATURES.md)
- Arquitectura del sistema (Técnico): [TECH.md](./TECH.md)

## Recursos

### Figma

En el Figma se encuentra el diseño en alta fidelidad de los flujos principales de la aplicación.

Link: https://www.figma.com/design/YGSJZ8mZAEDub3MOxKoCrE/glocal.xyz?node-id=0-1&t=MbkAVRg5shmPWiCg-1

### Figjam

En el Figjam se encuentran algunos diagramas documentando el sistema, como la arquitectura de información y roles de la aplicación.

- La **Arquitectura de la Información** es un diagrama para organizar y estructur la información dentro de una aplicación para que sea fácil de encontrar y usar. Nos permite asegurarnos de que todo esté en el lugar correcto y que no nos olvidamos ninguna funcionalidad clave incluso antes de diseñar y programar.

Link: https://www.figma.com/board/f7YTPJ9Qfdw2NWTRTeiWpJ/Nerdathon?node-id=1-110&t=4VAOGGp65ViovUyX-1

### Draw.io

En el Drawio se encuentran diagramas relacionados a la arquitectura del software, como arquitectura del sistema y DER.

- La **Arquitectura del Sistema** muestra de forma sencilla los componentes que conformarán al sistema y sus tecnologías o interfaces de forma simplificada.
- El **Diagrama de Entidad Relación (DER)** muestra las entidades del sistema y cómo estarán relacionadas entre sí las diferentes entidades o elementos dentro de la base de datos.

Link: https://drive.google.com/file/d/1NT76OEx7UOtG7pOZ7EVdPASLNqmd4CAE/view?usp=sharing

### Demo

- Slides de presentación para el Pitch de 1 minuto con video demo.

Link: https://docs.google.com/presentation/d/1D7UUuc3akpHiwwjAn-DziVeWY56ypH0utlIZsmW0Vo0/edit?usp=sharing



