# Recolección de Datasets

## Objetivo 
Predecir la probabilidad de que un cliente cancele una reservación con el objetivo de reducir la pérdida de ingresos de los hoteles. Al poder predecir podemos plantear estrategias para reducir el porcentaje de cancelación.
## Metodología de recolección 
Los datasets se buscaron en la plataforma Kaggle .
### Hotel bookings Dataset
Especificamente el conjunto principal de Hotel bookings: 
            https://www.kaggle.com/datasets/mathsian/hotel-bookings
Este dataset contiene información de las reservaciones de dos hoteles en Portugal. El hotel “Resort Hotel” en Algarve y el hotel “City Hotel” en Lisboa. En este dataset encontramos 119, 390 reservaciones con fechas desde 1 de Julio de 2015 y 31 de Agosto de 2017. Cada fila representa una reservación. 
El dataset presentado contiene el dataset original y una versión simplificada del mismo con solo 23 columnas. Y una versión aún más simplificada de 10 columnas como ayuda para el análisis.
Debido a que los datos son reales, todos los elementos pertenecientes al hotel y los que identifican al cliente fueron eliminados.
Los datos se encuentran en formato comma separated values (csv). 
### Hotel Dataset
Se encontró también otro conjunto en Hotel Dataset:
        https://www.kaggle.com/datasets/mashkuratualhassan/hotel-dataset
Presenta características similares al anterior, pero en este las reservaciones se encuentran dentro del periodo de 3 años entre 2018 y 2020. 
Los datos se encuentran en formato Excel (xlsx). 
### Hotel booking demand
Otro dataset similar 
Los datos son originarios del artículo “ Hotel Booking Demand Datasets” por Nuno Antonio, Ana Almeida y Luis Nunes para Data in Brief, Volumen 22, febrero 2019.
Los datos fueron descargados y limpiados por Thomas Mock y Antoine Bichat
    https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand
Este dataset está en formato csv y será convertido con la ayuda de la librería pandas a json. 