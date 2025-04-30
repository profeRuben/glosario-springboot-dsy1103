# Glosario técnico – DSY1103

## 1. Spring Boot
Es un framework que facilita la creación de aplicaciones web en Java. Hace que todo sea más rápido y sencillo al configurar automáticamente muchas cosas que normalmente tendrías que hacer tú mismo. Con Spring Boot, puedes crear aplicaciones listas para ejecutarse con poco código y configuración. Puedes hacer un hola Mundo fasilmente. 



## 2. Microservicios
Microservicios es una arquitectura de diseño de software en la que una aplicación se divide en pequeños servicios independientes que son autónomos y que se comunican entre sí a través de interfaces bien definidas, usualmente utilizando APIs (interfaz de programación de aplicaciones). Cada microservicio es responsable de una funcionalidad específica de la aplicación y puede ser desarrollado, desplegado y escalado de manera independiente, lo que facilita la gestión y el mantenimiento de aplicaciones grandes y complejas.

una tienda en línea. En lugar de tener una única aplicación monolítica que maneje todo (desde los usuarios hasta los pagos), la tienda se divide en varios microservicios:

Microservicio de usuarios: Gestiona el registro, inicio de sesión y administración de cuentas de usuario.

Microservicio de productos: Se encarga de mostrar los productos, detalles y gestionar el inventario.

Microservicio de pagos: Gestiona las transacciones y el procesamiento de pagos.

Microservicio de recomendaciones: Sugerencias personalizadas de productos basadas en el historial de compras.

## 3. Maven
(por completar)

## 4. pom.xml
(por completar)

## 5. API RESTful
(por completar)

## 6. Git
(por completar)

## 7. GitHub
(por completar)

## 8. Control de versiones
(por completar)

## 9. Base de datos
Una base de datos es una colección organizada de información, generalmente almacenada electrónicamente, que permite la gestión eficiente de datos. Sirve para almacenar, recuperar y manipular datos relacionados, facilitando tareas como análisis, búsqueda y actualización de información. Por ejemplo Oracle.

## 10. CRUD
DEFINICION: CRUD es un acrónimo que se refiere a las operaciones básicas que se pueden realizar sobre una base de datos o sistema de almacenamiento de información. Estas operaciones son: Crear (Create), Leer (Read), Actualizar (Update) y Eliminar (Delete). CRUD describe las cuatro funciones fundamentales para gestionar datos en una base de datos o aplicación.

EJEMPLO:  una aplicación de gestión de usuarios. En esta aplicación, las operaciones CRUD se aplicarían de la siguiente manera:

Crear (Create): Registrar un nuevo usuario con su nombre, correo electrónico y contraseña.

Leer (Read): Consultar la información de un usuario, como su nombre o correo electrónico, a partir de su identificador único.

Actualizar (Update): Modificar los detalles de un usuario, por ejemplo, cambiar su dirección de correo electrónico.

Eliminar (Delete): Eliminar la cuenta de un usuario de la base de datos.

## 11. Postman
(por completar)

## 12. Comunicación entre microservicios
(por completar)

## 13. Configuración del proyecto
(por completar)

## 14. Backend
(por completar)

## 15. Código fuente

El código fuente es el conjunto de instrucciones escritas por un programador utilizando un lenguaje de programación (como Java, Python, C++, JavaScript, etc.). Estas instrucciones indican paso a paso lo que debe hacer un programa o una aplicación.

Es el núcleo lógico de cualquier software y representa el primer paso en la creación de un programa informático.

¿Cómo se ve?
Un archivo de código fuente puede tener una extensión como .java, .py, .cpp, .js, etc., dependiendo del lenguaje utilizado. Por ejemplo:

Ejemplo en Python
print("Hola, mundo")


// Ejemplo en Java
public class HolaMundo {
    public static void main(String[] args) {
        System.out.println("Hola, mundo");
    }
}

El código fuente está diseñado para ser leído y entendido por humanos, especialmente por otros programadores. Por eso se escribe con sintaxis estructurada, nombres descriptivos y frecuentemente comentarios que explican qué hace cada parte.

¿Por qué es importante?
Es lo que permite modificar o mantener un software.

Garantiza que el programa haga lo que se espera.

Se puede compartir, versionar y colaborar en equipo usando sistemas como GitHub.

A veces es propietario (oculto al usuario final) y otras veces es código abierto (open source), lo que permite que cualquiera lo vea y lo mejore.

## 16. Repositorio
(por completar)

## 17. Commit
(por completar)

## 18. Pruebas
(por completar)

## 19. Pruebas unitarias
(por completar)

## 20. Pruebas de integración
(por completar)

## 21. Documentación técnica
(por completar)

## 22. @SpringBootApplication
Es una anotación compuesta que se utiliza para marcar la clase principal de una aplicación Spring Boot. Esta anotación incluye varias otras anotaciones de configuración, como @Configuration, @EnableAutoConfiguration, y @ComponentScan. Permite que Spring Boot configure automáticamente la aplicación y ejecute el código sin necesidad de mucha configuración manual.

## 23. @RestController
(por completar)

## 24. @RequestMapping
(por completar)

## 25. @GetMapping, @PostMapping, @PutMapping, @DeleteMapping
(por completar)

## 26. @Autowired
Es una anotación utilizada para inyectar dependencias de manera automática en Spring. Permite a Spring gestionar la creación y el ciclo de vida de los objetos que necesita un componente, reduciendo la necesidad de configuraciones manuales o explícitas. Se puede aplicar en campos, métodos o constructores.

## 27. application.properties
(por completar)

## 28. @Entity
(por completar)

## 29. @Repository
(por completar)

## 30. @Service
(por completar)

## 31. JpaRepository
(por completar)

## 32. RestTemplate
(por completar)

## 33. ResponseEntity
(por completar)

## 34. DTO (Data Transfer Object)
(por completar)

## 35. JSON
Acronimo de "JavaScript Object Notation"(Notacion de objeto de JavaScript) es un formato de intercambio de datos, con su escritura y lectura siendo simple de comprender para una persona y facil de interpretar y generar para una maquina. Se basa en un subconjunto del lenguaje JavaScript, pero es independiente del lenguaje y utiliza convenciones que son familiares con otros lenguajes, como la familia de lenguajes C, Java, Python, entre otros. 
Su formato de archivo principal es .json.

Fuente: https://www.json.org/json-es.html
## 36. Endpoint
(por completar)

## 37. Puerto (server.port)
(por completar)

## 38. IDE (Entorno de desarrollo)
Un IDE (Integrated Development Environment) es una aplicación que proporciona herramientas esenciales para desarrollar software de forma más eficiente. Reúne en un solo entorno:
Editor de código (para escribir el programa)
Depurador (para encontrar y corregir errores)
Compilador o intérprete (para ejecutar el código)
Autocompletado y resaltado de sintaxis (para facilitar la escritura)
Gestión de archivos y proyectos

## 39. Terminal
(por completar)

## 40. Dependencias
(por completar)

## 41. Build (mvn clean install, spring-boot:run)
(por completar)

## 42. target/
(por completar)

## 43. Error 404 / Error 500
(por completar)

## 44. HTTP Status Codes
(por completar)

## 45. @PathVariable
(por completar)

## 46. @RequestParam
(por completar)

## 47. Clase Main (main() de Spring Boot)
(por completar)

## 48. Hot reload
(por completar)

## 49. Consola de logs
(por completar)

## 50. Carpeta src/main/java
(por completar)

## 51. Estructura de capas (Controller – Service – Repository)
(por completar)

