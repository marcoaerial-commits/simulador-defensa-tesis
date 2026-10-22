# Comisión Examinadora — Simulador de defensa de tesis

Aplicación web para practicar la defensa de la tesis **«El uso de sociedades offshore y su impacto en la evasión tributaria en Chile»** (Fabiana Rodríguez Valdés).

Un profesor de la comisión hace preguntas sobre cada lámina de la presentación, evalúa la respuesta según los puntos clave de una pauta, muestra la respuesta sugerida, repregunta y entrega una nota (escala 1,0–7,0).

## Cómo usarla
- Abrir la página publicada en GitHub Pages (o `index.html` directamente en el navegador).
- Modalidades: **Defensa simulada** (8 preguntas, énfasis en láminas 9, 10, 11 y 14), **Por lámina** y **Banco completo**.
- El profesor lee las preguntas y sus comentarios en voz alta (se puede desactivar); las respuestas se escriben en el cuadro de texto.
- **Modo IA opcional**: con una clave de la API de Anthropic, el profesor comenta la respuesta y formula repreguntas propias usando Claude. La clave queda solo en el navegador.

## Editar preguntas
Las preguntas están en `index.html`, en el arreglo `BANCO`. Cada pregunta tiene `q` (pregunta), `puntos` (ideas clave con palabras que las detectan), `modelo` (respuesta sugerida) y opcionalmente `re` (repregunta).
