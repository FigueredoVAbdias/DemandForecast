CONTEXTO:
Responde los comentarios en español.
Tengo una dataframe llamado df_oinm que tiene los movimientos de inventario de varios items por dia.
INSTRUCCIONES:
- Agrupar por item y agrupar por semana en formato ISO 8601 YYYY-Www.
- Crear una columna NetMovement que calcule el movimiento neto de inventario por semana de cada item.
- Crear una columna AvailableStock que calcule el saldo de stock disponible despues de sumar el saldo de la semana anterior al MovimientoNeto para cada item.
- Crear una columna StartWeek que sera de tipo date y sera el lunes de cada semana.
Crea una columna StockOut que indicara 1 si el AvailableStock es igual a 0 y sera 0 si el AvailableStock es mayor que 0.
- Rellenar con ceros las semanas donde no hubo movimientos de inventario y para el Stock disponible de estas semanas sin movimientos tomar el StockDisponible anterior mas proximo.
- Devolver un dataframe que tenga las siguientes columnas: ItemCode, StartWeek, Week, InQty, OutQty, NetMovement, AvailableStock y Stockout