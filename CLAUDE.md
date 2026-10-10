# Reglas de trabajo — Web de FEBRA (febra.com.ar)

## Quién y cómo
- Dueña del proyecto: Laura (FuzioHub). Cliente: FEBRA Implementos Agrícolas, San Francisco, Córdoba.
- Responder SIEMPRE en español, simple y paso a paso (dónde ir, qué tocar, qué pegar). Laura no es programadora.
- Si algo no se sabe, preguntarle a Laura. No inventar datos (ni técnicos de las máquinas, ni del negocio).
- Nunca pedir ni copiar contraseñas, claves o tokens (Vercel, GitHub, Formspree, Google).

## Flujo de trabajo
1. Claude hace los cambios en este repositorio (lautaglioli-ctrl/febra-web, rama main) y los sube a GitHub.
2. Antigravity publica: en la carpeta "Febra Web" se le pide "Hacé git pull de main y después publicá en producción con vercel --prod".
3. Subir a GitHub NO publica solo. Recordarle a Laura que publique y verificar en febra.com.ar.

## Qué es el sitio
- Página única estática: `index.html` (estilos y código adentro), `politica-de-privacidad.html`, `assets/`, `fichas/` (PDF de fichas técnicas), `sitemap.xml`, `robots.txt`.
- Los datos de cada máquina están en `productosTechData` dentro de `index.html`. Si se cambia una tabla, regenerar también el PDF de esa máquina en `fichas/`.
- Fotos nuevas: en JPG, máximo ~1400 px de lado. Nada de PNG pesados.

## No tocar sin que Laura lo pida
- Formulario: lo envía Formspree (endpoint ya configurado en `handleFormSubmit`). Manda un mail por cada consulta. No cambiarlo.
- Teléfonos: +54 9 3564 233529 (principal) y +54 9 3564 506516.
- Google Analytics G-LHXEQ9L5MD y sus eventos: click_whatsapp, ver_ficha, descarga_ficha, generate_lead.
- Archivo de verificación de Google (`google668beb439c0b04c8.html`).
- Crédito "Diseño y Desarrollo: Fuzio Hub" en el pie.

## Importante: todo lo que está acá se publica
- Cualquier archivo del repositorio queda visible en febra.com.ar (salvo lo que está en `.vercelignore`).
- NO subir datos del negocio (precios, cobros, notas internas, archivos .md de gestión) ni archivos de prueba o capturas.

## Al terminar algo importante
Cerrar la respuesta con el bloque para el Central:

PARA EL CENTRAL – FEBRA (web) – (fecha)
- Qué se hizo:
- Plata (entró / salió / pendiente):
- Mails o mensajes a clientes:
- Pendiente:
