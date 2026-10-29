# Cómo participar

Gracias por aportar. Este recetario crece con pull requests (PR): tú propones un cambio, alguien lo revisa y, si está bien, se fusiona.

## Tu primer PR: agrega tu nombre

1. Entra a [`COLABORADORES.md`](COLABORADORES.md) y da clic en el lápiz.
2. Agrega un renglón al final de la tabla: `| Tu nombre | Tu profesión | Tu ciudad |`.
3. Clic en **Commit changes…**, escribe un mensaje como `Agrega a Juan Pérez, abogado, Puebla` y elige **Create a new branch**.
4. Clic en **Propose changes** y luego en **Create pull request**.

## Comparte un prompt

1. Copia [`plantillas/prompt.md`](plantillas/prompt.md) en la carpeta que corresponda (`prompts/contabilidad`, `prompts/fiscal` o `prompts/legal`).
2. Nombra el archivo en minúsculas y con guiones: `conciliacion-de-nomina.md`.
3. Llena todas las secciones. El ejemplo va con **datos inventados**.
4. Abre tu PR con un título que diga qué aporta.

## Buenas prácticas

- **Un cambio por PR.** Si quieres agregar tres prompts, abre tres PR: se revisan más rápido.
- **Mensajes claros.** Verbo en presente y qué cambió: `Corrige tasa de retención de ISR en honorarios`, no `cambios`.
- **Nada de datos reales.** Ni RFC, ni nombres de clientes, ni montos, ni archivos de e.firma. Un PR con datos reales se cierra sin fusionar.
- **Texto plano.** Los prompts van en Markdown. No subas `.xlsx`, `.docx` ni `.pdf`.
- **Revisa lo que te dio la IA.** Si un prompt incluye criterios fiscales o legales, cita la fuente (artículo, regla miscelánea, criterio).

## Licencia

Al abrir un PR aceptas que tu aportación se publique bajo [CC BY 4.0](LICENSE), con crédito a tu nombre en `COLABORADORES.md`.
