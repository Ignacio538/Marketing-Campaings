## **¿Qué canal de marketing se utiliza con mayor frecuencia y cuál genera mejor ROI?**

Si analizamos el número de veces que se han usado los canales, podemos observar que **"promotion" es el que más se ha usado**:

![Gráfica de análisis](https://github.com/Ignacio538/Marketing-Campaings/blob/main/docs/Most_Used_Channel.png)

Si hacemos la media del ROI por canal, observamos que **"referral" es el canal que mejor ROI ofrece**.

| channel   |      roi |
|:----------|---------:|
| referral  | 0.55156  |
| paid      | 0.54021  |
| promotion | 0.535714 |
| organic   | 0.517801 |

## **¿Qué tipo de campaña genera más ingresos en promedio y cuál tiene mejor conversión?**

Si analizamos los ingresos generados por tipo de campaña, podemos observar que **"social media" es el tipo que más ingresos genera**:

| type         |   revenue |
|:-------------|----------:|
| social media |    533773 |
| email        |    524764 |
| podcast      |    517895 |
| webinar      |    495772 |

Si hacemos la media del la tasa de conversión por tipo de campaña, observamos que **"webinar" es el tipo que mejor tasa de conversión ofrece**.

| type         |   conversion_rate |
|:-------------|------------------:|
| webinar      |          0.557328 |
| email        |          0.54375  |
| social media |          0.540474 |
| podcast      |          0.529035 |

## **¿Cómo se distribuye el ROI entre las campañas? ¿Qué factores están asociados con un ROI alto?**

Si analizamos la correlación del ROI con el presupuesto y la tasa de conversión, vemos que no hay una clara correlación. 

![ROI_Budget_correlation](https://github.com/Ignacio538/Marketing-Campaings/blob/main/docs/ROI_Budget_correlation.png) ![ROI_Conversion_correlation](https://github.com/Ignacio538/Marketing-Campaings/blob/main/docs/ROI_Conversion_correlation.png)

El ROI está distribuido de manera bastante uniforme entre todas las variables, lo que dificulta identificar los factores que contribuyen a un alto ROI.

![ROI_Columns_correlation](https://github.com/Ignacio538/Marketing-Campaings/blob/main/docs/ROI_Columns_correlation.png)

## **¿Hay diferencias significativas en la tasa de conversión entre audiencias B2B y B2C?**

![target_channel](https://github.com/Ignacio538/Marketing-Campaings/blob/main/docs/target_channel.png) ![target_type](https://github.com/Ignacio538/Marketing-Campaings/blob/main/docs/target_type.png)

Sí hay diferencias significativas en la tasa de conversión:
- Si observamos los valores en función al "channel", podemos observar una diferencia de un 10% en el target "B2C" cuando el channel es "paid" o "organic" así como una diferencia de un 7% en el target "B2B" en los mismos channels pero al revés. Lo cual es muy llamativo.
- Si observamos los valores en función del "type", poemos observar una diferencia de un 6% en el target "B2C" cuando el type es "webinar" o "podcast", sin embargo cuando el target es "B2B" no hay apenas diferencias siendo la mayor de un 1% entre "email" y "webinar".

## **¿Qué campaña tiene el mayor beneficio neto (net_profit)? ¿Qué características la hacen exitosa?**

| campaign_name                  |   net_profit |
|:-------------------------------|-------------:|
| Advanced systematic complexity |       987860 |

Podemos obserar que la campaña con más beneficio es la campaña "Advanced systematic complexity".

No podemos sacar ninguna conclusión de qué la hace exitosa. 

![Net_analysis](https://github.com/Ignacio538/Marketing-Campaings/blob/main/docs/Net_analysis.png)

Pero si analizamos el top 10 podemos observar que el "channel" está bastante diferenciado, teniendo el valor "organic" más peso sobre los otros. En menos medida podemos sacar las mismas conclusiones respecto al "target_audience" con "B2B" y el "type" con "social media" y "email".

## **¿Existe correlación entre el presupuesto (budget) y los ingresos (revenue)?**

![Budget_Revenue_cor](https://github.com/Ignacio538/Marketing-Campaings/blob/main/docs/Budget_Revenue_cor.png) ![Top_Bottom_Revenue](https://github.com/Ignacio538/Marketing-Campaings/blob/main/docs/Top_Bottom_Revenue.png)

Podemos observar en las tres gráficas que no hay correlación alguna entre el "budget" y el "revenue", tenemos campañas exitosas con un "budget" muy pequeño y campañas malas con un "budget" muy alto.

## **¿Qué campañas tienen un ROI mayor a 0.5 y ingresos encima de 500,000?**

Sólo 53 campañas cumplen con lo que consideramos "Campañas exitosas":
- 'revenue" mayor a 500,000
- 'roi' superior a 0.5
- 'conversion_rate' superior a 0.7
- 'budget' inferior a 50,000

![HP_Campaigns](https://github.com/Ignacio538/Marketing-Campaings/blob/main/docs/HP_Campaigns.png)

De las gráficas obtenemos las siguientes conclusiones:
- "referral" es el mejor "channel".
- "B2B" es el mejor "target_audience".

## **¿Existen patrones estacionales o temporales en el rendimiento de las campañas?**

![Revenue_ROI_CR_by_year](https://github.com/Ignacio538/Marketing-Campaings/blob/main/docs/Revenue_ROI_CR_by_year.png)

Podemos ver que el "revenue" ha ido disminuyendo para aquellas campañas que comenzaron de 2023 en adelante y la "Conversion Rate" desde aquellas que comenzaron desde 2024. El "roi", sin embargo, no ha parado de aumentar.

![ROI_per_month](https://github.com/Ignacio538/Marketing-Campaings/blob/main/docs/ROI_per_month.png)

Si obsevamos el "roi" por mes y trimestre, podemos ver que el segundo trimestre es el mejor, siendo abril el mes con el mejor "roi". En el otro lado, vemos que el tercer trimestre ha sido el peor. Es importante señalar que, pese a que el último trimestre no es malo, diciembre es el mes con peor "roi".

![Duration_campaigns](https://github.com/Ignacio538/Marketing-Campaings/blob/main/docs/Duration_campaigns.png)

Si miramos la duración de las campañas, podemos ver que aquellas que duran entre 660 y 720 días son las que más "revenue" y "roi" tienen. Sin embargo, las campañas que duran entre 120 y 180 o entre 240 y 300 días, son las que más "conversion_rate" tienen.

## **Conclusión Final:**

El análisis de las campañas de marketing revela patrones y tendencias clave que pueden ayudar a optimizar la estrategia de marketing de la empresa. Algunos de los hallazgos más importantes incluyen:

- Canales más efectivos: Aunque el canal "promotion" es el más utilizado, el canal "referral" destaca por generar el mejor ROI. Esto sugiere que las estrategias de marketing basadas en recomendaciones o referencias pueden ser particularmente rentables.

- Mejor tipo de campaña: El tipo de campaña "social media" es el que más ingresos genera, mientras que "webinar" tiene la mejor tasa de conversión. Esto podría indicar que, mientras las campañas en redes sociales son cruciales para generar ventas, los webinars son más efectivos para convertir a los usuarios en clientes.

- ROI y presupuesto: Aunque el presupuesto no parece tener una relación directa con los ingresos, es importante señalar que algunas de las campañas más exitosas en términos de ingresos tienen presupuestos modestos, lo que demuestra que la eficacia de la campaña no siempre depende de la cantidad invertida.

- Correlaciones estacionales: Se observa que el rendimiento de las campañas varía según la época del año, con el segundo trimestre siendo el más exitoso en términos de ROI. Esto es relevante para planificar futuras campañas y maximizar el impacto durante estos períodos.

- Campañas exitosas: Las campañas que cumplen con ciertos criterios como un ROI superior a 0.5, ingresos por encima de 500,000, una tasa de conversión alta y un presupuesto moderado son las más exitosas. Las campañas que se enfocan en el canal "referral" y en audiencias "B2B" tienen el mejor rendimiento.