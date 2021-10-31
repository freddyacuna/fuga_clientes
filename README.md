# Fuga Clientes

Considere el problema que enfrenta una entidad financiera que tiene altas tasas de fuga voluntaria. Esta institución no tiene claro cuál es el perfil característico que tienen los clientes fugitivos ni cuáles son las razones por las cuales estos se fuga. Dentro de este contexto, le han encomendado a usted dos tareas fundamentales. La primera tarea consiste en desarrollar un modelo predictivo que permita identificar tempranamente cuáles clientes son más propensos a fugarse. La segunda tarea consiste en definir una serie de políticas comerciales que permitan retener a estos potenciales clientes fugitivos. 

Adicionalmente, en la Tabla 1 se muestran los beneficios/costos económicos de los aciertos y errores en las predicciones. La decisión comercial del modelo de clasificación es definir a que clientes cobrarles con una tarifa normal y a que clientes ofrecerles una oferta.



Fuga|
No Fuga|
Fuga
5000
-100
No Fuga
-1000
0

Tabla 1. Matriz de pagos de las acciones comerciales.

De acuerdo con lo anterior, es necesario responder a las siguientes interrogantes expuesta por el gerente general: 

1. ¿Qué hacer para que estos clientes no se fuguen? 
2. ¿Cuáles son las acciones comerciales que deberíamos emprender con estos clientes? 
3. ¿Se las aplico a todos los clientes? 
4. ¿Cuál es el costo de estas iniciativas? 
5. ¿Qué tipo de herramienta tecnológica necesito? 


Una completa descripción de las variables recolectadas por cada cliente se presenta a continuación: 
 
1. FUGA: F=cliente fugado, NF= cliente activo (variable objetivo, última columna)
2. CreditMes_T: Crédito en mes T
CreditMes_T-1: Crédito en mes T-1
CreditMes_T-2: Crédito en mes T-2
NumTarjCred_T: Número de tarjetas de crédito en mes T
NumTarjCred_T-1: Número de tarjetas de crédito en mes T-1
NumTarjCred_T-2: Número de tarjetas de crédito en mes T-2
Ingreso: Ingreso cliente
Edad: Edad cliente
NumTransWeb_T: Número de transacciones en web en mes T
NumTransWeb_T-1: Número de transacciones en web en mes T-1
NumTransWeb_T-2: Número de transacciones en web en mes T-2
MargenComp_T: Margen del cliente para la compañía en mes T
MargenComp_T-1: Mmargen del cliente para la compañía en mes T-1
MargenComp_T-2: Margen del cliente para la compañía en mes T-2
MargenComp_T-3: Margen del cliente para la compañía en mes T-3
MargenComp_T-4: Margen del cliente para la compañía en mes T-4
MargenComp_T-5: Margen del cliente para la compañía en mes T-5
MargenComp_T-6: Margen del cliente para la compañía en mes T-6
Telefono: La compañia posee el numero de telefono del cliente
NivelEduc: Nivel Educacional del cliente
Genero: Genero del cliente
EstCivil: Estado civil del cliente
Region: Region donde vive el cliente
