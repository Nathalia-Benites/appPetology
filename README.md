# Petology 🐾  

Bienvenido a **Petology**, la plataforma dedicada al cuidado profesional de las mascotas. Aquí encontrarás información sobre adopción, precios y servicios veterinarios, así como detalles sobre quiénes somos y cómo trabajamos para garantizar la salud y felicidad de las mascotas.  

---

## Introducción  
El propósito de **Petology** es ofrecer servicios veterinarios de alta calidad, priorizando el bienestar de las mascotas y la confianza de sus dueños. Nuestra página web está diseñada para proporcionar información clara y accesible sobre nuestros servicios, fomentando una conexión responsable entre las personas y sus mascotas. 

### **Objetivos**  
- 🩺 Brindar servicios veterinarios confiables y profesionales.  
- 🐶 Facilitar el proceso de adopción de mascotas.  
- 💰 Ofrecer información clara y transparente sobre precios y servicios.  
- 🌱 Promover el cuidado ético y responsable de las mascotas.  
- 🌐 Garantizar una navegación fácil e intuitiva para los usuarios.  

---

## Contexto del problema  
Cuidar de las mascotas puede ser un desafío, ya que muchas personas enfrentan dificultades como:  
1. Falta de acceso a servicios veterinarios confiables y asequibles.  
2. Ausencia de información clara sobre precios y servicios.  
3. Poco fomento de la adopción como alternativa ética y sostenible.  

**Petology** aborda estas necesidades al ofrecer:  
- Una plataforma accesible y bien organizada.  
- Servicios profesionales que priorizan el bienestar animal.  
- Información completa y transparente para tomar decisiones informadas.  

---

## Sobre nosotros  
En **Petology**, nos comprometemos a cuidar de las mascotas como si fueran parte de nuestra familia. Con profesionales altamente capacitados y una experiencia amigable, trabajamos para garantizar que cada mascota reciba el amor y cuidado que merece.  

¡Gracias por confiar en nosotros para el cuidado de tus mascotas, contáctanos! 🐾  

---

## Análisis de Requerimientos 
El sistema implementado en **Petology** incluye las siguientes funcionalidades:
- **Formulario "Contáctanos":**
  - Campos: Nombre, Teléfono, Correo Electrónico, Mensaje.
  - Validación: No se permite enviar campos vacíos.
  - Uso: Recopilar comentarios y solicitudes como adopciones y agendamiento de citas.
- **Página "Adopta Ahora":**
  - Visualización de nombres y edades de animales disponibles para adopción.
  - Almacenamiento: Datos gestionados directamente en la base de datos MySQL.
- **Página "Servicios":**
  - Publicación de los servicios ofrecidos por Petology.
  - Almacenamiento: Los servicios se gestionan y guardan en una base de datos MySQL para facilitar su actualización y consulta.

---

## Modelo Relacional
El modelo relacional de Petology en MySQL incluye las siguientes tablas:

- **Formulario de Contacto:**
  - **Campos:** ID, Nombre, Teléfono, Correo Electrónico, Mensaje, Fecha de Envío.
- **Animales para Adopción:**
  - **Campos:** ID, Nombre del Animal, Edad, Fecha de Registro.
- **Servicios:**
  - **Campos:** id, nombre, descripcion, precio.

Estas tablas están diseñadas para garantizar integridad de datos y normalización adecuada para optimizar el rendimiento.

---

## Diseño del Sistema
El sistema utiliza Django como framework y MySQL para la gestión de datos, destacando las siguientes características:

- **Conexión a la Base de Datos:**
  - La aplicación establece una conexión segura con MySQL al iniciar y la cierra al finalizar.
- **Páginas Interactivas:**
  - **"Contáctanos":** Permite registrar comentarios y solicitudes de los usuarios.
  - **"Adopta Ahora":** Muestra información clara y detallada de animales disponibles para adopción.
  - **"Servicios":** Publica y actualiza los servicios ofrecidos por Petology.

---

## Resultados y Conclusión
Petology brinda una solución efectiva para las clínicas veterinarias al centralizar y optimizar la gestión de información crítica. Sus funcionalidades robustas y diseño intuitivo mejoran la eficiencia operativa y la experiencia del usuario, marcando un avance significativo en la digitalización del sector veterinario.
