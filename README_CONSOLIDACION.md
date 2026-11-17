# Budgy – Consolidación sobre V11.2 Ajustes 01 a 06

Base exacta: `Budgy_V11.2_ajustes_01_a_06.zip`.

Cambios incorporados en esta entrega de trabajo:
- Se aumentó el tamaño del wordmark del encabezado y se conserva la Y azul.
- Se retiró de Ajustes la sección de personalización de colores y se fija la paleta azul Budgy.
- Se agregó una primera pantalla de Finanzas accesible desde Ajustes, con registro local de préstamos otorgados, créditos recibidos e inversiones, tasa mensual/anual efectiva, plazo, modalidad de cálculo y estimación de cuota/intereses/total.

Pendiente de completar antes de considerar esta versión como implementación íntegra de los ajustes 07–20:
- Rediseño completo de las pantallas Presupuesto y análisis como vistas independientes, con presupuesto de ingreso y gasto, controles de disponibilidad y validaciones de categorías/conceptos.
- Integración de las operaciones financieras con Presupuesto y Movimientos, registro separado de capital e intereses, cuotas, abonos, pagos/cobros y calendario.
- Retirada completa de las opciones antiguas de cuentas por cobrar/pagar y ajuste de todos los filtros/estadísticas de Movimientos.
- QA funcional completo.

La compilación no pudo verificarse en este entorno porque la instalación de dependencias quedó incompleta y TypeScript no encontró definiciones de tipos (`@types/react`, `@types/react-dom` y otras). Esta entrega debe tratarse como versión de trabajo, no como release validada.
