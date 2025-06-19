# Caso de Estudio: Dashboard Ingresos y Descuentos — Salón de Belleza

## ES Español

**Rol:** Analista de Datos  
**Herramientas:** Microsoft Excel (tablas dinámicas, gráficos, fórmulas)

### Descripción del proyecto  
Realicé un estudio financiero integral para un salón de belleza, evaluando su desempeño económico y la efectividad de los descuentos aplicados. Se analizó una base de datos transaccional con operaciones diarias, que incluye ingresos por productos y servicios, descuentos, tipos de pago y gastos operativos. El objetivo fue identificar áreas rentables y oportunidades para optimizar precios, promociones y control de gastos, usando exclusivamente Excel.

### Objetivos del Proyecto  
- Evaluar la evolución de ingresos por tipo (productos vs. servicios).  
- Analizar el impacto de descuentos en ventas netas.  
- Estudiar hábitos de pago (efectivo vs. sin efectivo) y relación con total recaudado.  
- Identificar gastos significativos y su comportamiento mensual.  
- Detectar patrones semanales y mensuales en el negocio.

### Fuente de Datos  
Archivo: *Dashboard Ingresos y Descuentos Salón de Belleza.xls*  
Estructura:  
- Tipo: Producto o Servicio  
- Código de promoción: identificador del descuento aplicado  
- Operación: ingreso o gasto  
- Opción de pago: efectivo o sin efectivo  
- Categoría: tipo de producto o gasto  
- Fecha orden, Mes, Semana #, Día, Día de la semana  
- Costo de adquisición, Descuento ($), Descuento (%), Subtotal, Total

### Frecuencia de Actualización  
Datos actualizados cada 24 horas, a la medianoche UTC.

### Usuarios del Dashboard  
Gerente del salón de belleza  
Frecuencia de uso esperada: al menos una vez al día.

### Contenido y Visualizaciones del Dashboard  
| Elemento                                  | Filtro de fecha/hora | Filtro de país                      |
|-------------------------------------------|---------------------|-----------------------------------|
| Gráfico "Historial de tendencias"         | ✅ Ajuste de período | ✅ Afecta todos los gráficos      |
| Gráfico "Historial de tendencias" (%)     | ✅                   | ✅                                |
| Gráfico "Tendencias por país"              | ✅                   | Solo si se seleccionan múltiples países |
| Tabla "Tendencias por país y categoría"   | ✅                   | ✅ (Celdas resaltadas por valor)  |

### Análisis Realizado  
- Ingresos por categoría: productos más vendidos vs servicios más rentables.  
- Comparativa ingresos con y sin descuento.  
- Distribución de operaciones por tipo de pago.  
- Análisis de gastos por categoría (alquiler, marketing, utilidades, etc.).  
- Tendencias semanales y mensuales del total recaudado.  
- Identificación de días con mayor y menor facturación.

### Insights Clave  
- Servicios como “corte por estilista experto” y “corte y peinado” generaron mayores ingresos.  
- Productos (champú, gel) con alta frecuencia de descuentos, impactando márgenes.  
- 60% de transacciones sin efectivo, sugiriendo monitoreo de comisiones asociadas.  
- Mayor volumen de ingresos concentrado en fines de semana, especialmente sábados.  
- Gastos como “renovación” y “marketing” con picos en meses específicos, afectando flujo de caja.

### Resultados y Beneficios  
- Replantear política de descuentos en productos para mejorar márgenes.  
- Crear campañas promocionales en días con menor afluencia (martes y miércoles).  
- Monitorear crecimiento de pagos sin efectivo para negociar comisiones.  
- Establecer presupuesto mensual para gastos variables (marketing, renovación).  
- Automatizar análisis en Excel para actualizaciones rápidas mensuales.

---

# Case Study: Dashboard Revenue and Discounts — Beauty Salon

## US English

**Role:** Data Analyst  
**Tools:** Microsoft Excel (pivot tables, charts, formulas)

### Project description  
Conducted a comprehensive financial study for a beauty salon to evaluate economic performance and effectiveness of discounts. Analyzed a transactional database with daily operations including product and service revenue, discounts, payment types, and operating expenses. The goal was to identify the most profitable areas and optimize pricing, promotions, and expense control using Excel.

### Project Objectives  
- Evaluate revenue evolution by type (products vs. services).  
- Analyze impact of discounts on net sales.  
- Study payment habits (cash vs. non-cash) and relation to total revenue.  
- Identify significant expenses and monthly behavior.  
- Detect weekly and monthly patterns in business behavior.

### Data Source  
File: *Beauty Salon Revenue and Discounts Dashboard.xls*  
Structure:  
- Type: Product or Service  
- Promotion code: discount identifier  
- Operation: income or expense  
- Payment option: cash or non-cash  
- Category: product or expense type  
- Order date, Month, Week #, Day, Day of week  
- Acquisition cost, Discount ($), Discount (%), Subtotal, Total

### Update Frequency  
Data updated every 24 hours, midnight UTC.

### Dashboard Users  
Beauty salon manager  
Expected frequency of use: at least daily.

### Dashboard Content and Visualizations  
| Element                                  | Date/time filter   | Country filter                    |
|------------------------------------------|-------------------|---------------------------------|
| “Trend History” chart                     | ✅ Adjustable period | ✅ Affects all charts           |
| “Trend History” chart (%)                 | ✅                 | ✅                               |
| “Trends by country” chart                 | ✅                 | Only if multiple countries selected |
| “Trends by country and category” table   | ✅                 | ✅ (Cells highlighted by value) |

### Analysis Performed  
- Revenue by category: best-selling products vs. most profitable services.  
- Comparison of revenue with and without discounts.  
- Distribution of transactions by payment type.  
- Expense analysis by category (rent, marketing, utilities, etc.).  
- Weekly and monthly total revenue trends.  
- Identification of highest and lowest turnover days.

### Key Insights  
- Services like “haircut by expert stylist” and “cut and style” generated highest revenue.  
- Products (shampoo, gel) frequently discounted, impacting margin.  
- 60% of transactions paid non-cash, indicating need to monitor associated fees.  
- Highest revenue concentrated on weekends, especially Saturdays.  
- Expenses like “renovation” and “marketing” peaked in certain months, affecting cash flow.

### Results and Benefits  
- Rethink product discount policy to improve margins.  
- Create promotions on low-traffic days (Tuesdays, Wednesdays).  
- Monitor non-cash payment growth to negotiate fees.  
- Set monthly budget for variable expenses like marketing and renovation.  
- Automate part of the Excel analysis for quick monthly updates.
