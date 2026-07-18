## Auditorías Éticas por Áreas de la Ingeniería Informática y Sistemas

La evaluación de incidentes y dilemas éticos no se limita a la interfaz, sino que atraviesa todas las capas tecnológicas de un proyecto. Este Playbook categoriza las auditorías en las tres ramas fundamentales de la disciplina:

### 1. Ingeniería de Software y Arquitectura Web
Se enfoca en la ética del código, la construcción de plataformas (como sistemas web e-commerce) y la interacción directa con el usuario final.
*   **Deuda Técnica Consciente:** Auditar que las decisiones de arquitectura y despliegue rápido no comprometan la seguridad a largo plazo del sistema ni expongan vulnerabilidades conocidas en la lógica de negocio.
*   **Manipulación de Requerimientos (Dark Patterns):** Revisar que los requisitos funcionales (como la gestión de un carrito de compras o la generación de pedidos) no integren flujos engañosos que fuercen acciones no deseadas por el consumidor.
*   **Privacidad por Diseño (Privacy by Design):** Asegurar que las validaciones de cobertura logística y procesamiento de pagos recopilen única y estrictamente los datos necesarios para la transacción.

### 2. Ingeniería de Redes y Telecomunicaciones
Se enfoca en la infraestructura subyacente, el enrutamiento de paquetes y la administración del tráfico.
*   **Neutralidad y Gestión de Tráfico (SDN):** En arquitecturas de Redes Definidas por Software (ej. controladores Ryu y emuladores Mininet), auditar que las reglas de flujo y priorización de tráfico no se utilicen para censurar, ralentizar o discriminar servicios competidores de forma anticompetitiva.
*   **Privacidad a Nivel de Paquete:** Establecer protocolos éticos frente a la inspección profunda de paquetes (DPI). Garantizar que la administración de topologías con IPv6 o protocolos de enrutamiento dinámico (como OSPFv3) no se utilice para vigilancia injustificada o intercepción de datos de los usuarios.
*   **Alta Disponibilidad como Responsabilidad Social:** Auditar que los protocolos de redundancia (como VRRP) se configuren correctamente para evitar caídas de servicio en infraestructuras críticas (hospitales, sistemas financieros) donde una desconexión supone un riesgo humano o económico severo.

### 3. Ingeniería de Datos y Estadística Inferencial
Se enfoca en la recolección masiva de información, el entrenamiento de algoritmos y el análisis predictivo.
*   **Sesgos en el Contraste de Hipótesis:** Auditar que los modelos de inferencia estadística no fuercen correlaciones espurias. Al analizar bases de datos (como métricas de PIB y esperanza de vida por continentes), asegurar que las variables elegidas no invisibilicen o estigmaticen a poblaciones vulnerables.
*   **Procedencia y Consentimiento de Datasets:** Verificar que los conjuntos de datos masivos utilizados para análisis predictivos hayan sido obtenidos de forma transparente y con el consentimiento adecuado de los usuarios o entidades originarias.
*   **Transparencia Algorítmica:** Garantizar que los coeficientes de los modelos de datos y los gráficos generados (ej. visualizaciones en Python) representen la realidad de forma objetiva, sin manipular la escala o la perspectiva para favorecer agendas políticas o corporativas.
