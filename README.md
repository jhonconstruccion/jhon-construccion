# M&M Construcciones en General — sitio web

Sitio corporativo estático desarrollado con Astro para M&M Construcciones en General.

## Incluye

- Página de inicio orientada a cotizaciones.
- Página Nosotros.
- Página general de Servicios y seis páginas individuales.
- Página de Proyectos.
- Página de Contacto con formulario que prepara un mensaje de WhatsApp.
- Diseño responsive para móviles, tablets y escritorio.
- Metadatos SEO básicos y datos estructurados.
- Configuración inicial para Render Static Site (`render.yaml`).

## Datos incorporados

- Nombre: M&M Construcciones en General
- Experiencia: más de 10 años en el rubro
- Cobertura: Región Metropolitana y otras regiones de Chile, según alcance del proyecto
- Teléfono: +56 9 9019 3427
- Correo: mmconstruccion.general@hotmail.com

## Ejecutar localmente

Requisitos: Node.js 20 o superior.

```bash
npm install
npm run dev
```

Abre la dirección local que muestre Astro en la terminal.

## Generar versión de producción

```bash
npm run build
```

Astro genera el sitio final dentro de `dist/`.

## Publicar en Render

Crear un Static Site conectado al repositorio GitHub.

- Build Command: `npm install && npm run build`
- Publish Directory: `dist`

También se incluye `render.yaml` como configuración inicial.

## Antes de publicar

1. Sustituir las fotografías ilustrativas por fotografías reales de trabajos de M&M, con autorización.
2. Revisar que el número y correo de contacto sean correctos.
3. Confirmar comunas y regiones que la empresa efectivamente puede atender.
4. Confirmar el alcance de cada servicio y eliminar cualquier trabajo que no ofrezca.
5. Comprar y configurar el dominio definitivo.
6. Cuando exista el dominio, agregarlo como `site` en `astro.config.mjs` para habilitar URL canónicas y completar sitemap/SEO.
7. Incorporar reseñas reales solo con autorización de los clientes.

## Fotografías

Las fotografías remotas de esta versión son imágenes ilustrativas de Unsplash. No representan trabajos ejecutados por M&M y están identificadas como referencias en el portafolio. Deben reemplazarse por fotografías reales antes de usar el portafolio como prueba de experiencia.

## Formulario

El formulario no almacena datos ni envía correos automáticamente. Prepara un mensaje con los campos completados y abre WhatsApp para que el visitante lo revise y lo envíe. Esto permite probar la captación sin configurar todavía un backend.
