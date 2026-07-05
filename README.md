# 🍄 FungiApp — Trazabilidad de cultivo + Microdosis

Tablero de trazabilidad para cultivo de investigación de *Psilocybe cubensis* (cepas albinas **JF** · Jack Frost y **SIF** · Super Ice Flower) y seguimiento de pacientes con microdosis.

Es una **app de un solo archivo** (`Trazabilidad_Cultivo.html`): se abre directo en el navegador, sin servidor ni dependencias, y funciona offline.

## Módulos

- **Cultivo** — pipeline de 5 etapas: placas Petri → colonización de grano → incubación en sustrato (bulk) → fructificación → cosecha. Con efectividad (placas sanas, grano viable, rendimiento fresco/seco) y bitácora.
- **Microdosis** — seguimiento de pacientes con protocolo Fadiman personalizado (20 tomas en 8 semanas: semanas impares Lun/Mié/Vie, pares Mar/Jue). Calendario de tomas clickeable, progreso y observaciones. Editable desde la app.

## Uso

Abrir `Trazabilidad_Cultivo.html` en Chrome (o cualquier navegador).

- **Datos de cultivo:** se editan en el bloque `DATOS` dentro del `<script>` del archivo.
- **Datos de pacientes:** se editan directamente en la interfaz (vista Microdosis) y se guardan en el `localStorage` del navegador. Usar el botón *Exportar* para respaldar.

## Notas

Cepas albinas verdaderas, sin esporas viables — propagación solo en medio sólido (agar).
