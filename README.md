# Laboratorio - Prompts en Inteligencia Artificial

**Por: John J. Bocachica**

> La IA no es solo una herramienta de eficiencia; es un nuevo miembro en su equipo estratégico.  La calidad de su contribución depende enteramente de la calidad de nuestra dirección.

## ¿Qué es el Prompt Engineering? (El Arte de la Conversación Estratégica)

Es simplemente el proceso de diseñar las instrucciones que le damos a una IA.  Piénsenlo como si estuvieran haciendo un *briefing* a un analista extremadamente brillante pero muy literal.  Un *briefing* vago produce resultados vagos. Un *briefing* claro, contextualizado y estratégico produce ideas que pueden cambiar el juego. 

## El Costo de los Prompts Débiles vs. el ROI de los Prompts Efectivos

Un prompt débil como `Dame ideas de marketing` puede costar horas de trabajo refinando resultados genéricos. 

Un prompt efectivo como `Actúa como un CMO para una marca de lujo B2C. Genera 3 estrategias de marketing de bajo costo para aumentar la retención de clientes en un 15% este trimestre, enfocándote en canales digitales` puede generar una estrategia casi lista para implementar.

La diferencia es un ROI masivo en tiempo y calidad de ideas. 

-----

## El laboratorio

Este laboratorio consta de una serie de pasos que se deben ir ejecutando uno a uno. Es posible que sienta la tentación de adelantarse para ver el resultado final y sienta la ansiedad que la misma Inteligencia Artificial ha generado en los humanos, esa necesidad de obtener respuestas rápidas con preguntas simples. Pero déjese llevar por este proceso, verá cómo de forma progresiva irá logrando mejorar sus habilidades en el uso de este tipo de tecnologías. Es posible que en algunos casos se sienta decepcionado, tranquilo, es normal. En los 90 también nos costaba trabajo enviar un correo electrónico y hoy lo hacemos hasta dictándoselo a nuestro asistente digital mientras conducimos, sea Alexa, Siri, Google Home o el que utilicemos a diario (Si es que lo utilizamos – Sabían que eso se puede, ¿cierto?).

### Estructura

El laboratorio tiene la siguiente estructura. 

| Prompt Débil | Salida Esperada | Prompt Mejorado |
| :--- | :--- | :--- |
| Así encontrará los prompts que se consideran débiles, esos que no nos van a aportar, pero con el que nos sentiremos muy identificados porque quizá, sea la forma en que más interactuemos con este tipo de herramientas.  | Así encontrará la salida esperada de los prompts débiles, la intención es que veamos lo “predecible” que puede llegar a ser esta tecnología si no la aprovechamos.  | Así encontrará los prompts que se consideran “Mejorados”, lo pongo entre comillas porque este es un proceso de mejora continua.  |

-----

## Paso a paso del laboratorio

Diríjase a su herramienta preferida, puede ser [ChatGPT](https://www.chat.com) , [Gemini](https://gemini.google.com/), [Claude](https://claude.ai/), [Perplexity](https://www.perplexity.ai/) o con el que se sienta más cómodo. 
Este laboratorio puede tener algunas variaciones en la respuesta esperada dependiendo de la herramienta utilizada; el objetivo de este laboratorio es que dichas variaciones no dependan de la herramienta sino de la forma en que se use la tecnología. 

### ¿Es la IA realmente Inteligente?

Antes de iniciar con las tácticas, realizaremos una serie de ejercicios prácticos. 

#### Calibrando el reloj…

Vaya a la IA de su preferencia y pídale que cree un reloj de pulsera de manecillas, que sea hiperrealista y que genere dicha imagen. 

> **Prompt de ejemplo:** `Crea una imagen de un reloj de pulsera con manecillas hiper realista`

Es posible que su reloj tenga una hora “aleatoria”.  Ahora, necesitamos calibrar la hora del reloj. Elija una hora al azar y calibre dicha hora en la imagen generada por la IA seleccionada. Es una tarea simple, ¿no? Recuerde que necesitamos un reloj hiperrealista. 

> **Prompt de ejemplo:** `Ahora quiero que el reloj marque las 6:05` 

#### ¿Memoria o pensamiento?

Vaya a la IA de su preferencia, iremos pasando frases muy conocidas de las cuales todos sabemos la respuesta. Sin embargo, lo invito a que haga este mismo experimento con niños pequeños que no conozcan la respuesta y se sorprenderá… 

  - Cuando el río suena… 
  - Ojos que no ven… 
  - El que nada debe… 

#### Ahora realizaremos otro experimento, para este, no utilizaremos la IA, simplemente haremos una votación personal.

##### Metodología del ejercicio 

Van a ver una frase, puede que tenga sentido, puede que no, el objetivo es que simplemente seleccionen la palabra que consideran es la palabra que debe llenar el vacio o debe continuar en la frase.

| Frase | Posibles palabras (Selecciona una) |
| :---  | :---                               |
| El elefante es ... | &#x2713; Un mamifero <br> &#x2713; el animal terrestre mas grande <br> &#x2713; Gris <br> &#x2713; Un animal herbivoro <br> &#x2713; Inteligente |
| En diciembre el clima es ... | &#x2713; Frio <br> &#x2713; Lluvioso <br> &#x2713; Templado <br> &#x2713; Variable <br> &#x2713; Cálido |
| Las vacas producen ... | &#x2713; Leche <br> &#x2713; Carne <br> &#x2713; Metano <br> &#x2713; Alimento <br> &#x2713; Estiercol |
| Una sonrisa representa ... | &#x2713; Felicidad <br> &#x2713; Alegría <br> &#x2713; Amabilidad <br> &#x2713; Bienestar <br> &#x2713; Positividad |

Así como funcionó este ejercicio, asi mismo funciona una inteligencia artificial, basandose en unos datos de entrada, realiza una preseleccion de posibles palabras siguientes y aleatoriamente selecciona una de dichas palabras, cada palabra tendrá una probabilidad y dicha probabilidad será utilizada basandose en un parametro llamado Temperatura.

#### Como ocurre todo detrás de camaras?

$Hombre + Hijo \approx Papá$

$(Reina - Mujer) + Hombre \approx Rey$

-----

## Táctica 1: El poder de la persona y el contexto

| Prompt Débil |
| :--- |
| Explica los riesgos de la expansión a un nuevo mercado.  |

| Salida Esperada |
| :--- |
| Una lista genérica de riesgos: competencia, regulación, diferencias culturales, logística, etc.|

| Prompt Mejorado |
| :--- |
| Actúa como un CFO con 20 años de experiencia en fusiones y adquisiciones internacionales. <br> Estoy considerando expandir nuestra empresa de software SaaS al mercado alemán. <br> Enumera los 5 principales riesgos financieros que debo presentar al Consejo de Administración, y para cada uno, sugiere una métrica clave (KPI) para monitorearlo.|

-----

## Táctica 2: La especificidad y el formato de salida

Para este prompt, necesitaremos [este](datos-encuesta-nps.csv) archivo de ejemplo. 

| Prompt Débil |
| :--- |
| Resume los resultados de la encuesta de satisfacción del cliente.  |

| Salida Esperada |
| :--- |
| Un párrafo largo y denso con los hallazgos.  |

| Prompt Mejorado |
| :--- |
| He realizado una encuesta de satisfacción del cliente. <br> Los puntos clave son: A cada cliente se le hicieron 4 preguntas, Experiencia en general, Calidad de la comida, velocidad de Entrega y Si el producto fue entregado adecuadamente o no. <br> <br> Quiero que redactes un correo electrónico para mi equipo directivo. <br> El correo debe tener: <br> 1. Un asunto claro y conciso. <br> 2. Un párrafo introductorio de no más de 3 líneas. <br> 3. Tres bullets points: uno para el hallazgo positivo y dos para las áreas de mejora. <br> 4. Un llamado a la acción claro: agendar una reunión para definir un plan de acción.  |

-----

## Táctica 3: Few Shot Prompting, enseñar desde el ejemplo

| Prompt |
| :--- |
| Eres un clasificador de sentimientos de tweets. Tu tarea es analizar el texto de un tweet y clasificar el sentimiento que expresa en una sola palabra. Los sentimientos posibles son: 'happy', 'sad', 'fear', 'angry', 'surprise', 'irritating'.<br><br>A continuación, se muestran 10 ejemplos de tweets y su sentimiento asociado:<br>Tweet: " \#31: @Otep 🌠 ed ""im fvkin\* depressed [https://t.co/t1S92BIXwO](https://t.co/t1S92BIXwO)"""<br>Sentimiento: sad<br>Tweet: " \#60: @MrRemain is an Ultra-Remainer ed ""RT @SimonBruni: It's not a path, ""Let's go WTO"" is the UK having a nervous breakdown. We'll be the country that ends up on a park bench wea…"""<br>Sentimiento: fear<br>Tweet: " #7: @BabsMidd ed "RT @fireboyle: Someone shared a really fantastic speech and it reminded me of this from last March. This is an absolute masterclass in the…"" <br>Sentimiento: sad <br>Tweet: " #87: @moorsman ed "RT @karenspenley: I’m pleased to say this happened a lot this weekend. As we enter BBQ season, what will you be talking about? The most i…"" <br>Sentimiento: happy <br>Tweet: " #30: @眞琥 ed "@8o6p1y0a1n0n3u1 いつの絵でもダルさんは可愛いしかっこいい"" <br>Sentimiento: surprise <br>Tweet: " #86: @Kenny Masoko ed "RT @Sowellnomics: @kennymasoko Venezuela was once the most prosperous country in Latin America with the largest proven oil reserves on the…"" <br>Sentimiento: happy <br>Tweet: " #2: @Post-liberal Bot ed "Did you like the fact that I included the Jesuits this time? @glum_bucket dont want them to feel left out."" <br>Sentimiento: sad <br>Tweet: " #34: @The Norbert_empire™ 🏰 ed "@Wyclif256 Psalms 16:5 Lord, you alone are my inheritance, my cup of blessing. You guard all that is mine.#ApostleGraceInNairobi #KICC #1stJUNE"" <br>Sentimiento: happy <br>Tweet: " #21: @Asset Harbour ed "Recent research reveals 44% of UK adults do not think they will have enough money to enjoy their retirement. Whether you're thinking about saving into a pension for the first time, making decisions for your retirement or giving your child a financial head start, we can help. https://t.co/16X2NqF6Qt"" <br>Sentimiento: happy <br>Tweet: "Tweet #9: @#BlackChina☣️® tweeted "@MbalulaFikile @SpheDludla @Aveewear1 @AfriNewsAgency Brika nyana tuu we still mourning our granny we can’t be jaiving all over , rejoice not allowed in our culture https://t.co/MHK3YQtgAt"" <br>Sentimiento: sad <br><br>Ahora, clasifica los siguientes tweets. Solo responde con el sentimiento:  |

| Tweet a clasificar 1 |
| :--- |
| @kimilabs25 ed ""RT @AishaZ23: I don’t want to ever forget this night where there ordinary guys made Magic Happen and then stayed to watch the fireworks\! @B…""|

| Tweet a clasificar 2 |
| :--- |
| @Kathleen Lyons ed ""Win a $250 jovial Shopping Spree\! [https://t.co/nJIRVWiYgj](https://t.co/nJIRVWiYgj)|

| Tweet a clasificar 3 |
| :--- |
| Vi a Johnny de 'Guess Who's Home' y mi corazón se me encogió un poco.|

-----

## Táctica 4: Cadena de pensamiento (Chain-of-Thought)

> Problema: Necesitamos organizar un evento donde se sentarán 10 personas, distribuidas en 5 parejas casadas, alrededor de una mesa redonda. Existe una condición social estricta: ninguna persona puede sentarse junto a su propio cónyuge.

Para este ejercicio no utilizaremos un modelo tradicional, vamos a algo un poco mas avanzado. [Google AI Studio](https://aistudio.google.com/)

- Ejercicio 1: Probaremos con un modelo que no soporte "pensar"
- Ejercicio 2: Probaremos con un modelo mas sofisticado, pero que pueda "pensar"
- Ejercicio 3: Dejaremos que el modelo piense
- Ejercicio 4: Se lo pediremos explicitamente

> Prompt inicial: `¿De cuántas maneras pueden sentarse cinco parejas casadas alrededor de una mesa redonda si no hay cónyuges sentados uno al lado del otro?`

-----

## Ejercicio práctico

Ahora, apliquemos estas tácticas a un escenario real de negocio.  Tenemos un conjunto de datos, `rotacion-empleados.csv`, que contiene información sobre empleados y su historial en la empresa.  El objetivo de negocio es reducir la rotación de personal voluntaria.  Veamos cómo el prompt engineering nos ayuda a extraer inteligencia estratégica de estos datos. 

### Su primera misión / La descriptiva

Queremos entender por qué los empleados renuncian a la compañía. En el archivo, la columna “event” determina si este empleado renunció o no. Este archivo tiene más de 1000 filas de empleados de diferentes áreas.  Los datos son los siguientes:

| Columna | Significado |
| :--- | :--- |
| **Stag** | Experiencia en años |
| **Event** | Renunció (1 = Si, 0 = No) |
| **Gender** | Género (Femenino, Masculino) |
| **Age** | Edad del empleado |
| **Industry** | Industria en la que trabaja el empleado |
| **Profession** | Profesión del empleado |
| **Traffic** | Forma en que el empleado llegó a la compañía (`Advert` – Contacto directo por publicidad, `recNErab` – Recomendado por un no empleado, `Referal` – Recomendado por un empleado, `Youjs` – Aplicó a vacante, `KA` - Head hunter, `Friends` – Contacto directo por invitación, `rabreNErab` – Contacto por recomendación de un conocido, `Empjs` – Encontrado en portal de empleo) |
| **Coach** | Tuvo un coach para el entrenamiento |
| **Head\_gender** | Género del o la jefe |
| **Greywage** | Tipo de salario que recibe (`Grey`: Una parte del pago no es constitutivo de parafiscales, `White`: El 100% es salarial) |
| **Way** | Tipo de transporte utilizado para llegar al trabajo |
| **Extraversion** | Calificación de qué tan extrovertida es la persona |
| **Independ** | Calificación de independencia |
| **Selfcontrol** | Calificación de autocontrol |
| **Anxiety** | Calificación de ansiedad |
| **Novator** | Calificación de innovación |

El objetivo de la compañía es reducir el índice de rotación de personal, la verdad no sabemos por dónde empezar, pero necesitamos ayuda. 

### Su segunda misión / La predicción

Un buen líder no solo mira el pasado, sino que se anticipa al futuro. Podemos usar la IA para eso.  Ahora, necesito saber en qué empleados me puedo concentrar, quiénes son los de más alta probabilidad de renuncia, pero no quiero una lista, quiero saber cuál es el perfil de los que pueden estar renunciando en los próximos seis meses. 

### Su tercera y última misión / Uplift Modeling

Finalmente, el nivel más alto de estrategia: no solo predecir quién se irá, sino determinar qué acción tendrá el mayor impacto para retenerlos.  Esto se acerca al concepto de 'Uplift Modeling'.  Tenemos una idea, queremos darles a los empleados opciones sobre las acciones de la compañía (Stock Options), sin embargo, no tenemos ni idea de si eso va a servir o no, necesitamos de tu ayuda. 

-----

#### Se acuerdan del ejercicio de la seleccion de siguientes palabras?

```
Tu mision es demostrar como funcionan los modelos de LLM.

Para este ejercicio, te voy a entregar una frase y necesito que me entregues las 5 palabras mas probables que continuan, cada una con su probabilidad y finalmente selecciones una, no debes responder nada mas.

Por ejemplo:

Frase de entrada:
El sol es ...

Respuesta esperada:
Una estrella [ Probabilidad del 0.4]
Parte del sistema solar [Probabilidad de 0.2]
Amarillo [Probabilidad de 0.1]
Una bola de fuego [Probabilidad de 0.05]
Hermoso [Probabilidad de 0.05]
```
