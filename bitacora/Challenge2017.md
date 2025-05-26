PHYSIONET / COMPUTING IN CARDIOLOGY CHALLENGE 2017


El PhysioNet / Computing in Cardiology Challenge 2017 es una competencia internacional organizada por PhysioNet y Computing in Cardiology (CinC) que se centró en el análisis automático de registros de fonocardiogramas (PCG), es decir, sonidos cardíacos, no señales de ECG.

 Tema del Challenge 2017
- Objetivo:
Clasificar automáticamente sonidos cardíacos como normales o anormales a partir de fonocardiogramas grabados con estetoscopios electrónicos.

- ¿Qué tipo de datos se usaron?

Registros de fonocardiogramas (PCG):

  1. Capturados por dispositivos portátiles en entornos clínicos y comunitarios.

  2. De diferentes partes del cuerpo (apex, base, pulmonar...).

  3. A veces con múltiples canales.

Formato:

  1. Archivos .wav con los sonidos cardíacos.

  2. Archivos .txt con etiquetas (normal, abnormal, o unsure).


Dataset principal:
Disponible en PhysioNet:

"PhysioNet/CinC Challenge 2016 and 2017 Heart Sound Recordings"

Enlace directo: https://physionet.org/content/challenge-2016/1.0.0/

Aunque el challenge fue en 2017, los datos provienen de la edición 2016 y fueron reutilizados con nuevo enfoque para 2017.


- ¿Cuál era el reto?
Crear un algoritmo automático que, al recibir una grabación de sonido cardíaco, dijera si el corazón era:


Normal:	Latido sin anomalías
Abnormal:	Soplidos, ruidos extraños
Unsure:	Calidad insuficiente para juzgar

Y además se evaluaba el desempeño del modelo bajo incertidumbre clínica, por eso se permitía decir “unsure” con penalización leve.

- Importancia clínica:
Los sonidos cardíacos son una herramienta barata y efectiva para detectar enfermedades valvulares y otras afecciones sin equipos costosos. Este challenge ayudó a avanzar el uso de IA en diagnóstico auscultatorio.

- Evaluación:
  1. Sensibilidad (recall) y especificidad.

  2. Penalización por clasificaciones erróneas.

3. Se promovía el balance entre falsos positivos y negativos.
