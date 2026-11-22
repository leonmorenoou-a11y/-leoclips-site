LEOCLIPS — SITIO OFICIAL ESTÁTICO PARA GITHUB PAGES

IMPORTANTE — ANTES DE PUBLICAR:
1. Reemplaza CONTACT_EMAIL_AQUI en privacy.html y terms.html por un correo real que controles (idealmente uno específico para LeoClips). Son BORRADORES que requieren revisión del responsable del programa; NO los envíes como documentos legales definitivos sin hacerlo.
2. Confirma que las afirmaciones sobre procesos locales y servicios externos siguen reflejando el funcionamiento real del software. Revisa las obligaciones de privacidad y protección de datos que te correspondan.
3. Nunca subas el código fuente privado de LeoClips, App Secrets, tokens, passwords, archivos .env ni contenidos de usuarios a este repositorio público.

CONTENIDO PARA SUBIR (SIN CARPETA INTERMEDIA):
index.html
terms.html
privacy.html
styles.css
.nojekyll
assets/leoclips-icon.webp
assets/favicon.png

PASOS EN GITHUB:
1. En el repositorio público, pulsa Add file > Upload files. Arrastra TODO el contenido de esta carpeta (no la carpeta como contenedor) para que index.html quede en la raíz; si no conserva la estructura assets/, usa Git en tu equipo en su lugar.
2. Commit changes en main.
3. Settings > Pages > Build and deployment > Source: Deploy from a branch > Branch: main > Folder: /(root) > Save.
4. Una vez publicado, GitHub mostrará la URL REAL en Settings > Pages. Comprueba desde una ventana privada /, /terms.html y /privacy.html.
5. En TikTok: URL properties > verificar por URL prefix; usa la URL que GitHub muestre. TikTok entregará un archivo de verificación: súbelo EXACTAMENTE en la ruta solicitada y comprueba que sea público antes de pulsar Verify. GitHub Pages no te da control DNS sobre github.io.
6. En TikTok App details, coloca las URLs REALES de Terms of Service y Privacy Policy y elige Desktop. No pulses Submit for review hasta tener integración y pruebas reales.

NOTAS:
- La web no usa JavaScript externo, trackers, fuentes remotas ni APIs.
- La URL dependerá del nombre exacto del repositorio. En la captura aparece '-leoclips-site', con guion inicial. Puedes corregirlo en Settings > General > Repository name si quieres una URL más limpia.
- Al ser un sitio estático, no sirve como backend OAuth ni como alojamiento privado para subir videos; esos son componentes diferentes.
