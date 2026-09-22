# Documentos legales de Comer sin sustos

Política de privacidad de la aplicación **Comer sin sustos**, un escáner de alergias
alimentarias e información nutricional para Android.

Este repositorio existe solo para servir esos documentos por HTTPS con una URL
pública y estable, que es requisito de Google Play y del mensaje de
consentimiento de AdMob. **No contiene el código de la aplicación.**

| Documento | |
|---|---|
| Política de privacidad (español) | [privacidad-es.html](privacidad-es.html) |
| Privacy Policy (English) | [privacy-en.html](privacy-en.html) |

Se publica con GitHub Pages desde la rama `main`. El historial de commits sirve
además como registro de qué decía la política en cada momento, que en un
documento legal no es un detalle menor.

La URL base se pasa a la app al compilar, con
`--dart-define=PRIVACY_URL=https://.../nutricional-legal`, y la app elige el
documento por idioma: `privacidad-es.html` en español y `privacy-en.html` en
cualquier otro.

---

Comer sin sustos · JR Soft, nombre comercial de Javier Román Sáez ·
`com.jrsoft.nutricional`

Los datos de producto proceden de
[Open Food Facts](https://world.openfoodfacts.org), con licencia
[ODbL](https://opendatacommons.org/licenses/odbl/). Esta aplicación no está
afiliada a Open Food Facts.
