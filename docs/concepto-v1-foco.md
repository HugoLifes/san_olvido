# FUERA DE FOCO 📷
### Concepto: RPG en estilo diorama 2D-HD sobre manipular la realidad

> **"Solo existe lo que está enfocado."**

Una entidad de otra dimensión empezó a *mirar* nuestro mundo a través de un lente. Lo que enfoca se vuelve sólido y real. Lo que queda desenfocado se borra: personas, calles y recuerdos. La realidad se convirtió en una **maqueta**, y por eso todo se ve como diorama. Tú eres una fotógrafa de pueblo que encuentra **la Cámara**, un objeto que permite **controlar el enfoque de la realidad**.

---

## 1. La idea en una línea (y por qué es ingeniosa)

El estilo 2D-HD (el de *Octopath Traveler* y *Final Fantasy Resonance*) se reconoce por su **profundidad de campo con efecto tilt-shift**: el fondo y el frente se ven borrosos, como en una maqueta fotografiada. Todos los juegos de este estilo lo usan **solo como decoración**.

**Nosotros lo convertimos en LA mecánica, LA historia y LA interfaz.** El desenfoque deja de ser un filtro bonito: es la regla del mundo. Es lo que pedías: una sola idea explotada en cada capa, como el caballo y el honor en *Red Dead*, el salto de fe y la sincronización en *Assassin's Creed*, o la Oficina que cambia de forma en *Control*.

Además, el estilo tiene una **justificación dentro del mundo**. Los personajes son sprites planos en un mundo 3D porque **la entidad "fotografió" a la gente y la volvió imagen**. Eso no es una limitación técnica: es lore.

## 2. Una mecánica, todas las capas

| Capa | Cómo se usa el enfoque |
|---|---|
| **Exploración** | Con el anillo de enfoque (gatillos o rueda del mouse) mueves el plano de enfoque: frente, medio o fondo. Lo enfocado es sólido y lo borroso se puede atravesar. Un puente al fondo existe solo si lo enfocas. Una pared al frente desaparece si la desenfocas. |
| **Apertura** | Una apertura abierta enfoca una franja delgada: es precisa y poderosa. Una cerrada enfoca casi todo: es segura, pero **gasta luz**. La luz es tu maná. |
| **Puzzles** | Dos objetos a distintas profundidades tienen que verse nítidos a la vez. También hay que desenfocar a un guardia para pasar y enfocar una escalera al mismo tiempo. |
| **Combate** (por turnos) | Los enemigos están en filas de profundidad. Solo puedes dañar a lo enfocado, pero lo enfocado también te puede dañar. Si sobreexpones a un enemigo lo quemas, y si lo subexpones lo debilitas. El "break" se llama **Bokeh**. |
| **Captura** | Le tomas una foto a un enemigo o a un objeto alterado y lo **revelas** como un "Retrato" que invocas en combate. Es nuestra versión de las Visiones de FF Resonance y los Objetos de Poder de Control. |
| **Tiempo** | Una foto guarda un estado de la realidad. Al revelarla, ese lugar vuelve a como estaba. Así se arman puzzles de antes y después. |
| **Historia y emoción** | La gente desenfocada es **gente olvidada**. Las misiones secundarias consisten en volver a enfocar a alguien, o sea, en recordarlo. El tema del juego: **lo que no miramos deja de existir.** |
| **Interfaz** | El HUD es un visor de cámara: la batería es tu vida, el fotómetro tu luz y el indicador de distancia de enfoque tu posición. El menú es un álbum de fotos. |
| **Guardar** | Los puntos de guardado son **cuartos oscuros** con luz roja, como los Control Points de Control. |
| **Sonido** | Lo desenfocado suena apagado (filtro de graves). Lo enfocado suena nítido. |
| **Meta** (el giro tipo *Inception*) | Dentro del pueblo hay una maqueta del pueblo, y si entras ahí hay otra maqueta adentro. Cada capa es más profunda y cambiarla altera la de afuera. En la última capa descubres quién está mirando… y la última cámara es **tu pantalla**. |

## 3. "Sencillo pero llevado más allá": el alcance

- **1 pueblo + 4 dioramas** (capas de realidad) y **8 a 10 horas** de juego.
- **Combate por turnos.** Es mucho más barato de hacer que el combate en tiempo real y es justo lo que espera el público del 2D-HD.
- **Pixel art en los personajes y 3D simple en los escenarios.** El diorama permite niveles chicos y muy reutilizables.
- **Equipo:** de 1 a 3 personas, en unos **18 a 30 meses** para el juego completo.

## 4. Negocio

- **Precio:** de $15 a $20 USD en Steam, y después Switch, PlayStation y Xbox.
- **El modo foto ES el juego.** Cada captura que comparten los jugadores es publicidad. Se puede agregar un "reto de foto del día" en redes.
- **Ruta:**
  1. Prototipo de la mecánica de enfoque en días o semanas: ¿es divertido mover el foco?
  2. **Vertical slice** de 20 minutos, con un diorama completo, en 3 o 4 meses.
  3. Página de Steam para juntar wishlists, demo en **Steam Next Fest** y pitch a publishers indie.
- **Nombre:** "HD-2D" es **marca registrada de Square Enix**. El estilo es libre (*Eiyuden Chronicle* y *Wandering Sword* lo usan), pero en marketing hay que decir "2D-HD", "estilo diorama" o "pixel art 3D".

## 5. Motor

| | **Godot 4** (recomendado) | **Unreal 5** |
|---|---|---|
| Costo | Gratis, licencia MIT, sin regalías | Gratis; 5 % de regalía después del primer millón de USD |
| Para 2D-HD | Sprites en un mundo 3D, filtro nearest, profundidad de campo, bloom y niebla. Hay tutoriales del estilo Octopath | Lo que usó Square para *Octopath*. Mejor iluminación (Lumen), pero más pesado |
| Profundidad de campo controlable en tiempo real | ✅ (CameraAttributes) | ✅ (post-process) |
| Curva de aprendizaje | Baja (GDScript, parecido a Python) | Alta (C++ / Blueprints) |
| Equipo ideal | 1 a 3 personas | Equipos más grandes |

## 6. Ambientación (opciones)

- **Pueblo mágico mexicano con un estudio fotográfico de los años 50:** papel picado, retratos de estudio y fotógrafos ambulantes de plaza. Visualmente es único en el 2D-HD, que casi siempre es fantasía europea.
- **Ciudad gris y burocrática**, más cercana a *Control*, con un "Buró de Fenómenos Ópticos".
- 🧀 *Easter egg:* "el queso que nunca se detiene" puede ser un objeto alterado dentro de este universo, y Cuesta Queso un minijuego interno.

---

*Referencias: [Final Fantasy Resonance (mp1st)](https://mp1st.com/news/final-fantasy-resonance-announced-as-first-hd-2d-entry-launching-this-october) · [HD-2D (Wikipedia)](https://en.wikipedia.org/wiki/HD-2D) · [Marca HD-2D (GameSpot)](https://www.gamespot.com/articles/octopath-traveler-studio-trademarks-hd-2d/1100-6464573/) · [2D-HD en Godot (foro)](https://forum.godotengine.org/t/is-godot-able-to-create-octopath-travelers-hd2d-style-and-how-difficult-would-it-be/16380)*
