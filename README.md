En un hospital se está diseñando un nuevo sistema el cual gestionará la carga de recetas y su
procesamiento. En principio, el sistema incorporará profesionales de la salud (médicxs) con cierta
especialidad, pero por el momento no diferenciaremos. Un profesional siempre tendrá una matrícula
propia y única dentro del sistema y un nombre. Al momento de incorporar un profesional se debe
verificar si ya existe registrado contemplando su matrícula. Lxs profesionales pueden recetar estudios a
pacientes del hospital.
Lxs pacientes tienen un número de dni que lxs identifica y un un nombre. Para inscribir al paciente al
hospital, se debe verificar que no exista previamente en el mismo (considerando el dni).
Las recetas se componen de un identificador numérico único en todo el sistema del hospital. Al
momento de recetar, un profesional puede incluir varios estudios que deberá realizarse al paciente. Una
receta sólo puede estar dirigida a un paciente específico y cuando se carga inicialmente queda
pendiente de procesamiento, es decir, está disponible para procesar. Esta operación de procesar una
receta representa el momento en que el paciente se dirige a realizar los estudios de la misma. Se recibe
la receta, se valida que no haya sido procesada previamente y se efectúan los estudios
correspondientes. Una vez procesada, una receta no puede volver a procesarse.
Los estudios se dividen en distintas categorías, por ejemplo estudio de imagen, laboratorio, etc. Todos
los estudios tienen un nombre, una descripción y un estado para saber si fueron realizados. Se
simplifican los tipos de estudios a dos: Uno de rayos X (RX), el cual tiene también definida una zona que
describe sobre qué parte del cuerpo se realiza (tórax, abdomen, cráneo, etc). El otro es un estudio de
laboratorio que tiene definida una cantidad de items que serán analizados. Contemplar la posibilidad de
agregar otros tipos de estudios en el futuro.
Cuando se realiza un estudio, a partir del procesamiento de la receta, se envía el resultado al médico y
al paciente. A efectos prácticos, se pide que estos “envíos” sea una simple impresión en consola
notificando que se realiza.
Se solicita realizar lo siguiente:
a) Implementar todas las clases necesarias que se describen en el enunciado, incluyendo los
métodos necesarios para resolver las funcionalidades solicitadas.
b) Implementar el siguiente escenario (ver Anexo 1):
1) Crear un nuevo hospital llamado Pura Salud.
2) Registrar 3 profesionales.
3) Registrar 3 pacientes.
4) Cargar 5 recetas utilizando profesionales y pacientes de los puntos previos.
5) Procesar las primeras 4 recetas del punto previo.
6) Mostrar las recetas del sistema.
7) Mostrar sólo las recetas procesadas del sistema.
8) Mostrar pacientes con al menos 3 estudios realizados.
