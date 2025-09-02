---
Fecha de creación: 2025-09-01 21:58
Fecha de Modificación: 2025-09-01 21:58
tags: 
Tema:
---


## 📚 Idea/Concepto 
El mecanismo es un tipo de atención que permite al modelo evaluar la importancia de cada elemento de una secuencia con respecto a todos los demás. Este proceso se basa en calcular vectores de consulta (Q), clave (K) y valor (V) para cada palabra en la secuencia de entrada, se calcula una puntuación con producto escalar entre la consulta de una palabra y las claves de todas las demás palabras de la secuencia. Las puntuaciones se dividen por la raíz cuadrada de la dimensión de las claves para evitar valores muy grandes, luego con la función softmax se normalizan las puntuaciones para obtener pesos que indican cuánta atención debe prestar una palabra a las otras palabras en la secuencia. El resultado es una combinación ponderada de los valores V. Finalmente el modelo captura una variedad más amplia de información contextual con la atención multicabezal.

## 📌 Puntos Claves (Opcional)
- 

## 🔗 Connections
- [[Principios de IA]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 