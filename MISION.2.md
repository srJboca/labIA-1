## MISION 2: LA ROTACION DE LOS EMPLEADOS

Ahora, apliquemos estas tácticas a un escenario real de negocio.  Tenemos un conjunto de datos, `rotacion-empleados.csv` que puedes descargar [aquí](rotacion-empleados.csv), que contiene información sobre empleados y su historial en la empresa.  El objetivo de negocio es reducir la rotación de personal voluntaria.  Veamos cómo el prompt engineering nos ayuda a extraer inteligencia estratégica de estos datos. 

### Su primera sub-misión / La descriptiva

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

### Su segunda sub-misión / La predicción

Un buen líder no solo mira el pasado, sino que se anticipa al futuro. Podemos usar la IA para eso.  Ahora, necesito saber en qué empleados me puedo concentrar, quiénes son los de más alta probabilidad de renuncia, pero no quiero una lista, quiero saber cuál es el perfil de los que pueden estar renunciando en los próximos seis meses. 

### Su tercera y última sub-misión / Uplift Modeling

Finalmente, el nivel más alto de estrategia: no solo predecir quién se irá, sino determinar qué acción tendrá el mayor impacto para retenerlos.  Esto se acerca al concepto de 'Uplift Modeling'.  Tenemos una idea, queremos darles a los empleados opciones sobre las acciones de la compañía (Stock Options), sin embargo, no tenemos ni idea de si eso va a servir o no, necesitamos de tu ayuda. 
