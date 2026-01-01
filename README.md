# Planos.hotel-RESILIENCIA.2
RESILIENCIA - Visor Técnico de Proyecto (Resort Inmersivo Sensorial)

📋 Descripción

RESILIENCIA es una aplicación web de archivo único (Single File Application) diseñada para visualizar, presentar y gestionar el paquete técnico de planos arquitectónicos para el proyecto "Resort Inmersivo Sensorial".

Esta herramienta sustituye la entrega tradicional de planos estáticos, ofreciendo un entorno interactivo donde clientes, ingenieros y contratistas pueden explorar el Masterplan, activar/desactivar capas de instalaciones (MEP), consultar detalles constructivos y generar documentación vectorial bajo demanda.

✨ Características Principales

🗺️ Masterplan Interactivo: Visualización vectorial (SVG) del conjunto con control de capas en tiempo real.

Capas disponibles: Arquitectura, Red Eléctrica, Paisajismo, Rutas de Evacuación.

📑 Navegación Estructurada: Acceso rápido a diferentes disciplinas:

Masterplan & Site.

Módulos Habitacionales (Unidades Tipo).

Detalles Constructivos (Cimentación y Secciones).

Esquemas MEP (Eléctrico e Hidráulico).

Memorias y Listas de Cantidades (BOQ).

🖨️ Salida Profesional: Estilos CSS optimizados para impresión en formato PDF A1, ocultando interfaces de usuario y ajustando escalas.

⬇️ Exportación Vectorial: Función para descargar la vista actual como archivo .svg editable (compatible con AutoCAD, Illustrator, Inkscape).

✏️ Datos Editables: El cajetín del plano permite la edición de texto en vivo (Coordenadas, Fechas, Revisiones) directamente desde el navegador.

🚀 Inicio Rápido

No se requiere instalación de servidores, Node.js ni bases de datos. El proyecto es completamente autónomo.

Requisitos

Cualquier navegador web moderno (Chrome, Firefox, Edge, Safari).

Conexión a internet (únicamente para cargar Tailwind CSS y Lucide Icons vía CDN).

Ejecución

Clona este repositorio o descarga el archivo .zip.

Ubica el archivo resiliencia_project_viewer.html.

Haz doble clic para abrirlo en tu navegador.

🛠️ Tecnologías Utilizadas

HTML5 / SVG: Estructura semántica y gráficos vectoriales inline.

Tailwind CSS (v3): Estilizado rápido y responsivo mediante CDN.

Lucide Icons: Iconografía ligera y nítida.

Vanilla JavaScript: Lógica de interacción (cambio de pestañas, capas, descargas) sin frameworks pesados.

📂 Estructura del Código

El proyecto reside en un único fichero HTML para facilitar su portabilidad. Dentro del código encontrarás:

<header>: Controles globales (Impresión, Descarga).

<aside>: Navegación lateral y checkboxes de control de capas.

<main>:

#view-masterplan: Contenedor principal SVG con capas agrupadas (<g>).

#view-units: Tarjetas con planos de unidades tipo.

#view-details: Detalles constructivos SVG (Cimentación, Muros).

#view-mep: Esquemas unifilares y diagramas de flujo.

#view-specs: Documentación textual (Memorias).

📝 Uso y Personalización

Editar Información del Proyecto

En la esquina inferior derecha del visor, encontrarás un cajetín flotante. Haz clic sobre los textos con línea punteada (como coordenadas o fechas) para editarlos antes de imprimir.

Imprimir a PDF

Presiona el botón "Imprimir Todo (PDF)" o usa Ctrl + P. El sistema generará un documento limpio, sin barras laterales ni botones, listo para ser visado.

Descargar Planos Editables

Navega a la vista que desees (ej. Detalles Constructivos) y presiona "Descargar Plano Actual (.SVG)". Obtendrás un archivo vectorial que puedes importar en tu software CAD preferido.

Autor: IA Architecture

Licencia: Proyecto conceptual para uso educativo/profesional.
