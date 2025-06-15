# Caso-de-Estudio-Dashboard-Ingresos-y-Descuentos-Salon-de-Belleza-
Descripción del proyecto:

Como analista de datos, llevé a cabo un estudio financiero completo para un salón de belleza con el objetivo de evaluar su desempeño económico y la efectividad de los descuentos otorgados. Se analizó una base de datos transaccional con operaciones diarias, incluyendo ingresos por productos y servicios, descuentos aplicados, tipos de pago, y gastos operativos.

Este análisis buscó proporcionar una visión clara de las áreas más rentables del negocio y detectar oportunidades de optimización en precios, promociones y control de gastos, utilizando exclusivamente herramientas de Excel.

## Objetivos del Proyecto
Evaluar la evolución de ingresos por tipo (productos vs servicios).

Analizar el impacto de los descuentos en las ventas netas.

Estudiar los hábitos de pago (efectivo vs sin efectivo) y su relación con el total recaudado.

Identificar los gastos más significativos y su comportamiento mensual.

Detectar patrones semanales y mensuales en el comportamiento del negocio.

## Fuente de Datos
Archivo: Dashboard Ingresos y Descuentos Salón de Belleza.xls

Estructura de la base de datos:

Tipo: Producto o Servicio

Código de promoción: Identificador del descuento aplicado

Operación: Ingreso o Gasto

Opción de pago: Efectivo o Sin efectivo

Categoría: Tipo de producto o gasto

Fecha de orden, Mes, Semana #, Día, Día de la semana

Costo de adquisición, Descuento ($), Descuento (%), Subtotal, Total

## Frecuencia de Actualización
Datos actualizados cada 24 horas, a la medianoche UTC.

## Usuarios del Dashboard
Usuarios objetivo: gerente del salón de belleza

Frecuencia de uso esperada: al menos una vez al día

## Contenido y Visualizaciones del Dashboard



Título y descripción del dashboard	Filtro de fecha y hora	Filtro de país
Gráfico "Historial de tendencias": tendencias de videos divididas por tiempo y categoría (valores absolutos, gráfico de área)	✅ Se puede ajustar el período de análisis por fecha/hora	✅ El filtro afecta todos los gráficos
Gráfico "Historial de tendencias" (%): proporción de categorías por fecha (gráfico de área con porcentajes)	✅	✅
Gráfico "Tendencias por país": distribución de tendencias por país (gráfico de pastel con valores relativos)	✅	Aplicable solo si se seleccionan múltiples países
Tabla "Tendencias por país y categoría": categorías y países cruzados, resaltado por valores absolutos	✅	✅ (Celdas resaltadas según intensidad de valores)

## Herramientas Utilizadas
Microsoft Excel para limpieza, análisis y visualización de datos con tablas dinámicas, gráficos y fórmulas.

## Análisis Realizado con el Dashboard
Análisis de ingresos por categoría: productos más vendidos vs servicios más rentables.

Comparativa de ingresos con y sin descuento aplicado.

Distribución de operaciones por tipo de pago.

Análisis de gastos por categoría (alquiler, marketing, utilidades, etc.).

Tendencias semanales y mensuales del total recaudado.

Identificación de días con mayor y menor facturación.

## Insights Clave
Los servicios como “corte de cabello por estilista experto” y “corte y peinado” generaron los mayores ingresos.

Los productos (como champú y gel) presentaron una alta frecuencia de descuentos, lo que impactó el margen.

El 60% de las transacciones fueron pagadas sin efectivo, lo cual sugiere que se deben monitorear las comisiones asociadas a este método.

El mayor volumen de ingresos se concentra en fines de semana, especialmente los sábados.

Gastos como “obras de renovación” y “marketing” tuvieron picos en meses específicos, lo cual afecta el flujo de caja.

## Resultados y Beneficios
Replantear la política de descuentos en productos para mejorar el margen de ganancia.

Crear campañas promocionales los días con menor afluencia (martes y miércoles).

Monitorear el crecimiento de pagos sin efectivo para negociar comisiones más bajas con proveedores.

Establecer un presupuesto mensual para gastos variables como marketing y renovación.

Automatizar parte de este análisis en Excel para actualizaciones mensuales rápidas.
