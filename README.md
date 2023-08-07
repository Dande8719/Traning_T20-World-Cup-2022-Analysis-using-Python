# Traning_T20-World-Cup-2022-Analysis-using-Python
ES: Analizamos la ICC Men's T20, la copa del mundo de crikect con python. Trabajos mucho graficos de barras. EN:En analyze the ICC Men's T20 the crickets world cup with python.

1.-EN: We import the libraries and the data, here are very important the plotly libraries  ES:Cargamos librarias y datos. Tienen gran importancia en este projecto las librerias plotly.

2.-EN. We made a simple bar chart with plotly.express.bar ES: Contruimos un digrama de barras simple con plotly.express.bar.

![image](https://github.com/Dande8719/Traning_T20-World-Cup-2022-Analysis-using-Python/assets/103025222/85236e24-b7ae-48c7-9f6a-450cefcd5748)


3.-EN: We make a pie chart with 2 labels and 2 values. First, we need to use value-conuts() to count the matches won. Pay attention to the sintaxis of this pie chart !!  fig = go.Figure(data=[go.Pie(labels=label, values=counts)])
   ES: hacemos una grfica de tarta con 2 labels y 2 valores. Primero necesitamos usar value-conuts() para contar los partidos. Prestar atención a la sintaxis de la tarta  !! fig = go.Figure(data=[go.Pie(labels=label, values=counts)])

![image](https://github.com/Dande8719/Traning_T20-World-Cup-2022-Analysis-using-Python/assets/103025222/04d745fa-8a19-442f-ac8f-495a2e631e4e)

   
 4.-EN: we do a new bar chart but one that sums the x values in the chart, pay attention to the sintaxis ES: Hacemos un nuevo grafico de barras pero esta vez nos suma los valores de x en el grafico.  

![newplot (2)](https://github.com/Dande8719/Traning_T20-World-Cup-2022-Analysis-using-Python/assets/103025222/da17b4e7-4d95-4c33-82b2-f600720a2f2e)

 
 5.-EN: we go again with a bar chart but this time we use fig.add_trace to add columns in the x axis of the chart. ES: Vamos otra vez con los gráficos de barras pero esta vez usamos fig.add_trace para añadir columnas
 
![image](https://github.com/Dande8719/Traning_T20-World-Cup-2022-Analysis-using-Python/assets/103025222/227774fe-7dd5-46dc-accd-b8ddc7869ef2)
