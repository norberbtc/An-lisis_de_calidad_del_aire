# An-lisis_de_calidad_del_aire
# Solución 1: Cargar datos demográficos
# - Utiliza pandas para cargar datos demográficos desde una URL.
# - Realiza limpieza de datos eliminando columnas y duplicados.

# Solución 2: Cargar calidad del aire para ciudades
# - Crea una tabla para almacenar datos de calidad del aire.
# - Utiliza una API externa para obtener datos de calidad del aire para cada ciudad en el conjunto.
# - Procesa la respuesta de la API y agrega los datos a la tabla de calidad del aire.
# - Crea una base de datos SQLite y carga las tablas de datos demográficos y calidad del aire.

# Tests
# - Solución 1 Test: Verifica que la función de carga de datos demográficos selecciona correctamente ciertas filas.
# - Solución 2 Test: Verifica que la función de carga de calidad del aire genera resultados esperados para las primeras 10 ciudades.
