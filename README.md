# Sobre los datos

El siguiente conjunto de datos contiene información recolectada desde la segunda semana de marzo hasta diciembre del 2020, mediante encuestas aplicadas a negocios de la ciudad de Choluteca, Honduras. 

# Información de los  atributos
La primera columna corresponde al tipo de Actividad Económica de los negocios.
<br/><b>1</b>: Actividades profesionales <br/><b>2</b>: Alojamiento<br/>
<b>3</b>Comercio <br/> <b>4</b>: Servicios de comida <br/> <b>5</b>: Transporte.
<br/><br/> La segunda columna contiene la información sobre el tipo de financiamiento que usan las empresas para desarrollar sus actividades.
<br/> <b>1</b>: Banco <br/><b>2</b>: Cooperativas <br/> <b>3</b>: Familiar <br/> <b>4</b>: Institución no bancaria
<br/><br/> La tercer columna nos muestra la infomación sobre el tamaño de la empresa.
<br/> <b>1</b>: Micro <br/> <b>2</b>: Pequeña
<br/><br/>La cuarta columna es nuestro indicar de censura. <br/><b>1</b>:Cierre de operaciones (evento de interés) <br/> <b>0</b>: Abierto, No presento el evento (censurado)
<br/><br/> La última columna nos indica el tiempo (en semanas) que transcurre des de la segunda semana de marzo hasta que se presenta el evento (en caso de no presentarlo se le asigna el valor de 42 que corresponde al tiempo en semanas que hay entre la 2da semana de marzo y la ultima semana de diciembre).

# Sobre los códigos 

Se implento el lenguaje de programación R para generar los códigos y obtener los resultados para el desarrollo de el proyecto.
<br/>En el segundo avance se realizó un análisis descriptivo del conjunto de datos.
<br/>En el tercer avance se realizó la estimación de la función de supervivencia.
<br/>En el cuarto avance se realizó la comparación de la función de supervivencia por grupos
<br/>En el quinto avance se calculó los cocientes de riesgo para determinar que grupos tenían mayor o menor riesgo de cerrar operaciones. 
