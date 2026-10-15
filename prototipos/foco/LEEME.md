# Fuera de Foco: prototipo de la mecánica

Abre `index.html` en Chrome o Edge. Necesitas internet para cargar three.js y un teclado. Dura de 5 a 10 minutos.

## Controles
| Tecla | Acción |
|---|---|
| W A S D / flechas | Moverte (W va al fondo, S va al frente) |
| Q / E · rueda del mouse | Mover el foco |
| 1 · 2 · 3 (o Tab) | Apertura: f/1.4 (franja delgada, recarga luz) · f/4 · f/16 (casi todo enfocado, gasta luz) |
| F · Espacio · clic | Foto: lo inestable que esté enfocado se vuelve real por 10 s y los Mirones se congelan |
| R | Volver al último cuarto oscuro |

## Reglas
- **Lo inestable (puentes, cajas y Mirones) solo existe si está enfocado.** Lo borroso se atraviesa.
- **Tú también tienes que estar enfocada.** Si sales de foco, sube el **olvido**, y si llega al máximo vuelves al cuarto oscuro.
- Un Mirón solo te daña si **los dos** están enfocados.
- Los cuartos oscuros (luz roja) guardan tu progreso y recargan película, batería y luz.

## Las 7 secciones (cada una enseña una regla)
1. **La plaza:** enfocar hace aparecer el puente.
2. **Las cajas:** desenfocarte para atravesar cosas.
3. **Los Mirones:** decidir qué enfocar para esquivar.
4. **Dos distancias:** usar f/16 y administrar la luz.
5. **La foto:** congelar la realidad para cruzar.
6. **Los olvidados:** enfocar a alguien para que recuerde quién es.
7. **La Entidad:** su mirada te arrastra el foco.

## Preguntas para el playtest (anota lo que sientas)
1. ¿Mover el foco se siente **satisfactorio** o **tedioso**?
2. ¿El olvido (la presión de no desenfocarte) es **tensión divertida** o **castigo**?
3. ¿Entendiste **sin leer** que la foto era la solución de la sección 5?
4. ¿Qué momento te dio un "¡ahhh, ya entendí!"? Ese es el corazón del juego.
5. ¿Qué sección se te hizo más aburrida?

## Detalle técnico
El desenfoque no se calcula por distancia a la cámara, como en una cámara real, sino **por fila del mundo**. Así, lo que se ve nítido es exactamente lo que el juego considera real. Lo fotografiado se marca en una máscara y se dibuja nítido y en sepia.

Consola (F12) para pruebas: `FDF.tp(x, fila)` te teletransporta, `FDF.st()` muestra el estado y `FDF.step(seg, ['KeyD'])` simula teclas.
