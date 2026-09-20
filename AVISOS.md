# Avisos y créditos

**Pipe-Políglota** (Pi-Po) es © 2026 pipataki. Todos los derechos reservados:
se reparte la aplicación, no el código fuente.

## Lo que lleva dentro

| Componente | Autor | Para qué se usa |
|---|---|---|
| Vosk (vosk-android 0.3.47) | Alpha Cephei Inc. | oír la orden del idioma, en el móvil y sin conexión |
| Modelo de voz `vosk-model-small-es-0.42` | AC Technologies LLC | el vocabulario español de esa orden |
| ML Kit Translation 17.0.3 | Google LLC | traducir en el propio móvil |
| JNA 5.13.0 | Java Native Access project (doble licencia; se usa bajo Apache 2.0) | puente de Vosk con su parte nativa |

Todos ellos se usan bajo licencia **Apache 2.0** (ver `APACHE-2.0.txt`).

La frase que se traduce la transcribe el **reconocedor de voz del propio
móvil** (en el teléfono de pruebas, *Servicios de voz de Google*), y quien la
lee en voz alta es el **motor de voz del móvil**. Ninguno de los dos va dentro
de la aplicación.

## Lo que sale del teléfono, y cuándo

- **Nada, en el uso normal.** Se oye, se traduce y se habla en el propio móvil.
- **Los idiomas se descargan una vez**, con conexión, la primera vez que se usa
  cada uno (unos 30 MB). Después funcionan sin ella.
- **Una palabra suelta, si tú lo pides.** Cuando el traductor falla con un
  término y pulsas el botón de buscarlo, se consulta **Wikipedia** (su API de
  enlaces entre idiomas, sin clave ni cuenta) enviando **solo esa palabra** —
  nunca la frase ni la conversación—. Lo que se aprende se guarda, así que cada
  palabra se pregunta una sola vez.

El diccionario que vas construyendo se guarda **en la carpeta privada de la
app**, en tu móvil, y no se envía a ningún sitio.
