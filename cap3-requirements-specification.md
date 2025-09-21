# Capítulo III: Requirements Specification
## 3.1. User Stories
<table>
    <tr>
        <td>Epic / Story ID</td>
        <td>Título</td>
        <td>Descripción</td>
        <td>Criterios de Aceptación</td>
        <td>Relacionado con (Epic ID)</td>
    </tr>
      <tr>
      <td>EP-01</td>
      <td>Comunicación de valor y confianza en la página de inicio</td>
      <td>Como usuario, quiero entender de inmediato qué es PlantaE, sus beneficios y testimonios de otros usuarios, para sentirme motivado a registrarme.</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
        <td>EP-02</td>
        <td>Accesibilidad de la plataforma</td>
        <td>Como usuario, quiero que la plataforma sea accesible en móviles, tablets y escritorio, con modo oscuro y soporte de lectores de pantalla, para usarla sin barreras.</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>EP-03</td>
        <td>Gestión de autenticación y acceso</td>
        <td>Como usuario, quiero registrarme, iniciar sesión y recuperar mi contraseña, para acceder a mis cultivos de manera segura y sin inconvenientes.</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>EP-04</td>
        <td>Gestión al dashboard</td>
        <td>Como usuario, quiero acceder a un dashboard con métricas y mis plantas registradas, para supervisar mis plantas.</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>EP-05</td>
        <td>Gestión de perfil</td>
        <td>Como usuario, quiero editar mis datos personales, idioma y preferencias de notificación, para mantener mi perfil actualizado y adaptado a mis necesidades.</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>EP-06</td>
        <td>Gestión de plantas y sensores</td>
        <td>Como usuario, quiero registrar plantas y vincular sensores IoT (humedad, luz, temperatura), para monitorear el estado de mis cultivos en tiempo real.</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>EP-07</td>
        <td>Gestión de insumos y recursos de cultivo</td>
        <td>Como usuario, quiero llevar un registro básico de insumos (fertilizantes, semillas, tierra), para planificar mejor el cuidado de mis plantas.</td>
        <td></td>
        <td></td>
    </tr>    
    <tr>
        <td>EP-08</td>
        <td>Panel de métricas y estadísticas</td>
        <td>Como usuario, quiero ver gráficos de humedad, luz, temperatura y fertilización, para analizar la evolución de mis cultivos con datos históricos.</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>EP-09</td>
        <td>Notificaciones inteligentes y recordatorios</td>
        <td>Como usuario, quiero recibir alertas automáticas sobre humedad baja, falta de luz o fertilización pendiente, para actuar a tiempo y evitar problemas en mis plantas.</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>EP-10</td>
        <td>Seguimiento del estado de los cultivos</td>
        <td>Como usuario, quiero registrar y visualizar las fases de crecimiento de mis plantas, para planificar cuidados y saber cuándo cosechar.</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>EP-11</td>
        <td>Feedback y calificaciones comunitarias</td>
        <td>Como usuario, quiero calificar y comentar consejos de la comunidad, para apoyar las mejores prácticas y dar retroalimentación útil.</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>EP-12</td>
        <td>Gestión de catálogo de plantas</td>
        <td>Como usuario, quiero acceder a una biblioteca de plantas con fichas técnicas y cuidados básicos, para asociarlas a mis registros y aprender más sobre ellas.</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>EP-13</td>
        <td>Gestión de tareas y acciones programadas</td>
        <td>Como usuario, quiero programar tareas automáticas (regar, fertilizar, trasplantar), para no olvidar el cuidado de mis plantas.</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>EP-14</td>
        <td>Historial de cuidados y cosechas</td>
        <td>Como usuario, quiero guardar un historial de riegos, fertilizaciones, podas y cosechas, para llevar un control completo de mis cultivos.</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>EP-15</td>
        <td>Información institucional y autores</td>
        <td>Como visitante, quiero ver una sección sobre los autores de la aplicación y los objetivos del proyecto, para conocer quién está detrás de PlantaE.</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>US-01</td>
        <td>Acceso a la plataforma</td>
        <td>Como visitante, quiero registrarme o iniciar sesión, para acceder a las funcionalidades de PlantaE.</td>
        <td>
            <ul>
                <li>Escenario 1: Registro exitoso: Dado que el visitante no tiene cuenta, cuando ingresa datos válidos y confirma el registro, entonces el sistema crea la cuenta y lo dirige al dashboard.</li>
                <li>Escenario 2: Inicio de sesión válido: Dado que el usuario ya tiene cuenta, cuando ingresa sus credenciales correctas, entonces accede al sistema sin inconvenientes.</li>
            </ul>
        </td>
        <td>EP-03</td>
    </tr>
    <tr>
        <td>US-02</td>
        <td>Recuperación de contraseña</td>
        <td>Como usuario, quiero recuperar el acceso a mi cuenta mediante correo electrónico, para continuar usando la app aunque olvide mis credenciales.</td>
        <td>
            <ul>
                <li>Escenario 1: Solicitud válida: Dado que el usuario olvidó su contraseña, cuando ingresa su correo válido, entonces el sistema envía un enlace de recuperación.</li>
            </ul>
        </td>
        <td>EP-03</td>
    </tr>
    <tr>
        <td>US-03</td>
        <td>Gestión de plantas</td>
        <td>Como usuario, quiero registrar mis plantas con nombre, tipo y foto, para organizarlas y monitorearlas.</td>
        <td>
            <ul>
                <li>Escenario 1: Registro de planta: Dado que el usuario está en la sección “Mis plantas”, cuando ingresa nombre, tipo y foto, entonces el sistema guarda y muestra la planta en la lista.</li>
                <li>Escenario 2: Eliminación de planta: Dado que el usuario selecciona una planta, cuando confirma su eliminación, entonces el sistema la borra y actualiza la lista.</li>
            </ul>
        </td>
        <td>EP-04</td>
    </tr>
    <tr>
        <td>US-04</td>
        <td>Alertas de cultivo</td>
        <td>Como usuario, quiero recibir notificaciones sobre humedad, luz o temperatura, para cuidar mis plantas a tiempo.</td>
        <td>
            <ul>
                <li>Escenario 1: Alerta de humedad baja: Dado que la humedad cae bajo el umbral, cuando el sistema recibe el dato, entonces envía una alerta de riego al usuario.</li>
                <li>Escenario 2: Historial de alertas: Dado que el usuario ha recibido alertas, cuando accede al historial, entonces ve una lista cronológica de notificaciones.</li>
            </ul>
        </td>
        <td>EP-05</td>
    </tr>
    <tr>
        <td>US-05</td>
        <td>Recomendaciones personalizadas</td>
        <td>Como usuario, quiero recibir consejos basados en mi tipo de planta y datos históricos, para mejorar su salud.</td>
        <td>
            <ul>
                <li>Escenario 1: Generación de consejo: Dado que el usuario tiene plantas registradas, cuando el sistema analiza los datos de sensores, entonces genera recomendaciones de cuidado.</li>
            </ul>
        </td>
        <td>EP-05</td>
    </tr>
    <tr>
        <td>US-06</td>
        <td>Panel de métricas</td>
        <td>Como usuario, quiero ver gráficos de humedad, temperatura y luz, para analizar tendencias de mis plantas.</td>
        <td>
            <ul>
                <li>Escenario 1: Visualización de gráficos: Dado que hay datos históricos de sensores, cuando el usuario selecciona una planta, entonces se muestran gráficas de humedad, luz y temperatura.</li>
            </ul>
        </td>
        <td>EP-07</td>
    </tr>
    <tr>
        <td>US-07</td>
        <td>Gestión de perfil</td>
        <td>Como usuario, quiero actualizar mis datos e idioma preferido, para personalizar mi experiencia en PlantaE.</td>
        <td>
            <ul>
                <li>Escenario 1: Edición de datos: Dado que el usuario está en su perfil, cuando actualiza su nombre o correo válido, entonces el sistema guarda los cambios.</li>
                <li>Escenario 2: Cambio de idioma: Dado que la plataforma soporta español e inglés, cuando el usuario cambia el idioma, entonces todo el contenido se muestra en el idioma seleccionado.</li>
            </ul>
        </td>
        <td>EP-06</td>
    </tr>
    <tr>
        <td>US-08</td>
        <td>Alternar modo oscuro/claro</td>
        <td>Como usuario, quiero poder cambiar entre modo oscuro y claro, para visualizar la página de acuerdo a mis preferencias.</td>
        <td>
            <ul>
                <li>Escenario 1: Cambio manual: Dado que el usuario navega en la plataforma, cuando activa el botón de modo oscuro, entonces la interfaz cambia inmediatamente a ese esquema de colores.</li>
            </ul>
        </td>
        <td>EP-02</td>
    </tr>
    <tr>
        <td>US-09</td>
        <td>Sección de contáctanos</td>
        <td>Como visitante, quiero tener un formulario de contacto, para enviar consultas o sugerencias directamente al equipo de PlantaE.</td>
        <td>
            <ul>
                <li>Escenario 1: Envío válido: Dado que el visitante completa nombre, correo electrónico y mensaje, cuando hace clic en “Enviar”, entonces el sistema almacena la solicitud y notifica al equipo.</li>
                <li>Escenario 2: Validación de campos: Dado que el visitante deja un campo obligatorio vacío o ingresa un correo inválido, cuando intenta enviar el formulario, entonces el sistema muestra un error y no permite el envío.</li>
            </ul>
        </td>
        <td>EP-01</td>
    </tr>
    <tr>
        <td>US-10</td>
        <td>Mostrar autores de la aplicación</td>
        <td>Como visitante, quiero ver una sección con los autores de la app, para conocer quiénes desarrollaron PlantaE.</td>
        <td>
            <ul>
                <li>Escenario 1: Visualización de autores <br>Dado que el visitante accede a la sección “Sobre nosotros”, cuando carga el contenido, entonces ve una lista con nombres, roles y fotos de los autores.</li>
            </ul>
        </td>
        <td>EP-01</td>
    </tr>
    <tr>
        <td>US-11</td>
        <td>Agregar sensores IoT</td>
        <td>Como usuario, quiero poder vincular un nuevo sensor IoT a una planta, para empezar a recibir datos.</td>
        <td>
            <ul>
                <li>Escenario 1: Vinculación exitosa: Dado que el usuario tiene un sensor nuevo, cuando ingresa su código de registro válido, entonces el sistema lo vincula a la planta seleccionada.</li>
                <li>Escenario 2: Código inválido: Dado que el usuario ingresa un código incorrecto, cuando intenta registrarlo, entonces el sistema muestra un mensaje de error.</li>
            </ul>
        </td>
        <td>EP-04</td>
    </tr>
    <tr>
        <td>US-12</td>
        <td>Visualizar sensores más activos</td>
        <td>Como usuario, quiero ver cuáles sensores registran más actividad, para identificar cultivos con mayor demanda de cuidado.</td>
        <td>
            <ul>
                <li>Escenario 1: Ranking de actividad: Dado que hay sensores vinculados, cuando el usuario abre el panel de métricas, entonces el sistema muestra un ranking con los sensores más activos.</li>
            </ul>
        </td>
        <td>EP-07</td>
    </tr>
    <tr>
        <td>US-13</td>
        <td>Ver alertas recientes</td>
        <td>Como usuario, quiero ver un panel con mis últimas alertas de plantas, para actuar rápido.</td>
        <td>
            <ul>
                <li>Escenario 1: Visualización de alertas: Dado que existen alertas activas, cuando el usuario accede al panel, entonces se muestran clasificadas por tipo (riego, temperatura, luz).</li>
            </ul>
        </td>
        <td>EP-05</td>
    </tr>
    <tr>
        <td>US-14</td>
        <td>Identificar mis plantas más críticas</td>
        <td>Como usuario, quiero ver qué plantas requieren más atención, para priorizar su cuidado.</td>
        <td>
            <ul>
                <li>Escenario 1: Orden de criticidad: Dado que hay varias plantas registradas, cuando el sistema detecta alertas, entonces las ordena por nivel de criticidad en el dashboard.</li>
            </ul>
        </td>
        <td>EP-07</td>
    </tr>
    <tr>
        <td>US-15</td>
        <td>Registro de cosechas</td>
        <td>Como usuario, quiero registrar las veces que cosecho una planta, para llevar un historial de producción.</td>
        <td>
            <ul>
                <li>Escenario 1: Registro exitoso: Dado que el usuario cosecha una planta, cuando ingresa fecha y cantidad, entonces el sistema guarda el registro en el historial.</li>
                <li>Escenario 2: Registro incompleto: Dado que el usuario omite un dato obligatorio, cuando intenta guardar, entonces el sistema muestra un error.</li>
            </ul>
        </td>
        <td>EP-07</td>
    </tr>
    <tr>
        <td>US-16</td>
        <td>Seguimiento de estado de cultivo</td>
        <td>Como usuario, quiero ver las fases de crecimiento de mis plantas, para planificar mejor sus cuidados.</td>
        <td>
            <ul>
                <li>Escenario 1: Cambio automático de fase: Dado que el sistema tiene datos históricos, cuando detecta patrones de crecimiento, entonces actualiza automáticamente la fase de la planta.</li>
            </ul>
        </td>
        <td>EP-04</td>
    </tr>
    <tr>
        <td>US-17</td>
        <td>Visualizar feedback de la comunidad</td>
        <td>Como usuario, quiero ver comentarios y calificaciones de consejos publicados, para identificar las mejores prácticas.</td>
        <td>
            <ul>
                <li>Escenario 1: Visualización de feedback: Dado que existen comentarios en un consejo, cuando el usuario lo abre, entonces puede leerlos con sus calificaciones.</li>
            </ul>
        </td>
        <td>EP-08</td>
    </tr>
    <tr>
        <td>US-18</td>
        <td>Visualizar lista de sensores activos</td>
        <td>Como usuario, quiero ver todos los sensores conectados, para controlar qué plantas están siendo monitoreadas.</td>
        <td>
            <ul>
                <li>Escenario 1: Listado de sensores: Dado que hay sensores vinculados, cuando el usuario accede al panel de sensores, entonces se listan con estado y planta asociada.</li>
                <li>Escenario 2: Eliminación de sensor: Dado que el usuario ya no quiere usar un sensor, cuando lo elimina, entonces desaparece de la lista y se desasocia de la planta.</li>
            </ul>
        </td>
        <td>EP-04</td>
    </tr>
    <tr>
        <td>US-19</td>
        <td>Consultar datos de un sensor</td>
        <td>Como usuario, quiero ver todos los registros de un sensor específico, para entender el comportamiento de una planta.</td>
        <td>
            <ul>
                <li>Escenario 1: Consulta detallada: Dado que un sensor tiene registros, cuando el usuario lo selecciona, entonces el sistema muestra los datos históricos en gráficas.</li>
            </ul>
        </td>
        <td>EP-04</td>
    </tr>
    <tr>
        <td>US-20</td>
        <td>Historial de alertas por planta</td>
        <td>Como usuario, quiero ver todas las alertas recibidas de una planta, para llevar un control de su evolución.</td>
        <td>
            <ul>
                <li>Escenario 1: Listado cronológico: Dado que la planta ha generado alertas, cuando el usuario abre su historial, entonces se muestran en orden de fecha.</li>
            </ul>
        </td>
        <td>EP-05</td>
    </tr>
    <tr>
        <td>US-21</td>
        <td>Descargar reportes</td>
        <td>Como usuario, quiero descargar un reporte de mis cultivos en Excel o PDF, para analizar mis datos fuera de la plataforma.</td>
        <td>
            <ul>
                <li>Escenario 1: Generación exitosa: Dado que el usuario tiene datos registrados, cuando solicita un reporte, entonces el sistema genera el archivo con la información.</li>
            </ul>
        </td>
        <td>EP-07</td>
    </tr>
    <tr>
        <td>US-22</td>
        <td>Cambio de contraseña</td>
        <td>Como usuario autenticado, quiero cambiar mi contraseña, para mantener la seguridad de mi cuenta.</td>
        <td>
            <ul>
                <li>Escenario 1: Cambio exitoso: Dado que el usuario conoce su contraseña actual, cuando ingresa una nueva válida, entonces el sistema actualiza la información y confirma el cambio.</li>
                <li>Escenario 2: Contraseña incorrecta: Dado que el usuario ingresa la contraseña actual incorrecta, cuando intenta cambiarla, entonces el sistema rechaza la solicitud.</li>
            </ul>
        </td>
        <td>EP-03</td>
    </tr>
    <tr>
        <td>US-23</td>
        <td>Eliminar cuenta</td>
        <td>Como usuario, quiero poder eliminar mi cuenta, para dejar de usar PlantaE y borrar mis datos personales.</td>
        <td>
            <ul>
                <li>Escenario 1: Eliminación exitosa: Dado que el usuario confirma la acción, cuando acepta eliminar su cuenta, entonces el sistema borra toda su información.</li>
            </ul>
        </td>
        <td>EP-03</td>
    </tr>
    <tr>
        <td>US-24</td>
        <td>Consultar Preguntas Frecuentes</td>
        <td>Como visitante, quiero ver una sección de FAQ sobre sensores y uso de la app, para resolver dudas rápidas.</td>
        <td>
            <ul>
                <li>Escenario 1: Visualización de FAQ: Dado que el visitante accede a la sección de ayuda, cuando la abre, entonces el sistema muestra al menos tres preguntas frecuentes con respuestas claras.</li>
            </ul>
        </td>
        <td>EP-01</td>
    </tr>
    <tr>
        <td>US-25</td>
        <td>Contacto directo</td>
        <td>Como visitante, quiero enviar mis datos y mensaje al equipo PlantaE, para resolver dudas o sugerir mejoras.</td>
        <td>
            <ul>
                <li>Escenario 1: Envío válido: Dado que el visitante completa nombre, email y mensaje, cuando envía el formulario, entonces el sistema almacena la solicitud.</li>
                <li>Escenario 2: Confirmación de recepción: Dado que el sistema recibió la solicitud, cuando termina el proceso, entonces muestra el mensaje “Gracias por tu mensaje, te responderemos pronto”.</li>
            </ul>
        </td>
        <td>EP-01</td>
    </tr>
    <tr>
        <td>US-26</td>
        <td>Información institucional</td>
        <td>Como visitante, quiero ver redes sociales, contacto y términos legales en todo el sitio, para obtener soporte y conocer condiciones de uso.</td>
        <td>
            <ul>
                <li>Escenario 1: Footer visible: Dado que el visitante navega en el sitio, cuando se desplaza, entonces siempre visualiza la sección de información institucional.</li>
            </ul>
        </td>
        <td>EP-01</td>
    </tr>
    <tr>
        <td>US-27</td>
        <td>Acceso a secciones principales</td>
        <td>Como visitante, quiero navegar fácilmente a Inicio, Beneficios y Contacto, para entender PlantaE.</td>
        <td>
            <ul>
                <li>Escenario 1: Navegación desde menú: Dado que el visitante accede al sitio, cuando abre el menú principal, entonces puede ingresar a las secciones clave.</li>
            </ul>
        </td>
        <td>EP-01</td>
    </tr>
     <tr>
        <td>US-28</td>
        <td>Comprensión inmediata</td>
        <td>Como visitante, quiero entender en segundos qué es PlantaE, para captar rápido su valor.</td>
        <td>
            <ul>
                <li>Escenario 1: Mensaje principal visible <br>Dado que el visitante accede al sitio, cuando carga la página, entonces visualiza el mensaje de valor en la primera pantalla.</li>
            </ul>
        </td>
        <td>EP-01</td>
    </tr>
    <tr>
        <td>US-29</td>
        <td>Beneficios segmentados</td>
        <td>Como visitante, quiero ver beneficios adaptados a mi perfil (hogar, vivero, comunidad), para entender cómo me ayuda PlantaE.</td>
        <td>
            <ul>
                <li>Escenario 1: Segmentación visible: Dado que el visitante entra a la sección de beneficios, cuando la revisa, entonces encuentra información diferenciada según su perfil.</li>
            </ul>
        </td>
        <td>EP-01</td>
    </tr>
    <tr>
        <td>US-30</td>
        <td>Selección de idioma</td>
        <td>Como usuario, quiero poder cambiar entre inglés y español, para usar la app en mi idioma preferido.</td>
        <td>
            <ul>
                <li>Escenario 1: Cambio exitoso: Dado que el idioma actual es español, cuando el usuario cambia a inglés, entonces el sistema actualiza todo el contenido textual.</li>
                <li>Escenario 2: Persistencia de idioma: Dado que el usuario seleccionó español, cuando vuelve a navegar dentro de la sesión, entonces el sistema mantiene el idioma elegido.</li>
            </ul>
        </td>
        <td>EP-02</td>
    </tr>
    <tr>
        <td>US-31</td>
        <td>Optimización para escritorio</td>
        <td>Como usuario, quiero ver el sitio optimizado en pantallas grandes, para tener toda la información visible sin esfuerzo.</td>
        <td>
            <ul>
                <li>Escenario 1: Visualización completa: Dado que el visitante accede desde una PC, cuando carga la página, entonces el sistema distribuye el contenido de forma clara y amplia.</li>
                <li>Escenario 2: Panel accesible: Dado que el usuario usa desktop, cuando abre el dashboard, entonces ve métricas y datos sin necesidad de scroll excesivo.</li>
            </ul>
        </td>
        <td>EP-02</td>
    </tr>
    <tr>
        <td>US-32</td>
        <td>Navegación fluida</td>
        <td>Como visitante, quiero que cada sección del sitio esté claramente diferenciada, para comprender la estructura.</td>
        <td>
            <ul>
                <li>Escenario 1: Secciones identificables: Dado que el visitante navega, cuando recorre la página, entonces identifica claramente las secciones separadas.</li>
                <li>Escenario 2: Flujo natural: Dado que el visitante se desplaza, cuando pasa de una sección a otra, entonces entiende el orden sin perderse.</li>
            </ul>
        </td>
        <td>EP-02</td>
    </tr>
    <tr>
        <td>US-33</td>
        <td>Testimonios de usuarios</td>
        <td>Como visitante, quiero leer testimonios de otros usuarios de PlantaE, para confiar más en la plataforma.</td>
        <td>
            <ul>
                <li>Escenario 1: Ver testimonios <br>Dado que el visitante en la página, cuando llega a la sección de testimonios, entonces visualiza al menos tres experiencias reales.</li>
                <li>Escenario 2: Datos del testimonio <br>Dado que se muestra un testimonio, cuando el visitante lo lee, entonces identifica nombre, tipo de usuario y comentario.</li>
            </ul>
        </td>
        <td>EP-01</td>
    </tr>
</table>

## 3.2. Impact Mapping
<div align="center">
  <img src="assets/images/impact-mapping.png" alt="Impact">
</div>

## 3.3. Product Backlog
  | Orden | User Story Id | Título                           | Descripción                                                                                                                                   | Story Points |
  | ----- | ------------- | -------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ------------ |
  | 1     | US-01         | Acceso a la plataforma           | Como visitante, quiero registrarme o iniciar sesión, para acceder a las funcionalidades de PlantaE.                                           | 5            |
  | 2     | US-02         | Recuperación de contraseña       | Como usuario, quiero recuperar mi contraseña mediante correo electrónico, para continuar usando la app aunque olvide mis credenciales.        | 3            |
  | 3     | US-03         | Gestión de plantas               | Como usuario, quiero registrar mis plantas con nombre, tipo y foto, para organizarlas y monitorearlas.                                        | 8            |
  | 4     | US-11         | Agregar sensores IoT             | Como usuario, quiero poder vincular un nuevo sensor IoT a una planta, para empezar a recibir datos.                                           | 8            |
  | 5     | US-04         | Alertas de cultivo               | Como usuario, quiero recibir notificaciones sobre humedad, luz o temperatura, para cuidar mis plantas a tiempo.                               | 8            |
  | 6     | US-05         | Recomendaciones personalizadas   | Como usuario, quiero recibir consejos basados en mi tipo de planta y datos históricos, para mejorar su salud.                                 | 5            |
  | 7     | US-06         | Panel de métricas                | Como usuario, quiero ver gráficos de humedad, temperatura y luz, para analizar tendencias de mis plantas.                                     | 8            |
  | 8     | US-13         | Ver alertas recientes            | Como usuario, quiero ver un panel con mis últimas alertas de plantas, para actuar rápido.                                                     | 5            |
  | 9     | US-14         | Identificar plantas críticas     | Como usuario, quiero ver qué plantas requieren más atención, para priorizar su cuidado.                                                       | 5            |
  | 10    | US-15         | Registro de cosechas             | Como usuario, quiero registrar las veces que cosecho una planta, para llevar un historial de producción.                                      | 5            |
  | 11    | US-16         | Seguimiento de estado de cultivo | Como usuario, quiero ver las fases de crecimiento de mis plantas, para planificar mejor sus cuidados.                                         | 8            |
  | 12    | US-21         | Descargar reportes               | Como usuario, quiero descargar un reporte de mis cultivos en Excel o PDF, para analizar mis datos fuera de la plataforma.                     | 5            |
  | 13    | US-07         | Gestión de perfil                | Como usuario, quiero actualizar mis datos e idioma preferido, para personalizar mi experiencia en PlantaE.                                    | 3            |
  | 14    | US-08         | Alternar modo oscuro/claro       | Como usuario, quiero poder cambiar entre modo oscuro y claro, para visualizar la página de acuerdo a mis preferencias.                        | 3            |
  | 15    | US-09         | Sección de contáctanos           | Como visitante, quiero tener un formulario de contacto, para enviar consultas o sugerencias directamente al equipo de PlantaE.                | 5            |
