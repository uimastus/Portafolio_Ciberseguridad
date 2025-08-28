# 🔐 Portafolio de Ciberseguridad – Juan Pablo Tovar

Bienvenido a mi portafolio como estudiante de Ingeniería en Software y Redes, con especialización en ciberseguridad como analista principiante. Aquí encontrarás proyectos, certificaciones y recursos que reflejan mi formación técnica y compromiso con la protección digital.
Me entusiasma la seguridad de la información y disfruto encontrando soluciones que puedan repercutir positivamente en una organización y en las personas a las que sirve. Valoro mucho mantener una postura de seguridad sólida para ayudar a proteger la información sensible y mitigar los riesgos.

## 🧾 Auditoría Interna de TI – Caso Juguetes x

Este escenario simulado presenta una auditoría interna de ciberseguridad aplicada a **Juguetes x**, una empresa ficticia dedicada al desarrollo y venta de juguetes.

### 🏢 Contexto organizacional
Juguetes x opera desde una única sede física en EE.UU., que funciona como oficina, tienda y almacén. Su presencia en línea ha crecido, atrayendo clientes nacionales e internacionales, lo que ha generado presión sobre su equipo de TI para mantener operaciones seguras y escalables.

### 🎯 Motivación de la auditoría
La directora de TI identifica la necesidad de realizar una auditoría interna para:
- Proteger la infraestructura tecnológica.
- Identificar y mitigar riesgos, amenazas y vulnerabilidades.
- Garantizar el cumplimiento normativo, especialmente en pagos en línea y operaciones en la Unión Europea (GDPR).

### 🧩 Acciones iniciales
El responsable de TI aplica el **Marco de Ciberseguridad del NIST (CSF)** y realiza:
- Definición del alcance y objetivos de auditoría.
- Inventario de activos tecnológicos.
- Evaluación de riesgos organizativos.

### 📌 Objetivo principal
Proporcionar una visión clara sobre:
- Riesgos actuales que afectan la postura de seguridad.
- Posibles sanciones regulatorias por incumplimiento.
- Recomendaciones para fortalecer la seguridad operativa.

### 🛠️ Aplicación en portafolio
Este caso sirve como base para:
- Simular una auditoría completa usando el NIST CSF.
- Documentar controles administrativos, técnicos y físicos.
- Elaborar un informe técnico con plan de mitigación.
- Practicar la comunicación de resultados a partes interesadas.

> Este ejercicio refleja mi capacidad para aplicar marcos normativos, realizar evaluaciones de riesgo y estructurar auditorías internas como parte de mi formación en ciberseguridad.

## 🧾 **Informe de evaluación de alcance, objetivos y riesgos** 

### 🎯 Alcance y objetivos de la auditoría

**Alcance:**  
La auditoría abarca todo el programa de seguridad de Juguetes x, incluyendo activos tecnológicos, procesos internos y procedimientos relacionados con la implementación de controles y mejores prácticas de cumplimiento.

**Objetivos:**  
- Evaluar los activos existentes gestionados por el departamento de TI.  
- Completar la lista de verificación de controles y cumplimiento.  
- Determinar qué controles deben implementarse para mejorar la postura de seguridad.

---

### 🧩 Activos evaluados

- Equipos locales de oficina.  
- Dispositivos de usuario final: computadoras, teléfonos inteligentes, estaciones remotas, periféricos, cámaras.  
- Productos físicos en escaparate y almacén.  
- Sistemas y servicios: contabilidad, telecomunicaciones, bases de datos, comercio electrónico, inventario.  
- Acceso a Internet y red interna.  
- Retención y almacenamiento de datos.  
- Sistemas heredados en fin de vida útil.

---

### ⚠️ Evaluación de riesgos

**Descripción del riesgo:**  
Gestión inadecuada de activos y ausencia de controles críticos. Posible incumplimiento de regulaciones nacionales e internacionales.

**Recomendación clave (NIST CSF – Función: Identificar):**  
- Clasificar activos y evaluar el impacto de su pérdida.  
- Establecer inventario formal y procesos de administración.

**Puntuación de riesgo:**  
**8/10** – Riesgo alto por falta de controles y cumplimiento.

**Impacto potencial:**  
Medio en continuidad operativa; alto en sanciones regulatorias por exposición de datos sensibles.

---

### 📋 Hallazgos específicos

- ❌ Todos los empleados tienen acceso a PII/SPII ((Información de Identificación Personal y de Personal Sensible)) y datos de tarjetas sin restricciones.  
- ❌ No se utiliza cifrado para proteger datos de tarjetas de crédito.  
- ❌ No se aplican controles de privilegio mínimo ni separación de funciones.  
- ✅ Se garantiza disponibilidad e integridad de datos.  
- ✅ Firewall activo con reglas definidas.  
- ✅ Antivirus instalado y supervisado.  
- ❌ No se ha implementado IDS (Sistema de Detección de Intrusos).  
- ❌ No existen planes de recuperación ni copias de seguridad.  
- ✅ Plan de notificación a clientes de la UE en caso de violación.  
- ✅ Políticas de privacidad documentadas.  
- ❌ Política de contraseñas débil y sin sistema centralizado de gestión.  
- ❌ Sistemas heredados sin cronograma ni métodos claros de mantenimiento.  
- ✅ Seguridad física adecuada: cerraduras, CCTV, detección y prevención de incendios.

---

### 📌 Conclusión

Juguetes x presenta una postura de seguridad parcial, con fortalezas en disponibilidad e integridad, pero con debilidades críticas en confidencialidad, cumplimiento normativo y recuperación ante incidentes. Se recomienda priorizar la implementación de controles técnicos y administrativos, fortalecer la gestión de contraseñas, cifrado, y establecer un plan formal de recuperación de TI.

> Este informe forma parte de mi portafolio académico como evidencia de mi capacidad para aplicar el NIST CSF, realizar evaluaciones de riesgo y documentar auditorías internas en entornos empresariales.

## ✅ Lista de Verificación de Controles y Cumplimiento – Juguetes x

### 🔐 Evaluación de Controles

| ¿Implementado? | Control                                                                 |
|----------------|------------------------------------------------------------------------|
| ❌ No          | Privilegio mínimo                                                       |
| ❌ No          | Planes de recuperación ante desastres                                   |
| ❌ No          | Políticas de contraseñas (no cumplen requisitos mínimos)                |
| ❌ No          | Separación de funciones                                                  |
| ✅ Sí          | Cortafuegos                                                             |
| ❌ No          | Sistema de detección de intrusos (IDS)                                  |
| ❌ No          | Backups                                                                 |
| ✅ Sí          | Software antivirus                                                      |
| ❌ No          | Supervisión y mantenimiento regular de sistemas heredados               |
| ❌ No          | Encriptación para datos sensibles                                       |
| ❌ No          | Sistema de gestión de contraseñas centralizado                          |
| ✅ Sí          | Cerraduras físicas (oficinas, escaparate, almacén)                      |
| ✅ Sí          | Vigilancia CCTV                                                         |
| ✅ Sí          | Detección y prevención de incendios                                     |

---

### 📋 Evaluación de Cumplimiento

#### 🧾 PCI DSS – Estándar de Seguridad de Datos para Tarjetas de Pago

| ¿Cumple? | Mejores prácticas                                                                 |
|----------|------------------------------------------------------------------------------------|
| ❌ No    | Solo los usuarios autorizados tienen acceso a la información de tarjetas           |
| ❌ No    | La información se almacena y procesa en un entorno seguro                          |
| ❌ No    | Se implementan procedimientos de cifrado para proteger datos de transacciones      |
| ❌ No    | Se adoptan políticas seguras de administración de contraseñas                      |

#### 🇪🇺 RGPD – Reglamento General de Protección de Datos

| ¿Cumple? | Mejores prácticas                                                                 |
|----------|------------------------------------------------------------------------------------|
| ✅ Sí    | Los datos de clientes de la UE se mantienen privados y seguros                    |
| ✅ Sí    | Existe un plan de notificación en 72 horas ante violaciones                       |
| ❌ No    | Los datos están correctamente clasificados e inventariados                         |
| ✅ Sí    | Se aplican políticas y procesos de privacidad documentados                         |

#### 🧮 SOC Tipo 1 / Tipo 2 – Controles de Sistemas y Organizaciones

| ¿Cumple? | Mejores prácticas                                                                 |
|----------|------------------------------------------------------------------------------------|
| ❌ No    | Se establecen políticas de acceso de usuarios                                      |
| ❌ No    | Los datos confidenciales (PII/SPII) son privados                                   |
| ✅ Sí    | La integridad de los datos está garantizada                                       |
| ✅ Sí    | Los datos están disponibles para usuarios autorizados                             |

---

### 📌 Observaciones finales

Juguetes x presenta fortalezas en disponibilidad, integridad y seguridad física, pero muestra **deficiencias críticas en confidencialidad, recuperación ante incidentes y cumplimiento normativo**. Se recomienda priorizar la implementación de controles técnicos y administrativos, especialmente en cifrado, gestión de contraseñas, clasificación de datos y planes de recuperación.

> Esta lista forma parte de mi portafolio académico como evidencia de mi capacidad para aplicar el NIST CSF, realizar auditorías internas y evaluar controles y cumplimiento en entornos empresariales.

## 📊 Visualización de Auditoría – Juguetes x

Este dashboard interactivo muestra el estado de cumplimiento por categoría, basado en una auditoría simulada de ciberseguridad aplicada al caso Botium Toys. Utiliza el Marco de Ciberseguridad del NIST (CSF) y refleja mi capacidad para evaluar controles técnicos, administrativos y físicos.

🔗 [Ver dashboard en Tableau Public](https://public.tableau.com/views/EstadodeSeguridadTI-SimulacinJuguetesx/Dashboard1?:language=es-ES&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

Incluye:
- Porcentaje de cumplimiento por categoría
- Evaluación visual de controles implementados
- Mapa de calor de cumplimiento normativo


## 🧠 Sobre mí
- Egreso previsto: diciembre de 2025
- Certificaciones:
  - Fundamentos de Python 1 y 2
  - CCNA: Conmutación, Enrutamiento y Redes Inalámbricas
  - SQL Server: Administración de bases de datos
  - Fundamentos de Ciberseguridad – Google (en curso)

## 🛠️ Habilidades
- Análisis de vulnerabilidades
- Manejo de herramientas SIEM
- Pruebas de penetración (pen testing)
- Gestión de evidencias digitales
- Automatización con Python

## 📁 Proyectos
- Simulación de ataque y respuesta con manual de estrategias
- Detección de intrusiones con Snort y Wireshark
- Visualización de alertas con SIEM (Splunk/Graylog)
- Prueba de penetración en entorno virtualizado

## 📬 Contacto
- LinkedIn: [linkedin.com/in/juan-pablo-tovar-8aa896351](https://linkedin.com/in/juan-pablo-tovar-8aa896351)
- Correo: uimastus@gmail.com
