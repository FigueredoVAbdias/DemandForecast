CONTEXTO:
Responde los comentarios en español.
Tengo dos dataframes uno llamado dfWeekSalesOutliers que tiene las ventas (Quantity) de varios items por semanas, tengo otros dataframe llamado dfStock que tiene los stocks disponibles semanales de todos los items.
INSTRUCCIONES:
- Quiero que identifiques las semanas donde hubo no hubo ventas, es decir, Quantity igual a 0 y verificar si esa semana hubo Stock Disponible. En caso de que esa semana no hubo venta y tampoco Stock Disponible normalizar el Quantity por la mediana de la serie de cada item.
- Crear una columna llamada DemandStock que identificara esta condicion sera uno si no hubo venta y tampoco hubo stock y sera 0 si no cumple esta condicion.
- Devolver un dataframe con el ItemCode, StartWeek, Week, OriginalQuantity, NormalizedQuantity, AvailableStock y DemandStock.