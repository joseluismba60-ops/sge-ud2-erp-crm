# Comparativa ERP y CRM

## 1. Datos
* **Usuario de GitHub:** joseluismba60-ops
* **Empresa:** Caso 20 - Imprenta Digital "Impresiones Rapidas"
* **Palabra del dia:** Compañeros

## 2. Licencias y modelos
Software Propietario (Control total): pagas por usar el programa, pero el codigo es un secreto industrial bajo llave. Si el programa hace algo que no te gusta, o quieres adaptarlo a tus necesidades, es ilegal intentarlo. Eres un consumidor pasivo y dependiente al 100% del fabricante (ej. Windows, Photoshop).

Software Libre - FSF (El argumento ético): nace de la idea de ocultar una receta es una forma de someter al usuario. Defiende que, por una cuestion de derechos digitales, debes poder leer como esta hecho el programa, modificarlo para el uso personal y compartirlo libremente. Para la FSF, no se trata de hacer mejores programas, sino de construir una sociedad tecnologica mas justa.

Codigo Abierto - OSI (El argumento practico): permite exactamente lo mismo que el software libre (ver, modificar y compartir), pero su motivacion es empresarial. Su premisa es simple: si se encierra a diez programadores en una oficina, tendran buenas ideas; pero si publicas tu codigo en internet y descubriran los errores mas rapido y la innovacion sera imparable. Es pragmatismo puro.

¿Por que la libertad no elimina el dinero?
El gran malentendido surge porque en inglés free significa tanto "libre" como "gratis". Pero tener libertad sobre una herramienta no implica que el trabajo humano que la rodea pierda valor.

Piensa en los planos de una casa. Es posible que el diseño estructural (el código) sea de dominio público y puedas descargarlo libremente. Sin embargo, si quieres construir esa casa, vas a contratar a un arquitecto para que adapte los planos a tu terreno, y a obreros para que la construyan. En el software libre ocurre igual: no pagas un "peaje" abusivo (licencia de uso) solo por tener el derecho a abrir el programa, pero pagas por el servicio humano. Contratas a programadores para que instalen el sistema, lo personalicen a medida para tu empresa o te den formación técnica. El negocio pasa de ser un monopolio de licencias a ser un mercado de servicios profesionales.

Community vs Enterprise: El negocio del riesgo

Si cualquiera puede descargar el código fuente sin pagar, empresas como Red Hat generan miles de millones separando a los usuarios según el nivel de riesgo que están dispuestos a asumir.
Ediciones Community: Son el campo de pruebas. Obtienes el software gratis y con las funciones más novedosas, pero eres tu propio mecánico. Si tu servidor falla un viernes por la tarde, tu única línea de soporte es buscar en foros de internet y esperar que alguien te ayude gratis. Pagas con tu tiempo y asumes el riesgo.
Ediciones Enterprise: Es un seguro a todo riesgo corporativo. Los bancos, hospitales o ministerios no pueden depender de foros si su base de datos colapsa. No pagan por el código, pagan por tranquilidad. Compran una suscripción que les garantiza una versión del software mucho más estable, parches de seguridad prioritarios, indemnidad legal por si hay problemas de patentes, y un contrato que obliga a un equipo de ingenieros a responder al teléfono 24/7 si algo sale mal.

## 3. Fichas tecnicas ERP y CRM
Fecha de consulta: 29 de septiembre

3.1. ERP Libre: Odoo Community
Licencia exacta: GNU LGPL v3. [Fuente: https://github.com/odoo/odoo/blob/master/LICENSE]

Versión vigente: Odoo 19. [Fuente:https://www.odoo.com/es_ES/page/release-notes]

Lenguaje del servidor: Python y JavaScript. [Fuente: https://github.com/odoo/odoo ]

SGBD compatibles: PostgreSQL. [Fuente: https://www.odoo.com/documentation/master/administration/on_premise.html]

Modalidad: Instalación local y Nube. [Fuente: https://www.odoo.com/es_ES/page/editions]

Módulos principales: Ventas, Inventario, Fabricación, CRM, Sitio Web. [Fuente: https://apps.odoo.com/apps]

Requisitos (servidor): Linux, Python 3.10+, PostgreSQL 13+. [Fuente: https://www.odoo.com/documentation/master/administration/on_premise.html]

3.2. ERP Propietario: Microsoft Dynamics 365
Licencia exacta: Propietario (Suscripción comercial). [Fuente: https://www.microsoft.com/es-es/dynamics-365/pricing-overview]

Versión vigente: Release Wave 2 de 2026. [Fuente: https://learn.microsoft.com/en-us/dynamics365/release-plan/2025wave2/]

Lenguaje del servidor: AL y C#. [Fuente: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/devenv-dev-overview]

SGBD compatibles: Microsoft SQL Server y Azure SQL. [Fuente: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/deployment/system-]

Modalidad: Nube (Azure) e híbrida. [Fuente: https://www.microsoft.com/es-es/dynamics-365/products/business-central]

Módulos principales: Finanzas, Cadena de suministro, Ventas. [Fuente: https://www.microsoft.com/es-es/dynamics-365]

Requisitos: Navegador web moderno o ecosistema Windows Server para local. [Fuente: https://www.google.com/search?q=https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/deployment/system-requirements]

3.3. CRM Libre: SuiteCRM
Licencia exacta: GNU AGPL v3. [Fuente: https://www.google.com/search?q=https://github.com/salesagility/SuiteCRM/blob/master/LICENSE.txt]

Versión vigente: SuiteCRM 8.x. [Fuente: https://docs.suitecrm.com/8.x/admin/releases/]

Lenguaje del servidor: PHP. [Fuente: https://www.google.com/search?q=https://docs.suitecrm.com/8.x/admin/installation-guide/system-requirements/]

SGBD compatibles: MySQL, MariaDB y SQL Server. [Fuente: https://docs.suitecrm.com/8.x/admin/installation-guide/system-requirements/]

Modalidad: Local y Nube. [Fuente: https://suitecrm.com/]

Módulos principales: Cuentas, Contactos, Oportunidades, Campañas. [Fuente: https://suitecrm.com/what-is-suitecrm/]

Requisitos: Servidor web, PHP 8.x, Base de datos compatible. [Fuente: https://docs.suitecrm.com/8.x/admin/installation-guide/system-requirements/]

3.4. CRM Propietario: Salesforce
Licencia exacta: Propietario (SaaS). [Fuente: https://www.salesforce.com/sales/pricing/]

Versión vigente: Winter '27. [Fuente: https://help.salesforce.com/s/articleView?id=release-notes.salesforce_release_notes.htm&release=264&type=5]

Lenguaje del servidor: Apex. [Fuente: https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_intro_what_is_apex.htm]

SGBD compatibles: Arquitectura multitenant propietaria basada en Oracle. [Fuente: https://architect.salesforce.com/fundamentals/architecture-landscape]

Modalidad: Exclusivamente Nube. [Fuente: https://www.salesforce.com/es/]

Módulos principales: Sales Cloud, Service Cloud, Marketing Cloud. [Fuente: https://www.salesforce.com/es/products/]

Requisitos: Ninguno (100% Cloud). [Fuente: https://help.salesforce.com/s/articleView?id=xcloud.getstart_browsers_sfx.htm&type=5]

## 4. Fe de erratas del tema 2

##1. El desarrollador real de SuiteCRM##
* **Que dice el tema:** El documento afirma en su comparativa de soluciones que SuiteCRM esta "Desarrollado por la comunidad SugarCRM"[cite: 1].
* **A dia de hoy lo correcto es:** Esta informacion es inexacta. SuiteCRM fue creado y es mantenido oficialmente por la empresa **SalesAgility**. El proyecto surgio como un *fork* (bifurcacion) independiente porque la empresa SugarCRM decidio abandonar el modelo de codigo abierto y cerrar su edicion comunitaria en 2014.
* **Fuente:** https://suitecrm.com/about-us/

**2. La popularidad de Fat Free CRM en GitHub**
* **Que dice el tema:** El PDF asegura que Fat Free CRM es el "CRM mas valorado en GitHub por su comunidad activa"[Cite: 1].
* **A dia de hoy lo correcto es:** Este dato es desactualizado. Fat Free CRM es hoy en dia un proyecto con una comunidad muy reducida (ronda las 3.500 estrellas). Soluciones de codigo abierto que incluyen CRM, como Odoo, superan las 36.000 estrellas, y ERPNext supera las 18.00, teniendo comunidades de desarrollo infinitamente mas activas.
* **Fuente:** https://github.com/fatfreecrm/fat_free_crm