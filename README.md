# Integrity Group AAL S.A.S. — integrityaal.com

Sitio web en [Astro](https://astro.build) + Tailwind CSS, desplegado en Vercel.

## Desarrollo

```sh
npm install
npm run dev        # http://localhost:4321
npm run build      # genera ./dist
```

## Editar contenido

Todos los textos están en `src/content/`:

- `sitio.json` — datos generales: correo, teléfono, WhatsApp, dirección, redes.
- `home.json` — textos de la página de inicio y servicios.

También se pueden editar desde el panel en `/admin` (Sveltia CMS). Cada cambio crea un commit y Vercel republica el sitio.

## Formulario de contacto

Usa [Web3Forms](https://web3forms.com). Crea la clave con `gerencia@integrityaal.com` y configúrala como `PUBLIC_WEB3FORMS_KEY` en `.env` (local) y en Vercel → Settings → Environment Variables.
