---
layout: post
title: "The 10x Aura Developer"
date:   2024-10-14 13:00:00 -0600
categories: [blogging]
---
En el 2021 decidí cambiar de empleo. El proceso de búsqueda incluyó múltiples entrevistas e inclusive asignaciones, fue algo extenso. En uno de los posibles proyectos tuve la conversación referente a las tecnologías usadas y los conocimientos que se esperaban de mi parte.

En ese proyecto en particular, Typescript era el lenguaje de programación principal. Yo sólo conocía Python y Bash en ese momento. No dominaba Typescript.

Le comenté al entrevistador que no conocía esa tecnología y él tomó nota del tema. Conversamos sobre otros asuntos y finalizó la entrevista. Pensé que no había forma de lograr entrar al proyecto. El principal lenguaje usado no estaba dentro de mi CV.

Días después me comunicaron que fui aceptado, justo en el proyecto donde menos esperaba quedar. — Debió haber algún error — pensé yo, pero no, estaba dentro.

Las primeras semanas fueron verdaderamente retadoras. Tuve que aprender cosas nuevas y recordar conceptos olvidados. Lidiar con curvas de aprendizaje es algo que al parecer uno nunca deja de hacer durante la vida y carrera profesional.

Es por eso que en esta breve blog me gustaría compartir con ustedes lo que aprendí durante ese proceso.

# **TL;DR**

- Be honest & humble
- Read & share, a lot
- Principles DO matter


# Be honest & humble

Comenzaron a pasar los días dentro del proyecto y comencé a asistir a los daily standup. Se me asignaban tareas en el sprint que no siempre entendía del todo. En esta situación, incorrectamente asumía que era una debilidad exponer la verdad de mi situación con el resto del equipo: no tengo muy claro cómo usar este lenguaje.

En algún punto todos nos hemos encontrado en una situación similar. Se espera de nosotros algo que sabemos no somos capaces de lograr en ese instante. La respuesta natural de nuestra mente es protegernos ante la posibilidad de humillación o fracaso. La vía de escape es ocultar nuestra debilidad aparentando o mintiendo.

Está bien no saber todo de memoria. Está bien no entender algún concepto. Está bien no haber usado antes el framework más popular. No pasa nada, pero hay que comunicarlo abierta y honestamente.

Si ocultamos nuestra debilidad rechazamos la posibilidad de mejorar. En el equipo correcto, esto no será problema y podremos recibir apoyo para cubrir las necesidades de aprendizaje que tenemos. De eso se trata trabajar en equipo.

“Sí, claro que le entiendo, ya lo he hecho antes. Yo me encargo.” — alguien que no le entiende —

¿Qué te ganas ocultando las debilidades?

- Estrés innecesario
- Mala reputación
- Incertidumbre en el equipo

Es preferible la honestidad, siempre. Los problemas se tienen que comunicar rápido, claro y seguido. No retrasos. Comunicar correctamente ayuda a que el equipo tenga mayor disposición de ayudar.

Cuando superemos la curva de aprendizaje, ahora nosotros estaremos en la posición de tener conocimientos del tema y es muy probable que los papeles se inviertan. Se esperará de ti que seas una persona que logre empatizar con los nuevos miembros del equipo y puedas compartir lo que sabes con la misma paciencia que hubieras querido tener en tus inicios.

**Useful phrases:**

- I don’t understand *yet* how this should work. Can someone guide me through it?
- I haven’t used this before. I would like some help after today’s standup.

# Read & share, a lot

Superado el daily, era tiempo de trabajar en las actividades. Tiempo de ponerse a programar.

Guido van Rossum, el creador de Python, menciona que el código es mayormente *leído* que escrito. Esa es la realidad de interactuar con computadoras, mucho es texto.

Existe la percepción de que programadores jóvenes tienden a evitar leer. Es una discusión quizá algo basado en estereotipos, pero la idea es que prefieren el contenido en video a texto. Ahora mismo, el video parece tener mayor preferencia entre las formas de consumir contenido en redes sociales, por ejemplo. Personalmente considero que no es la mejor forma de aprender a desarrollar.

Me gustaría destacar algunas características del texto que lo hacen la opción que yo recomiendo en lugar de otros formatos.

- El texto es buscable, `ctrl + f`
- Puedes hacer copy-paste (copy-paste ≠ plagio)
- Cuando tengas que arreglar algo en tu código, todo lo que verás será usualmente… texto.

Cuando tu aplicación se encuentra fallando en producción, tendrás la información relevante en este formato:

![]({{ site.baseurl }}/assets/logging.png)
*Ejemplo de logging en una aplicación productiva*

Acostumbrarse a leer te dará grandes ventajas para resolver preguntas en tu proceso de aprendizaje. Después de cierto tiempo leyendo documentación o código, uno puede identificar patrones y keywords que aceleran el aprendizaje y resolución de problemas. No acostumbrarse a leer puede complicar reconocer esos patrones. Al final es una habilidad que podemos ejercitar.

Mantén a tus ojos y cerebro acostumbrados a buscar patrones relevantes. No hay escapatoria a la práctica.

Esto incluye saltarse la pregunta en StackOverflow e ir directo a la respuesta. El contexto hace toda la diferencia.

## Share code , share code, share code

Muchos aspiramos a tener un trabajo remoto. Hay un catch importante de conocer en esto. Es fácil volverse tímido o apático durante el trabajo. Todo comienza con evitar encender tu cámara, después con apatía a compartir pantalla y colaborar de forma virtual. Suena excelente la idea de trabajar en pijamas, pero de forma personal no lo recomiendo. Si algo he aprendido trabajando remoto es que mientras más colabores con tu equipo, mejor.

El equipo necesita visibilidad y compartir tu pantalla es la forma de dejarlos entrar a tu oficina.

Otra forma de mejorar tus ciclos de feedback es compartir tu código vía git. Nunca son suficientes commits, los branches vienen incluidos, crear un MR no tiene costo extra. Úsalo sin miedo.

<span style="color:red">*-\- No logro hacer que la autenticación funcione, me ayudas?*</span>
<br>
<span style="color:green">*++ No logro hacer que la autenticación funcione, he intentado esto <span style="color:blue"><u>MR Link</u></span>. Me ayudas? Puedo mostrarte en una llamada.*</span>

Si estás intentando resolver un problema técnico o entender algo sin compartir código, sin ejecutarlo y obtener los errores en vivo durante la llamada, todo es más lento. No se puede tener una discusión técnica sin ver y modificar el código. En otras palabras, uno aprende a programar  *programando.*

Logra sentirte cómodo programando en equipo, programando mientras otros ven lo que haces. Incluso cómo googleas por respuestas, en el equipo correcto eso no es cosa rara. Haz que tus errores aparezcan en la llamada, eso acelera el aprendizaje.

Useful phrases:

- Can you watch me refactor this method and spot where the issue is? I can’t see it.
- Can we jump on a call and *show* you where I’m getting the error?

# Principles DO matter

Durante las primeras semanas en el proyecto, tuve otra conversación con el líder del equipo que estuvo a cargo de mi contratación. Le comenté que me causó bastante sorpresa haber sido aceptado cuando les había dicho que no conocía la tecnología que más usaba el equipo. Su respuesta fue “What usually matters the most is that you know the principles…”

Mientras uno se enfrenta a temas desconocidos, es tentador enfocar la mente en obtener *la* respuesta. Cuando en realidad debemos buscar entender mejor el problema, lo que naturalmente te hará llegar a la solución después de las iteraciones necesarias. No te concentres en buscar respuestas, busca mejores preguntas.

Al interactuar con tu equipo recuerda que no buscas que te expliquen la situación particular, buscas entender mejor qué salió mal o el sistema con el que estás interactuando. Poco a poco, construirás un mapa mental más robusto que representa el verdadero aprendizaje sobre el tema en cuestión.

![]({{ site.baseurl }}/assets/neoSeesTheTruth.jpg)
*POV: entiendes los conceptos antes que las soluciones obvias*

## Sobre AI assisted programming

El uso de AI para apoyarse a programar llegó para quedarse. Creo que es una gran herramienta, pero a veces es mucho más de lo que uno necesita cuando se es principiante en algún tema.

El truco está en evitar aceptar en automático cualquier sugerencia. No lo haríamos en cualquier otra situación, tomar consejo de un *extraño* y aceptarlo sin cuestionarlo antes. Con AI es lo mismo. Si no entiendes los porqués del código que se te sugiere, es señal de que necesitas frenar un poco y *volver a los principios*. Las ideas básicas que conforman el gran concepto que pretendes dominar. Irás más lento, quizá, pero te aseguro que llegarás más lejos en el entendimiento del problema y tu capacidad de aplicarlo en otras áreas más adelante.

El segundo riesgo del uso inconsciente de AI en tu carrera de programador, será será cuando el código generado por AI que lograste meter al mainstream se rompa en producción.

En ese instante vas a ser despertado a las 3AM, tu equipo y responsables te meterán a la llamada de emergencia y esperarán que expliques y soluciones el por qué del error en tu código. Decir que le pregunten a Github Copilot no será tu mejor respuesta.

De todas formas, para obtener los mejores resultados de AI, necesitas — paradójicamente — hacer mejores preguntas. Esto se logra entendiendo los principios.

# Hard things are hard

Estos consejos me ayudaron a superar la curva de aprendizaje, sí, pero no representaron una solución mágica al reto de aprender algo nuevo. Las cosas complicadas son… complicadas. No hay atajos ni trucos.

Está bien sentirse estresado y frustrado, es difícil y te tomará tiempo dominar el tema y sentirte cómodo. Pero de eso se trata, no hay nada mal contigo. Sé paciente y aprende a encontrarle el cariño a la idea de que tu carrera como desarrollador estará llena de repetidos episodios de “Hey, I don’t know anything about this, but I’ll give it a try and have fun in the process!”.