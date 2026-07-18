## ⚠️ Clasificación Técnica de Incidentes Éticos

Los incidentes éticos no son accidentales; suelen ser el resultado de una gestión negligente en las capas técnicas de ingeniería. A continuación, clasificamos los incidentes críticos divididos por áreas de especialización:

### 1. Ingeniería de Software y Sistemas Web
*   **Fugas de Datos en E-commerce:** Incidentes donde el manejo inseguro de la información de clientes (ej. al implementar sistemas de venta online) expone datos personales sin cifrado.
*   **Manipulación de la Experiencia de Usuario (Dark Patterns):** Implementación de interfaces que inducen al error, como ocultar los costos de envío o el procesamiento de pagos, comprometiendo la transparencia del sistema.
*   **Vulnerabilidades por Deuda Técnica:** Dejar expuestas rutas de API o configuraciones (como dejar endpoints sin autenticación) que permiten accesos no autorizados a la base de datos de usuarios.

### 2. Ingeniería de Redes, IoT y Telecomunicaciones
*   **Interceptación en Redes IoT:** Incidentes donde la falta de seguridad en protocolos de comunicación (ej. en dispositivos IoT de monitoreo) permite la interceptación de tramas de datos geográficos o de estado.
*   **Configuraciones Inseguras de Enrutamiento:** Incidentes donde una mala configuración en protocolos de red (como el uso indebido de túneles o reglas de enrutamiento) permite el acceso no autorizado a nodos de la infraestructura o la intercepción de tráfico.
*   **Uso No Autorizado de Recursos:** Aprovechamiento de la infraestructura de red (ej. controladores SDN) para actividades ajenas a la misión del sistema, comprometiendo la integridad de la topología.

### 3. Ingeniería de Datos y Estadística
*   **Sesgo en la Inferencia Estadística:** Incidentes donde se manipulan los resultados de un análisis (ej. en el procesamiento de líneas móviles activas o PIB) mediante la selección tendenciosa de variables para validar una hipótesis falsa.
*   **Falsificación de Hallazgos:** Presentación de resultados estadísticos que omiten datos críticos (valores atípicos o alta dispersión) para presentar un panorama artificialmente estable de la realidad.
*   **Exposición de Datos Sensibles en Reportes:** Difusión de informes que, aunque contengan datos agregados, permiten la re-identificación de sujetos individuales debido a una anonimización deficiente.
