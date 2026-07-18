# 🛡️ Seguridad Informática

La seguridad informática comprende el conjunto de mecanismos técnicos, administrativos y organizacionales orientados a proteger los sistemas informáticos y la información frente a amenazas y vulnerabilidades. 

Sin embargo, la seguridad informática no depende únicamente de herramientas tecnológicas, sino también del comportamiento responsable de las personas encargadas de administrar los sistemas. 

## Mecanismos de Protección
Las organizaciones implementan medidas técnicas como mecanismos de protección frente a amenazas tecnológicas, las cuales incluyen:
* Políticas de control de acceso.
* Cifrado de información.
* Monitoreo de actividades.

## Estrategia de Defensa en Profundidad (Defense in Depth)

La seguridad no debe ser una capa aislada, sino un atributo transversal a toda la infraestructura. Implementamos un modelo de seguridad por capas para mitigar riesgos en cada punto del ciclo de vida del sistema:

### 1. Seguridad en el Desarrollo (AppSec & DevSecOps)
* **Integración en CI/CD:** Automatizar escaneos de vulnerabilidades estáticas (SAST) y dinámicas (DAST) en el código fuente antes de cualquier despliegue en entornos de producción.
* **Gestión de Secretos:** Utilizar bóvedas de gestión de secretos (Secret Managers) en lugar de exponer variables de entorno o archivos de configuración inseguros que puedan ser comprometidos.

### 2. Seguridad de Redes (Zero Trust Architecture)
* **Principio de Confianza Cero:** Asumir que ninguna entidad (interna o externa) es confiable por defecto; cada petición de red debe ser autenticada, autorizada y validada antes de permitir el acceso.
* **Segregación de Redes:** Implementar segmentación de redes y VLANs para aislar los entornos de producción, desarrollo y pruebas, limitando el movimiento lateral de un atacante en caso de brecha.

### 3. Gobernanza y Protección de Datos
* **Principio de Menor Privilegio (PoLP):** Otorgar a los usuarios, aplicaciones y procesos únicamente los permisos estrictamente necesarios para realizar sus funciones operativas, reduciendo la superficie de ataque.
* **Anonimización y Pseudonimización:** Garantizar que los datos sensibles utilizados en entornos de pruebas, analítica o entrenamiento de modelos de IA no puedan ser rastreados hasta el individuo, cumpliendo con los estándares de privacidad.

---

## Matriz de Responsabilidad compartida
La seguridad es una responsabilidad compartida entre el proveedor de servicios en la nube (ej. Vercel, Render, Neon) y el equipo de ingeniería. Nuestro compromiso es:
* **Configuración Segura:** Responsabilidad del equipo de ingeniería sobre la configuración lógica del sistema.
* **Integridad de la Infraestructura:** Confianza en los protocolos de seguridad provistos por las plataformas de despliegue, siempre validados bajo pruebas de penetración periódicas.
