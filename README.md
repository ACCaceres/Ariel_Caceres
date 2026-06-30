# Analista de Datos

#### Skills Técnicos: Python, SQL,  Linux, Power Bi, Excel, Looker BigQuery, VBA, JS, Jupyter

## Educación

+ **Ingeniero en Administración de Empresas**, _Universidad de los Lagos (Titulado en 2011)._							       		
+ **Contador Auditor**,  _Universidad Andrés Bello (Finaliza 2026)._ 			        		
+ **Diplomado Data Analyst**, _Universidad del Desarrollo (Finalizado Febrero 2024)._
+ **Diplomado en Gesión Tributaria**,  _Thomson Reuters (Julio a Noviembre 2021)._

## Experiencia Laboral
### **Ejecutivo de Área Digital @ Coopeuch (_Mayo 2025_ - _Presente_)**
- Responsable de la gestión comercial y evaluación de operaciones en los canales digitales de la institución, asegurando la eficiencia del proceso y el cumplimiento de las políticas internas.
- Evaluación de Riesgo Financiero: Análisis de perfiles de clientes y transacciones para la originación de productos, mitigando riesgos operativos y crediticios.
- Gestión Operativa y Atención: Administración integral del ciclo de vida del cliente digital, asegurando la correcta ejecución de los procesos y una experiencia de usuario fluida bajo normativas vigentes.

#### Proyectos Destacados
**_Motor de Automatización de Mailing Corporativo_**
**Stack Tecnológico:** 

* **Backend:** Microsoft Excel, VBA (Uso estricto de funciones nativas de manipulación de memoria y strings) OS.VBA (Excel/Word/Outlook), OLEDB/SQL, Windows API (kernel32)
* **Entorno:** Microsoft Edge (Chromium), Windows.

**Contexto:**
Operación dentro de un ecosistema corporativo cerrado, con alto nivel seguridad informática.

**Desafío:**
Automatizar el envío masivo de resoluciones comerciales personalizadas, cuidando los niveles seguridad del sistema operativo (alertas de inyección SQL) y la inestabilidad de memoria RAM en el procesamiento por lotes masivos.

 **Solución Técnica:**
* **Orquestación Centralizada:** Desarrollo de un motor controlador en Excel para gestionar la base de datos de clientes, coordinar plantillas dinámicas y auditar los envíos en tiempo real.
* **Inyección SQL Dinámica:** Implementación de conexión de datos en caliente (`OpenDataSource`) para evadir las alertas de seguridad restrictivas de correspondencia, manteniendo la integridad del proceso sin violar los niveles de administrador.
* **Control de Procesos a Nivel de Sistema:** Integración de la API de Windows (`Sleep` vía *kernel32*) para inyectar pausas dinámicas, garantizando una gestión eficiente del portapapeles y previniendo la saturación de memoria de Outlook durante la compilación de formatos enriquecidos.
* **Trazabilidad:** Asignación automatizada de categorías nativas en Outlook para el control, clasificación y seguimiento visual inmediato de las bandejas de salida.

 **Impacto:**
Eliminación del trabajo manual en el procesamiento de lotes de alto volumen. Mitigación del 100% de errores operativos por cruce de datos confidenciales y reducción del tiempo de ejecución a milisegundos por registro, optimizando drásticamente la productividad comercial.


**_Sistema Híbrido RPA (JS + VBA) para Entornos Corporativos._**

Este proyecto demuestra una arquitectura de automatización de procesos robóticos (RPA) diseñada para entornos *Air-gapped* o corporativos .

**Problema de Negocio**
Extraer perfiles de clientes diarios desde un CRM web interno hacia una planilla local de Excel para cálculos de riesgo, requiriendo procesamiento manual tedioso y propenso a errores.

**Arquitectura de Solución**
Se diseñó un modelo híbrido de **"Puente de Datos Asíncrono"** utilizando la carpeta de descargas del sistema operativo como zona neutral:

1. **JavaScript Bookmarklet (El Interceptor):** Un script inyectado en el navegador vía marcadores que intercepta las respuestas de red (`fetch` y `XHR`) del CRM en segundo plano, extrae el ID del cliente y descarga silenciosamente el payload estructurado (JSON).
2. **VBA Listener (El Motor Back-end):** Una macro de Excel operando en bucle pasivo que detecta los nuevos archivos JSON, extrae nodos específicos mediante parseo de cadenas nativo (sin dependencias XML), limpia datos científicos/flotantes, inyecta los enteros en la base de datos y destruye el archivo temporal.

**Stack Tecnológico**
* **Frontend:** JavaScript Vanilla (ES6+), Interceptación de API REST.
* **Backend:** Microsoft Excel, VBA (Uso estricto de funciones nativas de manipulación de memoria y strings).
* **Entorno:** Microsoft Edge (Chromium), Windows OS.

**Impacto**
* Reducción del tiempo de procesamiento manual en un **85%**.
* Eliminación total de errores de transcripción en saldos financieros.
* Cero instalación de software de terceros requerida.


### **Control Interno @ Patagonia Club SpA (_Octubre 2023_ - _Abril 2025_)**
- Generar reportes BI, Analizar Data Histórica y actual Ventas (Looker Studio Overview).
- Control de Activos, adquisiciones, Fondos a Rendir, Fondos Fijos.
- Implementación de Políticas de control interno e implementar acciones para este fin.
- Analizar ventas a clientes, históricas y actuales e implementación de políticas para calidad de ventas.
- Seguimiento y control de stock de instrumento valorizados.
- Control del área cobranza, fondos transferencias depósitos efectivo, control de valores.
- Elaboración de reportes e indicadores para la Gerencia.
- Cierre comisiónal cálculo de remuneraciones, reestructuración de compensaciones.
- Seguimiento y elaboración trimestral de Flujo de caja.
- Analizar, medir, corregir y evaluar acciones del departamento de telemarketing.
Logros: Reducción de 17% costos operativos.
 Reducir tiempo de asignación de recursos en un 77%.
 Implementación de políticas de control, rendición de gastos y fondos fijo.
 Reducción en un 60% la demora de tiempos de respuesta de posventa y devoluciones.

#### Proyectos Destacados
**_Automatización de Procesos de Facturación (iGlobal ERP)_**

Diseñé e implementé un script en Python que automatizó la emisión de más de 250 documentos electrónicos en iGlobal ERP, un sistema sin API de integración. Incorporé características como personalización de rutas de guardado, manejo de errores, y monitoreo en tiempo real para detener el proceso según la necesidad del usuario. Resultado: Reducción de 21 horas de trabajo manual a solo 1 hora de ejecución automatizada.

•	Herramientas pyautogui, Pandas, IGlobal ERP

**_Automatización y Extracción de Datos_**

Desarrollé un script en Python para automatizar la extracción y estructuración de datos desde un sistema web Interno basado en tablas HTML, la problematica es el termino de asistencia, blouqeo a la bases de datos. Implementé técnicas avanzadas de web scraping utilizando BeautifulSoup, logrando identificar y manejar estructuras dinámicas de datos en diferentes formatos. Extraer información clave como datos personales, número de contratos, tipos de planes y detalles adicionales, normalizando los datos para análisis. Generar informes en formato CSV, optimizando el manejo de grandes volúmenes de fichas. Diseñar una solución robusta para manejar excepciones como clientes sin contratos y etiquetas variables. Sobre los datos extraídos se presentó información relevante para la gerencia para la toma de decisiones de cara a las acciones comerciales 2025.

•	Herramientas utilizadas Jupyter, Pandas, BeatifulSoup, Técnicas de Webscraping.

#### Otros Proyectos
**_Testeo y Evaluacion CRM Odoo_**

Implementación instalación testeo y prueba en VPS de Google GCP de Odoo 17 versión Community (Open Source) la evaluación buscaba una reducción de Costos en comparación con Hubspot esta solución reduce costos en un 90% anuales. (También se testeo como alternativas en la misma instancia VPS)


### **Analista Comercial	@ CLM DIGITAL SOLUTIONS (_junio 2023 – octubre 2023_)**
- Revisar el portal de Mercado Público para detectar nuevas licitaciones que sean de importancia para CLM.
- Preparar y gestionar con otras áreas de CLM, la documentación administrativa, legal, comercial y técnica para participar en licitaciones, boletas de garantías, facturación y órdenes de compras.
- Ejecutar compras de productos, entrega en portal partner a cliente final
- Analizar ventas a clientes, históricas y actuales, contrastar ofertas, seguimiento del mercado y competencia.
- Elaboración de reportes e indicadores para la Gerencia.
Logros: Incrementar en 78% la participación en mercado público.
 Posicionar vía análisis cambio de estrategia y apertura a mercado a privado
 Determinar costos y márgenes adecuados de acuerdo a mercado.
 Analizar potencial del mercado Español en compras públicas.
 Aumentar en 27% la cantidad de Partner tecnológicos y proveedores de servicio.
 Obtener partner Uplevel para distribución de servicios Adobe para CLM

