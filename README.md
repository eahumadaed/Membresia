# Gestión de Membresías de Servicio de Streaming

Este proyecto consiste en un sistema de gestión de membresías para un servicio de streaming, donde los usuarios pueden suscribirse a diferentes planes según sus necesidades.

## Grupo 2
- Edinson Ahumada
- Yanina Belmar
- Najla Gatica
- Livio Gutierrez
- Manuel Ruiz
- Pablo Hernández

## Descripción del Código

### Clase Membresia
- Esta clase abstracta define la estructura básica de una membresía en el servicio de streaming.
- Tiene métodos para obtener el correo del suscriptor y el número de tarjeta asociada a la membresía.
- Además, contiene un método abstracto para cambiar la suscripción a otro tipo de membresía y un método para cancelar la suscripción actual.

### Clases de Membresías Específicas
1. **Gratis**: Membresía gratuita con un dispositivo máximo y opción para cambiar a otros tipos de membresía.
2. **Básica**: Membresía con costo, permite hasta dos dispositivos y se puede cambiar a otros tipos de membresía.
3. **Familiar**: Extiende la membresía básica y agrega opciones como días de regalo y control parental.
4. **SinConexión**: Extiende la membresía básica y agrega opciones como días de regalo e incremento de contenido sin conexión.
5. **Pro**: Combina características de las membresías familiar y sin conexión, con mayor costo, más dispositivos y más días de regalo.