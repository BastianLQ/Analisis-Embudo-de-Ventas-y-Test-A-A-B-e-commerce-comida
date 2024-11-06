# Analisis-Embudo-de-Ventas-y-Test-A-A-B-e-commerce-de-comida
__Proyecto de análisis a la plataforma de delivery Instacart, análisis exploratiorio y visualización de datos__

<image src="https://github.com/BastianLQ/Analisis-Instacart/blob/main/N3.jpg" alt="Collage de gráficos">

_Fragmentos del notebook, para ver proyecto completo hacer click [aquí](https://portfoliodabastianlopez.on.drv.tw/Portafolio/An%C3%A1lisis%20Instacart.html)_

## Descripción del Proyecto
Se investigó el comportamiento de usuario para la aplicación de una empresa que comercializa productos alimentarios.

Primero, se estudió el embudo de ventas para descubrir cómo los usuarios y las usuarias llegan a la etapa de compra. Para ello se formularon preguntas relacionadas al comportamiento de los clientes durante su paso por el embudo.

Luego se analizaron los resultados de un test A/A/B, realizado debiido a que al equipo de diseño propuso cambiar las fuentes de toda la aplicación, sin embargo, la gerencia temió que los usuarios y las usuarias pensaran que el nuevo diseño era intimidante. Por ello, decidieron tomar una decisión basada en los resultados del test A/A/B.

Los usuarios se dividieron en tres grupos: dos grupos de control para las fuentes antiguas y un grupo de prueba para las nuevas. Se debió descubrir qué conjunto de fuentes produce mejores resultados. Crear dos grupos A tiene ciertas ventajas. Se puede establecer el principio de que solo se confiará en la exactitud de las pruebas cuando los dos grupos de control sean similares. Si hay diferencias significativas entre los grupos A, esto puede ayudar a descubrir factores que pueden estar distorsionando los resultados. La comparación de grupos de control también indica cuánto tiempo y datos se necesitarán cuando se realicen más tests.

La información para el análisis general y para el análisis A/A/B está en el mismo dataset.
  
## Herramientas Utilizadas
- __Lenguaje de Programación:__ Python.
- __Entorno de Desarrollo:__ Jupyter Notebook.
- __Bibliotecas:__ Pandas, Matplotlib, Plotly, Seaborn, Scipy, Numpy, Math.

## Proceso del Proyecto
Este informe está dividido en tres partes, cada una de ellas tendrá diferentos objetivos:

__Preanálisis:__ Etapa en la cual se cargan los datos y se optimizan en caso de ser necesario, se trabajan los valores duplicados y ausentes, y finalmente, se modifican los datos para facilitar el posterior análisis.

- Optimizar el nombre de las columnas de manera que sea conveniente para el análisis.
- Comprobar si hay tipos de datos y valores ausentes y corregir los datos si es necesario.
- Agregar una columna de fecha y hora y una columna separada para las fechas (transformar las fechas del formato timestamp).

__Análisis:__ Etapa en la cual se responden las preguntas establecidas y se trazan los gráficos correspondientes.

- Estudiar y comprobar los datos.
    - ¿Cuántos eventos hay en los registros?
    - ¿Cuántos usuarios y usuarias hay en los registros?
    - ¿Cuál es el promedio de eventos por usuario?
    - ¿Qué periodo de tiempo cubren los datos?
    - ¿Hay una cantidad suficiente de registros por grupo?
    
    
- Estudiar el embudo de eventos.
    - ¿Qué eventos hay en los registros? y ¿Cuál su frecuencia de suceso?
    - ¿Cual la cantidad de usuarios y usuarias que realizaron cada una de las acciones registradas?
    - ¿En qué orden ocurrieron las acciones?
    - ¿Cual es la proporción de usuarios y usuarias que pasan de una etapa a la siguiente?
    - ¿En qué etapa pierdes más usuarios y usuarias?
    - ¿Qué porcentaje de usuarios y usuarias hace todo el viaje desde su primer evento hasta el pago?


- Estudiar los resultados del experimento.
    - ¿Cuántos usuarios y usuarias hay en cada grupo?
    - ¿Hay una diferencia estadísticamente significativa entre los grupos de control?
    - ¿Los grupos se dividieron correctamente?
    - ¿Qué conclusiones se pueden sacar del experimento?
    - ¿El nivel de significación ha sido el correcto?

__Conclusiones:__ Etapa en la cual se resume la totalidad del informe y se destacan los hallazgos mas importantes del análisis.

## Relevancia de los descubrimientos
El análisis de datos de Instacart reveló patrones importantes en el comportamiento de compra de los clientes. Estos insights pueden ser utilizados para optimizar las estrategias de marketing, gestión de inventarios y mejorar la experiencia del cliente.

## Ejecuta el proyecto [aquí](https://portfoliodabastianlopez.on.drv.tw/Portafolio/An%C3%A1lisis%20Instacart.html)
Para ver el diccionario de datos, el desarrollo completo en código, todos los gráficos y las conclusiones, haga click en el enlace de arriba.
