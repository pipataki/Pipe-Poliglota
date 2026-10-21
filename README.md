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
- **Se conversa seguido.** El idioma se dice una vez y se queda puesto: frase,
  traducción, y a por la siguiente sin tocar nada. Para cambiarlo, se nombra el
  otro; para terminar, «para» o «basta».
- **Escucha también la respuesta.** Con «Conversación» marcado, después de
  decir tu frase se queda oyendo en el otro idioma, y lo que te contesten te lo
  dice en español. Los turnos se alternan solos; si nadie contesta, vuelve a
  escucharte a ti, y si quieres hablar antes, el botón «Hablo yo».
- **Con auricular Bluetooth, cada uno por su aparato.** Tú hablas y oyes por el
  auricular; el otro habla al móvil y oye tu traducción por su altavoz. Si
  nadie habla, el turno pasa solo al otro: empieza el primero que hable. Sin
  auricular, o si no responde, todo sigue por el móvil.
- **Lo que te contestan, con el traductor de Firefox.** El mismo que lleva el
  navegador Firefox: libre, gratuito y dentro del móvil, sin conexión. Suena
  más natural. Traduce directo del inglés; los demás idiomas pasan por el
  inglés y tardan algo más. Si falla o le falta un idioma, sigue el traductor
  de siempre.
- **Cada frase, con su altavoz y su ✕.** Las traducciones se van apilando en una
  lista, la última arriba: se vuelve a oír la que quieras y se borra la que
  quieras. También por voz: «borra» o «borra la última».
- **Se cierra cuando lo dices.** Un botón al final de la pantalla y la orden
  «cierra la aplicación», para no dejarla abierta con el micrófono cogido.

> **Versión 1.8.** El traductor de Firefox se probó en un Motorola Moto G31
> con Android 12, con noticias de la tele en inglés y en polaco; la 1.8 tal
> cual sale **sin la tanda de uso diario** de las versiones anteriores. En
> otros móviles puede haber diferencias, sobre todo en las voces instaladas. Si
> encuentras un fallo, se agradece el aviso.
>
> **Desarrollo en pausa.** Las pruebas de traducción siguen ahora en un
> proyecto hermano en preparación. Pipe-Políglota queda a la espera de que el
> traductor de Firefox traduzca entre más idiomas sin pasar por el inglés, y
> eso depende de sus desarrolladores.

## Descarga

La versión de cada momento está en la pestaña [**Releases**](../../releases).
Más información en [pipataki.net](https://pipataki.net/pi-po.html).

**Para instalarla:** descarga la APK en el móvil y ábrela con **Archivos
(Files) de Google**. Android pedirá permiso para instalar apps de origen
desconocido; es lo normal fuera de Google Play.

## Qué necesita

- Android 8 o superior, procesador ARM de 64 bits. El traductor de Firefox
  pide Android 9; en Android 8 se usa el de siempre.
- **Micrófono** (es lo único que pide).
- El **reconocedor de voz** y el **motor de voz** del propio móvil. Si falta la
  voz de algún idioma, la app lo dice y se instala desde los ajustes de Android.
- Conexión **solo la primera vez** de cada idioma (y de cada modelo de
  Firefox, de 20 a 40 MB, que se baja de los servidores de Mozilla).

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
Y el traductor de Firefox,
[bergamot-translator](https://github.com/browsermt/bergamot-translator)
(MPL-2.0), con Marian NMT (MIT) y otras piezas libres. Sus licencias completas
van dentro de la APK, en `assets/licencias-firefox.txt`. Los modelos de
traducción (MPL-2.0) los descarga la app de los servidores de Mozilla.

## Contacto

[pipataki@pipataki.net](mailto:pipataki@pipataki.net)

---

Hermanos de este proyecto: **[Andro-Kontrol](https://github.com/pipataki/Andro-Kontrol)**,
que maneja el móvil por voz y con la cabeza, y
**[VoiceController](https://github.com/pipataki/VoiceController)**, que hace lo
propio con el ordenador (software libre, LGPLv3).
