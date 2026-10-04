# EkoPat.cl - Reciclaje de Aceite y Futuro Sostenible

Sitio web oficial de EkoPat. Landing page estatica, rapida y optimizada para GitHub Pages + Cloudflare.

**Dominio:** ekopat.cl
**Web:** https://ekopat.cl
**Contacto:** reciclajeekopat@gmail.com / +56 9 7796 9866 (WhatsApp)

### Que hace EkoPat?
Recoleccion, tratamiento y transformacion de aceite vegetal usado en biocombustible y economia circular en Chile. Trabajamos con restaurantes, industrias y comunidades.

### Stack
- HTML5 / CSS3 / JS Vanilla
- Sin frameworks
- Hosting: GitHub Pages
- DNS / CDN: Cloudflare
- Contacto directo a WhatsApp

### Estructura
/
├── index.html   -> Sitio completo single-page
└── README.md

Secciones:
#inicio - Portada
#nosotros - Mision
#proceso - Ciclo de 4 pasos
#impacto - Estadisticas
#contacto - Formulario que abre WhatsApp

### Deploy
1. Subir index.html al repo
2. GitHub > Settings > Pages > Branch: main / root
3. Custom domain: ekopat.cl
4. Cloudflare DNS:
   A @ 185.199.108.153 - DNS Only (gris)
   A @ 185.199.109.153 - DNS Only
   A @ 185.199.110.153 - DNS Only
   A @ 185.199.111.153 - DNS Only
   CNAME www TUUSUARIO.github.io - DNS Only
5. Esperar verificacion y activar HTTPS en GitHub Pages

### Como funciona el contacto?
El formulario no usa backend. Al enviar, abre WhatsApp directo al +56 9 7796 9866 con el mensaje pre-escrito. Usa wa.me


© 2026 EkoPat. Avanzando con la naturaleza.
