# servicio_de_transporte
Análisis a la eficiencia del servicio de transporte entre dos ciudades.

1.	Introducción

    a.	Compañía

      La compañía de transporte público provee servicio diario a la comunidad A. Todos los días ofrece viajes de la comunidad A a la comunidad B. La compañía transporta un promedio diario de 2,600 personas que hacen un recorrido ida-vuelta. 
      La comunidad A está inconforme debido a los últimos incrementos en el precio del servicio. Por lo tanto, la compañía de transporte quiere evitar incrementos en el precio del servicio, de manera que buscan revisar sus horarios de servicio para conocer si el servicio que proveen es óptimo y así, poder evitar incrementos al precio del servicio de manera frecuente.

    b.	Objetivos

       •	Encontrar el número de viajes adecuados por día

2.	Análisis

    a.	Datos

      Los datos fueron provistos por la compañía de transporte en archivos diarios de Excel. Una muestra de 15 días son los que aquí se analizan. Los datos son proporcionados en un formato que no es adecuado para el análisis, así que extraer y organizar los datos de manera apropiada para el análisis es la primera tarea. Los datos no están duplicados, 15 viajes tienen datos colocados en un lugar que no corresponde. Una vez solucionado esto, es posible avanzar al análisis.
    b.	Análisis
      Con los datos proporcionados, se obtienen las primeras gráficas exploratorias.

      ![Pasaje diario](https://user-images.githubusercontent.com/118465839/227619934-05906df8-b264-4722-a59b-706e88072d08.png)

      Se observa que en los días lunes se tiene la mayor cantidad de usuarios. Y los días domingos son los días en los que la menor cantidad de usuarios usa el servicio.
    
      ![Promedio de usuarios por día](https://user-images.githubusercontent.com/118465839/227620056-00415b64-e717-49a6-9afd-6ee5206f5366.png)

      La gráfica anterior muestra un promedio de usuarios por día de la semana. El patrón de uso es el apreciado anteriormente. Lunes es el día con mayor demanda, mientras que el domingo es el día con menor demanda.
    
      ![Vueltas diarias](https://user-images.githubusercontent.com/118465839/227620137-02de6e2e-e8f3-4d6b-b2ef-669af2cd2bb4.png)

      La oferta del servicio, es decir, el número de viajes realizados por la compañía, tanto de ida como de vuelta, es el que se aprecia en la gráfica. Es congruente con cómo se comparta el número de usuarios durante la semana.
    
      ![Promedio de pasajes por día](https://user-images.githubusercontent.com/118465839/227620237-68f7b047-715b-45ed-b710-313a4c2116a3.png)

      En este gráfico que representa el promedio de usuarios por cada viaje realizado, se aprecia un hecho alarmante. En la gráfica se aprecia una línea de referencia en color rojo, que representa la capacidad de pasajes de cada autobús. Cada barra indica el porcentaje de la capacidad del autobús que está siendo utilizado, en promedio, en cada viaje. Los autobuses están siendo usados, como máximo, en un 67% de su capacidad total. 
    
      ![Análisis por hora A](https://user-images.githubusercontent.com/118465839/227620297-5a22887b-a4bc-4735-91ac-188921c3cce9.png)
      ![Análisis por hora B](https://user-images.githubusercontent.com/118465839/227620305-80d5289b-ef77-4841-8191-d575589ac9de.png)

      En los dos gráficos se observa la razón. El gráfico está dividido por hora del día y viajes de ida (A) y vuelta (B). Existen horarios donde la capacidad de transporte de viajes realizados excede la demanda del servicio. 
    
      ![Ajuste de viajes A](https://user-images.githubusercontent.com/118465839/227620409-1fcb0907-5d19-4011-a8f2-1172fa9035c6.png)
      ![Ajuste de viajes B](https://user-images.githubusercontent.com/118465839/227620419-92380771-221a-4fe7-93d0-460906100221.png)

  
      Se vuelve evidente que el servicio ofrecido excede la demanda y que un ajuste en la cantidad de viajes en algunos horarios es necesario. Apegándose a los datos, las gráficas arriba representan un ajuste bastante preciso del servicio ofrecido por la compañía. 

      ![Comparación viajes realizados y viajes necesarios](https://user-images.githubusercontent.com/118465839/227620500-f2fe9383-4c18-4d63-9449-c3ec4635edda.png)

      La comparación del servicio ofrecido y del servicio necesario es representado en el gráfico anterior. Los ajustes van de una reducción de 48% en el número de viajes el día domingo, hasta un 70% para los días lunes. 

3.	Resultado

    Después de presentar los hallazgos en los datos y presentar los ajustes requeridos con los socios de la compañía, se presentaron algunas restricciones a la hora de ajustar los horarios, que llevaron a una reducción más conservadora del 20% en el número de viajes ofrecidos por la compañía. 
Los días lunes, de 320 viajes, en promedio, se redujeron a 260 viajes; de martes a sábado, la reducción fue de 260 a 216 viajes; el único día que resultó sin cambios, fue el día domingo, quedando con un promedio de 77 viajes.

    ![Ajuste 20](https://user-images.githubusercontent.com/118465839/227620545-265c40d7-e4c6-43fc-9741-d79a71e0878d.png)
