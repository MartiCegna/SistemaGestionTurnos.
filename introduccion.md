# Programacion Orientada a Objetos (POO)
La Programación Orientada a Objetos(POO) es un paradigma de progremación basado en la organización del código en objetos, los cuales representan entidades reales y agrupan tanto sus datos como los comportamientos que pueden realizar.

En POO, los programas se estructuran en torno a **clases** (plantillas para crear objetos) y **objetos** (instancias de esas clases), permitiendo una mejor organización y reutilización del código.

La POO es importante porque facilita la creación de estructuras modulares y escalables, los cambios de una clase no afectan otras partes del código si está bien diseñado, los objetos pueden ser reutilizados
en diferentes partes del programa o incluso en otros proyectos. Es fundamental en el desarrollo de **software empresarial**, **videojuegos**, **aplicaciones móviles** y **sistemas complejos**.

# Fundamentos de POO.
### **Abstracción**
La abstracción consiste en representar solo los aspectos esenciales de un objeto sin mostrar detalles innecesarios.

### **Encapsulamiento**
El encapsulamiento protege los datos de acceso no autorizado y controla cómo se interactúa con ellos.

### **Herencia**
La herencia permite que una clase (subclase) herede características de otra (superclase), evitando la repetición de código.

### **Polimorfismo**
El polimorfismo permite que un mismo método funcione de diferentes maneras según el objeto que lo use.

# Requisitos iniciales del sistema
### **Gestión de turnos médicos**
El sistema debe permitir a los usuarios registrar, modificar y cancelar turno. Cada turno debe incluir fecha, hora, médico asignado, paciente, estado y observaciones. No se debe permitir turnos duplicados para un mismo horario y médico.

### **Registro y gestión de pacientes**
Se debe poder registrar nuevos apcientes con nombre, documento, fecha de nacimiento, contacto y su historial de turnos. El sistema debe permitir la actualización de datos de los pacientes.

### **Regisstro y gestión de profesionales de la Salud**
Se debe registrar a los médicos con nombre, matrícula, especialidad, horario de atención y contacto. El sistema debe validar que los turnos asignados no superen la disponibilidad del profesional.

### **Notificaciones automáticas**
El sistema debe enviar notificaciones por correo electrónico o mensajes de texto cuando un turno sea confirmado, cancelado o modificado. Tanto el paciente como el médico debe recibir la notificación.

### **Control de acceso y seguridad de datos**
La información de pacientes y médicos debe estar protegida y solo accesible para el personal autorizado.

# Casos de uso
1. **Agendar un turno médico**
   - **Actor(es) involucrado(s): Recepcionistas, Paciente.

2. **Descripción breve:** Permite registrar un nuevo turno en el sistema según la disponibilidad del médico.

3. **Fujo principal de eventos**
   -El usuario (recepcionista o paciente) accede al sistema.
   -Selecciona la opción "Agendar turno".
   -Ingresa los datos del paciente.
   -Selecciona la fecha, hora y médico disponible.
   -Ingresa el motivo del turno y observaciones (opcional).
   -Confirma el turno.
   -El sistema registra el turno y envía una notificación al paciente y al médico.

4. **Precondiciones:**
El paciente debe estar registrado en el sistema y debe haber disponibilidad en el horario del médico.

5. **Postcondiciones:**
El turno queda resitrado en la agenda y se notifican tanto el paciente como el médico.
   


















