<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Velocímetro GPS - README</title>
</head>
<body>
    <h1>Velocímetro GPS</h1>
    <h2>Descripción</h2>
    <p>
        <strong>Velocímetro GPS</strong> es una aplicación web que utiliza la API de geolocalización para proporcionar información en tiempo real sobre velocidad, distancia recorrida, altitud, tiempo transcurrido y más. Diseñada con un estilo retro, esta herramienta es ideal para ciclistas, conductores y cualquier persona interesada en monitorear sus métricas de desplazamiento.
    </p>

    <h2>Características</h2>
    <ul>
        <li>Velocidad actual en tiempo real.</li>
        <li>Distancia recorrida en kilómetros.</li>
        <li>Velocidades máxima y promedio alcanzadas durante la sesión.</li>
        <li>Altitud basada en datos GPS.</li>
        <li>Tiempo transcurrido desde el inicio de la sesión.</li>
        <li>Modo configurable: <em>Bici</em> o <em>Auto</em>.</li>
        <li>Modo de pantalla completa para maximizar la experiencia.</li>
        <li>Botones interactivos para iniciar/detener, reiniciar y guardar datos.</li>
    </ul>

    <h2>Capturas de pantalla</h2>
    <p>*Aquí puedes incluir imágenes o gifs que muestren la funcionalidad y diseño de la aplicación.*</p>

    <h2>Tecnologías utilizadas</h2>
    <ul>
        <li><strong>HTML5</strong>: Estructura principal del proyecto.</li>
        <li><strong>CSS3</strong>: Estilización avanzada con fuentes personalizadas y diseño responsivo.</li>
        <li><strong>Bootstrap 5.3</strong>: Implementación de componentes y diseño adaptable.</li>
        <li><strong>JavaScript</strong>: API de geolocalización y cálculo de métricas en tiempo real.</li>
    </ul>

    <h2>Instalación</h2>
    <ol>
        <li>Clonar el repositorio:
            <pre><code>
git clone https://github.com/tuusuario/velocimetro-gps.git
cd velocimetro-gps
            </code></pre>
        </li>
        <li>Abrir el archivo <code>index.html</code> en cualquier navegador compatible.</li>
        <li>¡Listo! La aplicación estará funcionando de inmediato.</li>
    </ol>

    <h2>Requisitos</h2>
    <ul>
        <li>Navegador con soporte para la API de geolocalización.</li>
        <li>Permitir el acceso a la ubicación en el navegador.</li>
    </ul>

    <h2>Uso</h2>
    <ol>
        <li>Abre la aplicación en tu navegador.</li>
        <li>Permite el acceso al GPS cuando sea solicitado.</li>
        <li>Interacciona con los botones:
            <ul>
                <li><strong>Iniciar/Detener</strong>: Comienza o detén el seguimiento.</li>
                <li><strong>Reiniciar</strong>: Limpia las métricas para un nuevo inicio.</li>
                <li><strong>Guardar</strong>: Muestra en consola los datos de la sesión en formato JSON.</li>
                <li><strong>Cambiar Modo</strong>: Alterna entre los modos <em>Bici</em> y <em>Auto</em>.</li>
                <li><strong>Pantalla Completa</strong>: Activa o desactiva el modo de pantalla completa.</li>
            </ul>
        </li>
        <li>Observa cómo se actualizan las métricas en tiempo real.</li>
    </ol>

    <h2>Personalización</h2>
    <p>Para personalizar la aplicación:</p>
    <ul>
        <li>Modifica los estilos en el bloque <code>&lt;style&gt;</code> o crea un archivo CSS independiente.</li>
        <li>Actualiza las funciones en el bloque <code>&lt;script&gt;</code> para agregar nuevas métricas.</li>
        <li>Mejora el diseño de la interfaz usando Bootstrap o CSS personalizado.</li>
    </ul>

    <h2>Notas importantes</h2>
    <ul>
        <li>La velocidad puede mostrar "0" si el GPS no recibe datos precisos.</li>
        <li>El proyecto está optimizado para dispositivos con GPS habilitado.</li>
        <li>Las métricas son aproximadas y no deben usarse para cálculos legales o profesionales.</li>
    </ul>

    <h2>Posibles mejoras</h2>
    <ul>
        <li>Agregar soporte para guardar datos en una base de datos o archivo local.</li>
        <li>Implementar gráficos para visualizar la evolución de las métricas.</li>
        <li>Crear una versión PWA para instalar la aplicación en dispositivos móviles.</li>
        <li>Traducir la interfaz a otros idiomas.</li>
        <li>Optimizar el código para reducir el consumo de batería en dispositivos móviles.</li>
    </ul>

    <h2>Licencia</h2>
    <p>Este proyecto se distribuye bajo la licencia <strong>MIT</strong>. Puedes usar, modificar y compartir el código mencionando al autor original.</p>

    <h2>Contribuciones</h2>
    <p>Las contribuciones son bienvenidas. Si tienes ideas, errores o mejoras, abre un <code>issue</code> o envía un <code>pull request</code>.</p>

    <h2>Autor</h2>
    <p>
        <strong>@Emiliando</strong><br>
        2024
    </p>
</body>
</html
