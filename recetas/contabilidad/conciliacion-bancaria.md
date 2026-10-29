# Conciliación bancaria contra auxiliar

**Área:** contabilidad
**Autor:** Israel Castro
**Probada con:** Claude, ChatGPT

## Para qué sirve

Encontrar las partidas que no cuadran entre el estado de cuenta del banco y el auxiliar de bancos del mes.

## Lo que necesitas antes

- El estado de cuenta del mes, exportado a CSV o copiado como texto
- El auxiliar contable de la cuenta de bancos del mismo periodo

## El prompt

```text
Actúa como auxiliar contable. Te voy a dar dos listas de movimientos del mes de [mes]:
1. El estado de cuenta bancario.
2. El auxiliar contable de la cuenta [número de cuenta contable].

Haz la conciliación:
- Empareja los movimientos por importe y fecha (tolerancia de 3 días).
- Lista en una tabla los movimientos del banco que no están en contabilidad.
- Lista en otra tabla los movimientos de contabilidad que no están en el banco.
- Al final, muestra la conciliación: saldo según banco, más y menos partidas en tránsito, saldo según contabilidad.
No inventes movimientos. Si un emparejamiento es dudoso, márcalo como "por revisar".

Estado de cuenta:
[pegar aquí]

Auxiliar:
[pegar aquí]
```

## Ejemplo (con datos inventados)

Banco: depósito del 3 de marzo por $11,600.00 sin registro en el auxiliar. La IA debe listarlo como "en banco, no en contabilidad" y sugerir revisar si falta registrar el cobro de una factura.

## Revisa antes de usarlo

- Comprueba la suma final a mano: la IA puede equivocarse en la aritmética con listas largas.
- Verifica los emparejamientos de importes repetidos (dos pagos iguales en fechas cercanas).
