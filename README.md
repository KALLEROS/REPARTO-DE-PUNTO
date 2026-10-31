# Reparto de Punto

Calculadora de cierre para los meseros de Sala de Despecho: captura la venta de cada mesero y calcula el punto (9.5% de la venta) y lo que le toca a cada área.

| Área | % de la venta |
|---|---|
| Gerencia | 4.3% |
| Barra | 1.7% |
| CAJA | 1.5% |
| Cocina | 1.1% |
| Host | 0.9% |
| **Punto total** | **9.5%** |

Son dos apps:

| App | Para qué | Link |
|---|---|---|
| **Captura** (principal) | Quien hace el cierre captura las ventas, hace el corte y lo manda. | https://kalleros.github.io/REPARTO-DE-PUNTO/ |
| **Visualización** | Solo para ver los cortes: venta, punto, reparto por área y aportación de cada mesero, sin nombres. No se puede editar nada. | https://kalleros.github.io/REPARTO-DE-PUNTO/visualizacion-reparto-de-punto/ |

## Usar la captura en el iPhone

1. Abre la app en Safari: https://kalleros.github.io/REPARTO-DE-PUNTO/
2. Toca **Compartir** (cuadro con flecha) → **Agregar a inicio**.

Ya instalada, abre aunque no haya señal. Los datos se guardan solo en ese teléfono.

## Cierre del día

1. Captura la venta de cada mesero. Para quitar a uno, la app pide confirmación.
2. **Hacer corte**: el día se guarda en el **Historial de cortes** (con nombres, solo en ese teléfono) y la lista queda en limpio. Un corte antes de las 8 a. m. cuenta para la jornada del día anterior.
3. Al terminar, la app ofrece **Enviar por WhatsApp**: manda un link a la app de visualización con ese corte y los 6 anteriores, sin nombres de meseros. Cualquier corte del historial se puede volver a enviar.

## Visualización

Quien recibe el link lo abre y el corte aparece; se va guardando en su teléfono como historial. No hace falta instalarla: conviene abrir siempre los links desde WhatsApp. En el iPhone, si se agrega a inicio, abre en Safari para que vea los mismos cortes que llegaron por link.

## Versiones anteriores

- Rama `BORRADOR`: la versión anterior (crema/madera, sin el nombre del bar).
- Rama `ESTETICA-COLORES`: prueba con los colores de marca del bar.
