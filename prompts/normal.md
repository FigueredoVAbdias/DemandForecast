CONTEXTO:
Responde los comentarios en español.
Tengo una dataframe llamado dfSales que tiene las ventas (Quantity) de varios items por dia.
INSTRUCCIONES:

Agrupar por item y agrupar por semana en formato ISO 8601 YYYY-Www.
Toma solo en cuenta solo semanas cerradas.
Crear una columna StartWeek que sera de tipo date y sera el lunes de cada semana.
Rellenar con ceros las semanas donde no hubo ventas para cada item.
Devolver un dataframe que tenga las siguientes columnas: ItemCode, StartWeek, Week, Quantity,