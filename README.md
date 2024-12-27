Veloccgps - README
Descripción
Veloccgps es una aplicación web que utiliza la API de geolocalización para proporcionar información en tiempo real sobre velocidad, distancia recorrida, altitud, tiempo transcurrido y más. Ha sido diseñada para funcionar de manera óptima en dispositivos móviles y está dirigida a ciclistas, conductores, y cualquier persona que desee realizar un seguimiento básico de sus métricas de desplazamiento.

La aplicación incluye un diseño inspirado en las interfaces retro con texto verde brillante sobre fondo negro, haciendo uso de la fuente pixelada Press Start 2P para un toque nostálgico.

Características
Velocidad actual: Muestra la velocidad en km/h basada en datos GPS.
Distancia recorrida: Calcula y visualiza la distancia en kilómetros desde que comienza el seguimiento.
Velocidad máxima y promedio: Muestra las velocidades más alta y promedio alcanzadas durante la sesión.
Altitud: Obtiene la altitud del dispositivo respecto al nivel del mar.
Tiempo transcurrido: Indica la duración total de la sesión.
Modo Bici/Auto: Permite alternar entre diferentes modos según el tipo de vehículo usado.
Compatibilidad con pantalla completa: Ideal para maximizar la experiencia en dispositivos móviles.
Botones interactivos:
Iniciar/Detener seguimiento.
Cambiar de modo (Bici/Auto).
Reiniciar métricas.
Guardar datos de la sesión.
Capturas de pantalla
(Puedes incluir imágenes o gifs que muestren la funcionalidad y diseño de la aplicación en esta sección.)

Tecnologías utilizadas
HTML5: Estructura principal del proyecto.
CSS3: Estilización avanzada utilizando fuentes personalizadas y diseño responsivo.
Bootstrap 5.3: Implementación de un diseño moderno y adaptable.
JavaScript:
API de geolocalización para obtener datos de velocidad, posición y altitud.
Funciones para calcular métricas en tiempo real.
Instalación
Clonar el repositorio:
bash
Copiar código
git clone https://github.com/tuusuario/velocimetro-gps.git  
cd velocimetro-gps  
Abrir el archivo index.html en cualquier navegador moderno compatible con la API de geolocalización.
¡Listo! La aplicación estará funcionando de inmediato.
Requisitos
Navegador web con soporte para la API de geolocalización.
Permitir el acceso a la ubicación en el navegador.
Uso
Abre la aplicación en un navegador.
Permite el acceso al GPS cuando sea solicitado.
Usa los botones:
Iniciar/Detener: Comienza o detén el seguimiento.
Reiniciar: Limpia todas las métricas para empezar desde cero.
Guardar: Muestra en consola los datos de la sesión en formato JSON.
Cambiar modo: Alterna entre los modos Bici y Auto.
Pantalla completa: Activa/desactiva el modo de pantalla completa.
Observa las métricas actualizándose en tiempo real.
Personalización
Si deseas personalizar este proyecto:

Modifica los estilos en el bloque <style> o crea un archivo CSS independiente.
Cambia las funciones en el bloque <script> para incluir nuevas métricas.
Implementa mejoras en el diseño de la interfaz con Bootstrap o CSS puro.
Notas importantes
La velocidad puede mostrar "0" si el GPS no recibe datos precisos (por ejemplo, dentro de edificios).
El proyecto está diseñado para dispositivos con GPS habilitado.
Las métricas son aproximadas y no deben ser utilizadas para cálculos precisos o legales.
Posibles mejoras
Agregar soporte para guardar datos en una base de datos o archivo local.
Implementar gráficos para visualizar la evolución de las métricas.
Crear una versión PWA (Progressive Web App) para instalar la aplicación en dispositivos móviles.
Traducir la aplicación a otros idiomas.
Optimizar el código para reducir el consumo de batería en dispositivos móviles.
Licencia
Este proyecto se distribuye bajo la licencia MIT. Siéntete libre de usar, modificar y compartir, siempre y cuando menciones al autor original.

Contribuciones
¡Las contribuciones son bienvenidas! Si tienes sugerencias, errores o mejoras, abre un issue o envía un pull request.

Autor
@Emiliando
2024
