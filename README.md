# Prompts de IA para contadores y abogados

Prompts probados para trabajar con inteligencia artificial en el despacho y en el bufete: conciliaciones, revisión de CFDI, contratos y lo que la comunidad vaya sumando.

Los programadores crecieron compartiendo su trabajo en público. Este repositorio es el intento de hacer lo mismo entre contadores y abogados: lo que a ti ya te funciona, a alguien más le ahorra la tarde.

## Qué hay aquí

| Carpeta | Qué contiene |
|---|---|
| [`prompts/contabilidad`](prompts/contabilidad) | Conciliaciones, cierres, papeles de trabajo |
| [`prompts/fiscal`](prompts/fiscal) | CFDI, declaraciones, revisiones ante el SAT |
| [`prompts/legal`](prompts/legal) | Contratos, escritos, revisión de cláusulas |
| [`plantillas/prompt.md`](plantillas/prompt.md) | El formato para proponer un prompt nuevo |
| [`COLABORADORES.md`](COLABORADORES.md) | Quiénes han aportado |

Cada prompt es un archivo Markdown (`.md`): texto plano, así Git muestra exactamente qué cambió entre una versión y otra.

## Participa con un pull request

No necesitas saber programar ni usar la terminal. Todo se hace desde el navegador:

1. Abre [`COLABORADORES.md`](COLABORADORES.md) y da clic en el lápiz (**Edit this file**).
2. Agrega un renglón con tu nombre, tu profesión y tu ciudad.
3. Da clic en **Commit changes…** y escribe un mensaje claro, por ejemplo: `Agrega a Ana López, contadora, Monterrey`.
4. GitHub crea tu copia (fork) y te propone abrir el pull request: clic en **Create pull request**.

Cuando te sientas cómodo, comparte un prompt: copia [`plantillas/prompt.md`](plantillas/prompt.md), llénala y abre otro pull request. Los detalles están en [CONTRIBUTING.md](CONTRIBUTING.md).

## La regla que no se rompe

**Nunca subas datos reales de clientes.** Ni RFC, ni nombres, ni montos reales, ni archivos de e.firma (`.cer`, `.key`), ni contraseñas. Usa ejemplos inventados. Un repositorio público lo puede leer cualquiera, y lo que se sube queda en la historia aunque después se borre.

## Licencia

El contenido está bajo [Creative Commons Atribución 4.0 Internacional (CC BY 4.0)](LICENSE): puedes usarlo, adaptarlo y compartirlo, incluso con fines comerciales, siempre que cites la fuente. Al abrir un pull request aceptas que tu aportación se publique con esta misma licencia.

Los prompts son un punto de partida, no asesoría profesional: revisa siempre lo que te entrega la IA antes de usarlo con un cliente.
