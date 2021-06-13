# TP7 Back

### Consigna Spring Boot parte 1 (Calculador para calendario de siembra)

Dado el calendario de siembra que se indica en la siguiente tabla adjunta, se pide crear un recurso el cual cumpla con lo siguiente:

-  Tome los siguientes parámetros:
 - Especie
 - Ancho del área de sembrado (metros)
 - Largo del área de sembrado (metros)
-  Debe devolver en su respuesta un JSON con los siguientes datos:
 - Especie
 - Cantidad de plantines posibles a sembrar en dicha área
 - Fecha estimada de cosecha
-  Si la especie no figura en el listado debe devolverse un mensaje `"No se encontraron datos de dicha especie"`
-  Si la fecha en que se ejecuta esta consulta está fuera de la fecha de siembra debe devolverse el mensaje: `"La especie consultada está fuera de calendario"`
-  Si el ancho y/ó largo del área de sembrado en metros es negativo debe devolverse el mensaje: `"Los datos ingresados son incorrectos"`

Especie |	Distancia entre plantas (cm)|	Fecha de siembra o plantación|	Días a cosecha
------- | --------------------------- | ---------------------------- | ---------------
Acelga | 20	| Todo el año excepto enero y julio	| 80
Ajo | 15 | Marzo a Mayo | 270
Apio | 25 | Setiembre a Diciembre, Enero a Marzo | 150
Esparragos | 30	| Agosto a Setiembre	| 1825
Espinacas | 10 | Febrero a Junio | 90
Lechuga | 20 | Agosto a Diciembre | 90
Papa | 30	| Agosto a Setiembre, Enero a Febrero	| 150
Pimiento | 45	| Setiembre	| 200
Rabanito | 5 | Febrero a Junio, Setiembre a Diciembre | 40
Remolacha | 10 | Agosto a Diciembre, Marzo a Junio | 130
