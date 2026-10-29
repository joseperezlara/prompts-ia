# Revisar un contrato de prestación de servicios

**Área:** legal
**Autor:** Israel Castro
**Probada con:** Claude

## Para qué sirve

Una primera lectura de un contrato de prestación de servicios profesionales para encontrar huecos antes de revisarlo a fondo.

## Lo que necesitas antes

- El contrato en texto (si está en Word, cópialo y pégalo)
- Saber a qué parte representas: prestador o cliente

## El prompt

```text
Eres abogado en México y representas a [el prestador / el cliente]. Revisa este contrato de prestación de servicios profesionales (Código Civil Federal, artículos 2606 a 2615, o el código civil local de [estado]).

Entrégame una tabla con columnas "Cláusula", "Riesgo para mi representado", "Sugerencia de redacción". Revisa en especial:
- Objeto y alcance de los servicios: ¿está claro qué incluye y qué no?
- Honorarios, forma de pago, facturación (CFDI) y retenciones de ISR e IVA cuando aplique.
- Confidencialidad y protección de datos personales.
- Vigencia, terminación anticipada y penas convencionales.
- Que no se configure una relación laboral encubierta.
- Jurisdicción y solución de controversias.

Cita la cláusula exacta que comentas. Si algo depende de un criterio que no puedes confirmar, dilo.

Contrato:
[pegar aquí]
```

## Ejemplo (con datos inventados)

Una cláusula dice "El prestador estará a disposición del cliente de lunes a viernes de 9 a 18 horas en sus oficinas". La IA debe señalar el riesgo de que se interprete como subordinación laboral y sugerir redactarlo por entregables.

## Revisa antes de usarlo

- La IA no sustituye la revisión del abogado responsable.
- Verifica los artículos citados contra el código aplicable al contrato.
- Quita nombres y datos de las partes antes de pegar el contrato.
