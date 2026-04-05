SEMCO - PROPUESTA DE REDISEÑO WEB
Arquitectura de navegación y recomendaciones UX
================================================


BARRA DE NAVEGACIÓN PROPUESTA
------------------------------
Logo SemcoCAD | Licencias | Cursos | Especializaciones | Servicios | Eventos | Blog | Nosotros | [Cotizar →]


ARQUITECTURA DE MENÚS DESPLEGABLES
------------------------------------

1. LICENCIAS
   Autodesk AEC:
   - Revit, Civil 3D, AutoCAD
   - Navisworks, Robot Structural
   - Construction Cloud, Infraworks, Advance Steel
   - Dynamo, 3ds Max

   Autodesk Mecánica:
   - Inventor, Fusion, AutoCAD Plant 3D
   - AutoCAD Electrical, Inventor Nastran, Inventor CAM

   Ansys:
   - CFD, Fluent, Rocky, Mechanical, Discovery

   Oracle:
   - Primavera P6, Unifier, Aconex

   LyraCode:
   - Task-ing, Plan-ing, ADVManager


2. CURSOS
   Diseño general:
   - AutoCAD, 3ds Max, Navisworks, Tinkercad

   BIM AEC:
   - Revit, Civil 3D, Advance Steel
   - Dynamo, Twinmotion, ISO 19650
   - Construction Cloud, Robot Structural

   Mecánica:
   - Inventor, Fusion, Inventor CAM
   - AutoCAD Electrical, AutoCAD Plant 3D

   Simulación:
   - Dinámica de Fluidos CFD, Ansys Rocky

   Gestión:
   - Oracle Primavera P6
   - Corporativo (in-house)


3. ESPECIALIZACIONES
   Programas certificados:
   - BIM en Edificaciones
   - BIM en Plantas Industriales
   - BIM en Infraestructura
   - PIM – Prototipos Digitales

   Formatos disponibles:
   - Presencial, Online, Híbrido

   CTAs internos:
   - Ver cronograma completo
   - Capacitación corporativa


4. SERVICIOS
   CAD / BIM / CAE:
   - Catálogos 3D
   - Automatización CAD
   - Simulación CAE
   - IoT / Forge

   Software propio:
   - LyraCode (Task-ing, Plan-ing)
   - ADVManager (agencias de publicidad)

   Soporte:
   - Soporte post-venta


ESTRUCTURA DE URLs RECOMENDADA
--------------------------------
/licencias/autodesk/revit          → Página individual por software (precio, características, CTA cotización)
/licencias/autodesk/civil-3d       → Idem por producto
/licencias/ansys/cfd               → Idem Ansys
/licencias/oracle/primavera        → Idem Oracle
/licencias/lyracode/task-ing       → Idem LyraCode

/cursos/bim-aec/revit              → Ficha de curso (temario, modalidad, duración, inscripción)
/cursos/mecanica/inventor          → Idem por categoría
/cursos/simulacion/ansys-rocky     → Idem simulación
/cursos/gestion/oracle-primavera   → Idem gestión
/cursos/corporativo                → Capacitación in-house

/especializacion/bim-edificaciones → Landing con programa, docentes, certificación, admisión
/especializacion/bim-infraestructura
/especializacion/bim-plantas-industriales
/especializacion/pim-prototipos-digitales

/eventos                           → Listado con filtro presencial/webinar, fechas y formulario
/blog                              → Artículos SEO, tutoriales, novedades Autodesk/Ansys
/contacto                          → Formulario unificado (selector producto/servicio/curso)
/nosotros                          → Historia, equipo, certificaciones


ANÁLISIS: QUÉ CONSERVAR, MEJORAR, AGREGAR Y QUITAR
----------------------------------------------------

✓ CONSERVAR del sitio actual (semco.com.pe):
- Separación clara entre Licencias y Formación
- Sub-categorías AEC vs Mecánica bien diferenciadas
- Página de Nosotros con historia de la empresa
- Sección de Eventos dedicada

▲ MEJORAR del sitio actual:
- Mega-menú excesivamente largo (más de 20 ítems visibles)
- Nombre "Formación" confuso → renombrar a "Cursos"
- CTA de cotización enterrada dentro del menú → llevar a navbar
- Licencias y cursos mezclados en el mismo dropdown

+ ADOPTAR de la propuesta (semco.pages.dev):
- Blog como sección propia visible en la nav principal
- URLs limpias por jerarquía /licencias/marca/producto
- Especializaciones separadas de los cursos sueltos
- Botón "Cotizar" en navbar como CTA destacado (color naranja)

✗ QUITAR / SIMPLIFICAR:
- Sub-menú "Compra online" en el nav principal (moverlo a cada ficha de producto)
- Duplicados: AutoCAD aparece en AEC y en Mecánica → unificar
- Sección "Software" genérica dentro de Servicios (confusa)
- Links a páginas en construcción (#) → quitar hasta que estén listos


DECISIONES CLAVE DE DISEÑO
----------------------------

1. COTIZAR como único CTA en naranja en la navbar
   Actualmente está escondido. Si alguien llega interesado en una licencia,
   el camino a la cotización debe ser inmediato, sin scroll ni clics extra.

2. BLOG visible en la navegación principal
   Las búsquedas en Google de profesionales CAD/BIM en Perú son constantes
   (tutoriales de Revit, novedades Autodesk, etc.). Un blog bien posicionado
   captura tráfico orgánico gratuito. Categorías recomendadas: BIM, Mecánica,
   Simulación, Gestión de proyectos, Novedades software.

3. SEPARAR Cursos de Especializaciones en el nav
   Una especialización (varios meses, certificación) tiene un valor y proceso
   de decisión muy distinto a un curso suelto (días). Mezclarlos confunde al
   usuario y reduce la percepción de valor de los programas certificados.

4. URLs LIMPIAS por jerarquía
   La estructura /licencias/autodesk/revit permite que Google entienda
   la taxonomía del sitio y que el usuario sepa siempre dónde está.
   El sitio actual con slugs directos (/revit/, /civil-3d/) pierde ese contexto.

5. MEGA-MENÚ con grupos visuales claros
   Actualmente AutoCAD aparece dos veces (AEC y Mecánica). El usuario no necesita
   duplicados, necesita encontrar su área de trabajo rápidamente.


================================================
Análisis basado en scraping de:
- https://www.semco.com.pe (sitio actual)
- https://semco.pages.dev (propuesta en desarrollo)
================================================