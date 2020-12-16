# Cambiar-Temp-UNITARIOS

El Script busca de forma recursiva por el directorio en busca de archivos del tipo *UNITARY****.DAT* y una vez los encuentra los abre uno a uno para modificar la columna de temperatura *Temp*.

El interior de los archivos debe ser de este tipo:
<!-- language: lang-none -->
+----------+----------+----------+----------+----------+----------+----------+----------+  
| Column1  |  Column2 | Column3  |  Column4 |  Column5 |  Column6 |  Column7 |   Temp   |  
+----------+----------+----------+----------+----------+----------+----------+----------+  
| PRE-CHK2 |     0.00 |     0.00 |     0.00 |     0.00 |     0.00 | -11057.9 |     10.0 |  
| PRE-CHK3 |     0.00 |     0.00 |     0.00 |     0.00 |     0.00 |  13342.7 |      0.0 |  
| PRE-CHK4 |     0.00 |     0.00 |     0.00 |     0.00 |     0.00 |   8857.4 |     -5.0 |  
| PRE-CHK5 |     0.00 |     0.00 |     0.00 |     0.00 |     0.00 | -11053.1 |     20.0 |  
| PRE-CHK6 |     0.00 |     0.00 |     0.00 |     0.00 |     0.00 |  13364.3 |    -15.0 |  
+----------+----------+----------+----------+----------+----------+----------+----------+
