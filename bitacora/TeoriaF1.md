La medida F1 (o F1-score) es una métrica de evaluación usada en problemas de clasificación, especialmente cuando hay clases desbalanceadas (es decir, unas aparecen mucho más que otras).

🧮 ¿Qué mide la F1?
Es el promedio armónico entre:

Precisión (precision): cuántos de los que clasificaste como positivos lo son realmente.

Sensibilidad (recall o recobrado): cuántos de los positivos reales fuiste capaz de encontrar.

📐 Fórmula:
F1
=
2
⋅
precision
⋅
recall
precision
+
recall
F1=2⋅ 
precision+recall
precision⋅recall
​
 
✅ ¿Por qué usar F1?
Porque equilibra precisión y recall, lo que es útil cuando:

No quieres muchos falsos positivos (alta precisión).

No quieres dejar pasar casos reales (alta recall).

Por ejemplo, en diagnóstico médico, una F1 alta indica que detectas bien las enfermedades sin sobrediagnosticar demasiado.

📊 Ejemplo:
Supón que estás clasificando pacientes con fibrilación auricular (AF) en un ECG:

Predicho AF	Predicho No-AF
Real AF	80	20
Real No-AF	10	90

Precision = 80 / (80 + 10) = 0.89

Recall = 80 / (80 + 20) = 0.80

F1-score ≈ 2 × (0.89 × 0.80) / (0.89 + 0.80) ≈ 0.84

📌 ¿Cuándo no usar F1?
Si el costo de falsos positivos y negativos es muy diferente (entonces se prefieren métricas ajustadas).

Si el dataset está muy balanceado, puedes usar simplemente accuracy (precisión global).

¿Quieres que te muestre cómo calcular F1 en Python con sklearn?
