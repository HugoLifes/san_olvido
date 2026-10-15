# San Olvido: prototipo de combate (Fuera de Foco v2)

Abre `index.html` en Chrome o Edge. Necesitas internet para cargar three.js, además de teclado y mouse. Dura de 10 a 15 minutos.

## La regla de oro
**Tú y el enemigo tienen que estar dentro de la franja de foco para hacerse daño.** La franja es la banda horizontal nítida, marcada con líneas doradas en el suelo. Todo lo de afuera es niebla: no te toca, pero tampoco lo tocas.
Los **Velados** son al revés: solo existen **fuera** de foco. Para pelear con ellos, mueve la franja lejos de los dos (Q/E) y pelea rápido antes de que el **olvido** te alcance.

## Controles
| | |
|---|---|
| WASD + mouse | Moverte y apuntar |
| Clic / J | Atacar con el lente (el 3.er golpe del combo pega más fuerte) |
| Clic derecho / K | **Flash**. Si el enemigo brilla en **dorado (!!)**, lo sobreexpones (parry) y queda aturdido |
| F | **Foto** a un enemigo aturdido: lo ejecutas (al jefe le quita 10 %) y recuperas vida |
| Espacio | Esquiva: te desenfocas un instante y nada te toca |
| Q / E · rueda · C | Mover la franja de foco · centrarla en ti |
| 1 / 2 | Gran angular (arco amplio y franja ancha) / Teleobjetivo (disparos y franja estrecha; crítico en el centro exacto) |
| H | Veladora: cura (3 por descanso) |
| R | Descansar en un cuarto oscuro: sube de nivel con tus recuerdos y revive a los enemigos |

## Qué hay en el panteón
- **Mirones:** rápidos, se lanzan contra ti. El flash los deslumbra.
- **Olvidados:** lentos y pegan duro. **Si los mantienes enfocados de cerca 3 s sin atacarlos, recuerdan su nombre** y se van en paz (dan más recuerdos).
- **Velados:** solo existen desenfocados y te susurran (sube tu olvido).
- **Botín:** el Teleobjetivo (en un altar al fondo), el Milagrito de corazón (+vida) y el Milagrito de ojo (franja más ancha).
- **Jefe, El Sepulturero Sin Rostro:** su *palada* se puede parar con flash; el *golpe de tierra* (círculo rojo) hay que esquivarlo. A la mitad de su vida llama a dos Olvidados y empieza a **velarse**: mientras está velado, solo lo puedes herir fuera de foco.
- **Al morir:** tus recuerdos se quedan en una foto donde caíste. Vuelve por ella.


## Novedades (v0.2): progresión estilo Minecraft + Diablo
- **Corazones** en lugar de barra de vida, y **barra de experiencia verde** con tu nivel abajo.
- Los enemigos sueltan **orbes de recuerdo** (experiencia) que vuelan hacia ti. Cada nivel te da **1 punto de atributo**.
- **I** abre la hoja de personaje (el juego se pausa). Ahí repartes puntos en ❤ Vitalidad, 🕯 Luz, ⚔ Exposición (daño), 👁 Enfoque (franja y parry) y 👟 Agilidad.
- **Ropa visible:** sombreros, rebozos y sarapes, botas y amuletos **cambian cómo se ve Luz** y sus estadísticas. Hay 4 rarezas: común, raro, épico y legendario.
- **Cofres** (R para abrir): normales; **velados**, que solo existen fuera de foco (aléjales la franja para verlos); un **cofre mirón** que muerde; y el **cofre del Sepulturero**, que se abre al vencerlo.
- **Dificultad creciente:** los enemigos suben de nivel (Nv 1 a 4) mientras más avanzas, y hay **élites** con aura dorada que pegan más fuerte y siempre sueltan objetos.
- **5 secretos:** 3 notas de Don Aurelio que cuentan la historia, una tumba muy especial y algo que *nunca se detiene*…
- Al morir pierdes la experiencia del nivel en curso, que se queda en una foto donde caíste. Los niveles nunca se pierden.

## Preguntas para el playtest
1. ¿Mover la franja de foco **en pleno combate** se siente como una herramienta táctica o como un estorbo?
2. ¿El parry con flash se entiende? ¿El aviso dorado llega a tiempo?
3. ¿La fase velada del jefe es emocionante o confusa?
4. ¿Lo oscuro se siente atmosférico o simplemente no ves nada?
5. ¿Recordar a un Olvidado en lugar de matarlo te dio algo distinto?

Consola de pruebas (F12): `SO.st()`, `SO.tp(x,z)`, `SO.god(true)`, `SO.step(seg,['KeyD'])`.
