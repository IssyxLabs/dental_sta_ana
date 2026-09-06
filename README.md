# Dental Santa Ana — Sitio web

Sitio web estático para el consultorio **Dental Santa Ana** (Zapopan sur, Guadalajara, Jalisco), dirigido por la Dra. Flor de Liz Bistrain. Odontología general desde 1996, con especialidad en ortodoncia y ortopedia maxilar.

## Estructura del proyecto

```
dental-santa-ana/
├── index.html              # Página principal (inicio, servicios, FAQ, contacto)
├── terminos.html            # Términos y condiciones
├── aviso-privacidad.html    # Aviso de privacidad (LFPDPPP)
├── politicas.html           # Políticas del consultorio
├── borrado-datos.html       # Instrucciones de eliminación de datos (requerido por Meta)
└── assets/
    ├── css/style.css        # Estilos compartidos (variables de color, animaciones)
    ├── js/main.js           # Menú móvil, acordeón de FAQ, header con sombra al hacer scroll
    └── img/                 # Logo y fotografías del consultorio
```

No requiere instalación ni proceso de build: es HTML/CSS/JS plano. Usa [Tailwind CSS](https://tailwindcss.com) y [Font Awesome](https://fontawesome.com) vía CDN, y la fuente Poppins/Nunito Sans de Google Fonts — por lo tanto **necesita conexión a internet** para verse con los estilos correctos.

## Cómo verlo en tu computadora

Simplemente abre `index.html` con doble clic, o desde una terminal:

```bash
python3 -m http.server 8000
```

y entra a `http://localhost:8000` en tu navegador.

## Cómo publicarlo gratis con GitHub Pages

1. Ve a **Settings → Pages** en este repositorio.
2. En "Branch" selecciona `main` y la carpeta `/(root)`.
3. Guarda. En unos minutos el sitio queda disponible en una URL tipo `https://<usuario>.github.io/<repositorio>/`.

## Contenido pendiente por parte del consultorio

- Fotografías reales del consultorio, la Dra. Flor de Liz Bistrain y el equipo (las imágenes actuales en `assets/img/` son de referencia/genéricas).
- Enlaces reales de Instagram y Facebook (actualmente los íconos del header y footer apuntan a `#`).
- Confirmar si desean un correo de contacto específico para solicitudes de privacidad/eliminación de datos (actualmente se usa el WhatsApp del consultorio).

## Datos de contacto del consultorio

- **Dirección:** Guadalupe Victoria 71, Zapopan sur, Guadalajara, Jalisco, C.P. 45230, México
- **WhatsApp / Teléfono:** 33 1089-1206
- **Horario:** Lunes a viernes 10:00–19:00 hrs · Sábados y domingos 9:00–16:00 hrs · Días festivos y vacaciones solo con cita

---

© Dental Santa Ana. Todos los derechos reservados. Sitio desarrollado por **Issyx Labs**.
