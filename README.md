# Ven a Clases en la FEN

Plataforma de agendamiento para el programa "Ven a Clases" de la Facultad de Economía y Negocios, Universidad de Chile.

## Desarrollo local

```bash
npm install
npm run dev
```

## Publicar en Vercel

1. Sube este proyecto completo a un repositorio en GitHub
2. Ve a vercel.com, conecta tu cuenta de GitHub
3. Importa el repositorio
4. Vercel detectará Vite automáticamente — haz clic en "Deploy"

## Configuración

Edita `src/App.jsx`:

- **SEMANA_INICIO**: Fecha del primer lunes del período
- **NUM_SEMANAS**: Cantidad de semanas del período
- **DIAS_CORTE**: Días de anticipación para cerrar inscripciones
- **ADMIN_PASS**: Contraseña del panel admin (acceso via URL#admin)
- **APPS_SCRIPT_URL**: URL del Google Apps Script para guardar datos y enviar correos

## Admin

Acceder a: `tusitio.com/#admin`
