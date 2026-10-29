# Revisar un CFDI antes de deducirlo

**Área:** fiscal
**Autor:** Israel Castro
**Probada con:** Claude

## Para qué sirve

Detectar errores comunes en un CFDI 4.0 recibido antes de registrarlo como deducible.

## Lo que necesitas antes

- El XML del CFDI (abre el archivo con un editor de texto y copia su contenido)
- Los datos fiscales de tu cliente: régimen y código postal

## El prompt

```text
Eres un contador mexicano que revisa CFDI 4.0. Revisa el XML que te pego y dime, en una tabla con columnas "Campo", "Valor" y "Observación":
- Si el RFC, nombre, régimen fiscal y código postal del receptor coinciden con estos datos: [RFC], [nombre], [régimen], [C.P.].
- El uso de CFDI y si es congruente con el gasto.
- Método de pago (PUE o PPD) y forma de pago, y si son congruentes entre sí.
- Si los impuestos trasladados y retenidos cuadran con la base.
Al final dime si ves algún motivo para pedir una corrección al proveedor. Si algo no lo puedes confirmar con el XML, dilo; no supongas.

XML:
[pegar aquí]
```

## Ejemplo (con datos inventados)

Un CFDI con método de pago PPD y forma de pago 03 (transferencia). La IA debe señalar que con PPD la forma de pago debe ser 99 (por definir) y que el pago se ampara con un complemento de pago.

## Revisa antes de usarlo

- La IA no consulta al SAT: valida el estatus del CFDI en el portal de verificación.
- Confirma los criterios contra la guía de llenado vigente del Anexo 20.
- Antes de pegar el XML, considera quitar datos que no hagan falta para la revisión.
