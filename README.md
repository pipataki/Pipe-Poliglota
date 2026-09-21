# Pipe-Políglota

**Habla en español y el móvil lo dice en otro idioma.** Para viajar, para
entenderse con alguien que no habla tu lengua, y pensado —como el resto de
estas aplicaciones— para que se pueda usar sin manos.

- **Di el idioma y luego la frase.** «Inglés», «francés», «alemán», «griego»,
  «chino»… y a continuación lo que quieras decir. Nada de menús.
- **Se traduce en el propio móvil**, sin conexión: cada idioma se descarga una
  vez (unos 30 MB) y después funciona en modo avión.
- **Lo dice en voz alta** con la voz del idioma de destino.
- **Comprueba lo que va a decir.** Antes de hablar, traduce la frase **de
  vuelta** y mira qué se ha perdido por el camino. Si algo baila, lo avisa —y a
  menudo lo arregla solo.
- **Aprende de sus fallos.** Cuando un término se le atraganta («misa» en
  francés, «la Gran Muralla China» en chino) propone la corrección, la prueba
  en la frase entera y, si encaja, se la queda. Si ni el traductor lo sabe,
  puede preguntárselo a Wikipedia. Y lo aprendido se aplica solo cuando mejora
  la frase: una corrección no vale en todo contexto.
- **Pone los signos de puntuación.** Las comas y los puntos salen de tus
  pausas; los que dependen del significado —dos puntos, comillas, paréntesis—
  se dicen en voz alta, porque quien sabe dónde van es quien habla. Reconoce
  las citas: «él escribió» y lo que sigue sale entrecomillado. Y distingue una
  pregunta de una afirmación, que también cambia la traducción.
- **Los idiomas descargados, a la vista.** Se elige uno tocándolo, sin tener
  que decirlo; se borra del móvil con una ✕; y hay un tope para que no se llene
  el teléfono. Lo que le hayas enseñado **se conserva** aunque borres el idioma.

> **Versión 1.4.** Probada a diario en un Motorola Moto G31 con Android 12. En
> otros móviles puede haber diferencias, sobre todo en las voces instaladas. Si
> encuentras un fallo, se agradece el aviso.

## Descarga

La versión de cada momento está en la pestaña [**Releases**](../../releases).
Más información en [pipataki.net](https://pipataki.net/pi-po.html).

**Para instalarla:** descarga la APK en el móvil y ábrela con **Archivos
(Files) de Google**. Android pedirá permiso para instalar apps de origen
desconocido; es lo normal fuera de Google Play.

## Qué necesita

- Android 8 o superior, procesador ARM de 64 bits.
- **Micrófono** (es lo único que pide).
- El **reconocedor de voz** y el **motor de voz** del propio móvil. Si falta la
  voz de algún idioma, la app lo dice y se instala desde los ajustes de Android.
- Conexión **solo la primera vez** de cada idioma.

## Privacidad

- **La conversación no sale del teléfono**: se oye, se traduce y se habla ahí.
- **No registra lo que oye.** El registro de fallos viene apagado.
- **Una palabra, y solo si la pides**: cuando el traductor falla con un término
  y pulsas el botón de buscarlo, se consulta Wikipedia enviando **esa palabra
  sola**, nunca la frase. Lo aprendido se guarda para no repetir la consulta.
- El diccionario que construyes se queda en la carpeta privada de la app.

## Licencia

**© 2026 pipataki. Todos los derechos reservados.** Este repositorio contiene
solo las descargas: el código fuente no se publica.

Lleva dentro componentes con licencia **Apache 2.0**: Vosk y su modelo de voz
español (Alpha Cephei / AC Technologies), ML Kit Translation (Google) y JNA.

## Contacto

[pipataki@pipataki.net](mailto:pipataki@pipataki.net)

---

Hermanos de este proyecto: **[Andro-Kontrol](https://github.com/pipataki/Andro-Kontrol)**,
que maneja el móvil por voz y con la cabeza, y
**[VoiceController](https://github.com/pipataki/VoiceController)**, que hace lo
propio con el ordenador (software libre, LGPLv3).
