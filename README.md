## TrabajoFinal-Diplomatura-Log.-CDA

**Integrantes del grupo Nº 5 -**

- Matias Vanni <Matiaasvanni@gmail.com>
- Joaquin Nougues <joaquinnougues71299@gmail.com>
- Emilio Gabriel Paredes <chogabrielparedes1999@gmail.com>
- Facundo Vargas <vargasfacundomiguel@gmail.com>
- Federico Antonio <federicoangelantonio1@gmail.com>

*_TRABAJO FINAL: ENUNCIADO_*

[2023 Trabajo práctico para evaluar Diplomatura.pdf](https://github.com/FedericoAntonio1/TrabajoFinal-Diplomatura-Log.-CDA/files/13351765/2023.Trabajo.practico.para.evaluar.Diplomatura.pdf)

_*Empresa de referencia*: **Grupo UNIBER**_


## **_DESARROLLO DEL TRABAJO_**

## Gestión del flujo de Pallets

*_**1.** 
Situación Actual: Describa en hasta una página la situación actual y el
problema detectado. Trate de utilizar números (costos,
tiempos, unidades)
Situación mejorada: Describa la mejora que propone para la situación
actual, justificando en cada aspecto relevante por
qué cree que esa implementación mejoraría_*

**_Situación Actual_**

Grupo UNIBER es una empresa dedicada a la comercializacion de materiales de construccion , para minoristas y mayoristas. Actualmente cuenta con sucursales en provincia de Salta, Catamarca, Jujuy y Tucuman. 
El trabajo esta referido al abastecimiento terciarizado de cemento y devolucion de pallets desde el proveedor Loma Negra, con aprovisionamiento de las sucursales de Supermat (ubicadas en Oran, Tartagal, Salta Capital y Jujuy), El Sol Materiales (en Yerba Buena y Lastenia, Tucuman) e Hipercat (en Catamarca), con la aclaracion de contar con 2 sucursales en Salta Capital: ATH y CHILE.
La empresa UNIBER presenta una problemática en la gestion de devolución de pallets frente a su proveedor Loma Negra, ocacionando una pérdida económica significativa. El criterio de Loma Negra para la facturacion al cliente (UNIBER) es contar con el saldo pendiente mayor al 25% de la salida de pallets del mes, este porcentaje se considera como mercaderia en circulacion. La facturacion es un resultado de un analisis realizado el día 5 o 6 del mes siguiente, comparando la variacion entre las salidas y entradas de tarimas (despacho e ingreso de Loma Negra) y una _foto_ del total de salida del corriente mes.  

A continuación, se presenta un caso real:
_Datos a tomar en cuenta:_ 

- Cliente de Loma Negra: SUPERMAT (Razon social que comprende parte de Grupo UNIBER)
- Costo unitario de tarima: $11.200 + IVA

En el mes de octubre se realizo una compra y abastecimiento de Loma Negra de un total de 370 equipos de cemento aproximadamente. Entendiento que cada transporte que llega con cemento a la sucursal, cuenta en promedio con 15 pallets de cemento, lo que nos da un total de abastecimiento de 5570 pallets despachados de fabrica. Entonces, siguiendo con el criterio del proveedor para facturacion de tarimas (pallets), deberiamos contar con un saldo de solo 1388 pallets (tarimas vacias) para el momento de analisis final realizado el 05/11. Lo que finalmente paso es que se conto con un saldo de hasta 2200 tarimas, mas de 800 por arriba del limite y para el analisis final el 05/11 con un saldo de 1750 tarimas. Lo que genero una facturacion de 400 pallets del mes de octubre. Cabe aclarar que la facturacion de pallets a clientes es de solo 140 pallets, lo que no llega a justificar el costo incurrido para una gestion deficiente en la devolucion de tarimas al proveedor. 

Se podria optar, en los primeros dias del mes, optar por no despachar nada de cemento y con esto no incurir en aumentar la deuda hasta el 05 del mes, periodo final de analisis. Esto presenta un inconveniente, ya que, siguiendo con el ejemplo de SUPERMAT en octubre, demanda diariamente 15 equipos de cemento aproximadamente. Esto genera un despacho de hasta 225 pallets por dia.

**_Situación mejorada_**

Se propone como solución: 

A)Revisión y control del flujo de tarimas, junto con un seguimiento desde la web LOMANET clientes. Es un cambio significativo ya que la empresa únicamente vendía cemento e ignoraba la cuestión de las tarimas, actualmente se sabe cuántas de ellas ingresan a la empresa, cuantas salen y donde están, quienes son los transportistas que realizan devoluciones. 

B) A los clientes con cuenta corriente emitirles conceptos facturables por las tarimas que llevan junto con el cemento, con el mismo criterio del tope del 25% que impone Loma Negra.
C) Para los clientes de contado: 1. cargar las bolsas a granel; 2. facturarles las tarimas; 3. el cliente al momento de cargar debe ir con sus tarimas.

D) Para una optimización de los costos logísticos, se proponen devoluciones quincenales de pallets con equipos completos a Loma Negra. Ese mismo camión que devuelve las tarimas, carga cemento para retornar a Tuc. Cabe destacar que cumplir con la política de devolución reduce no solamente las perdidas monetarias, sino también contribuye a reducir el impacto ambiental mediante la reutilización. Se busca una comunicacion constante entre los involucrados en el circuito de tarimas. 

E) Ademas, se busca llevar el stock de la sucursal a valores optimos en el ultimo dia del mes, para luego bajar el aprovisionamiento hasta fecha del analisis final. Con esto conseguimos no demandar tanto cemento en los primeros dias del mes y no aumentar considerablemente el saldo de pallets. Desafortunadamente, esto aumenta la posibilidad de contar con una rotura de stock en la sucursal.


## Implementacion - Mes de noviembre

Para el mes de noviembre de implemento algunas de las ideas propuestas anteriormente, logrando resultados favorables. A continuacion informamos el comportamiento del stock de cemento de las sucursales que comprenden SUPERMAT y el resultado del analisis de tarimas del mes de noviembre, con periodos de analisis el 01/12 y el 05/12.

Adjunto: 
- Vease: "TarimasNoviembre_Supermat" Analisis de tarimas del mes de noviembre de la sucursal de SUPERMAT

- Vease: "ABASTECIMIENTO LN-UNIBER NOV23.xlsx - PRESENTACION" Comportamiento del stock del mes de noviembre de la sucursales que comprenden SUPERMAT. 

Cabe aclarar que los graficos de las sucursales como parametros el stock optimo que puede tener de inventario la sucursal, el 50% de la misma y un stock minimo de 2 veces la demanda diaria estimada. 
Observamos en el analisis de tarimas que se pudo reducir de saldo negativo de 2092 tarimas a 1506 para el dia 05/12. Para el fin del mes, y con el criterio del proveedor, contamos con 1275 tarimas como el limite de tarimas que se podria deber. El resultado final es 208 pallets por arriba del limite, con un justificativo para una futura facturacion de 228 tarimas facturadas a cliente durante el mes y un desperdicio de 110 pallets.

## Proceso de la empresa y gestión logística

*_**2.** 
Situacion Inicial: Defina el proceso principal de su empresa, sus entradas,
salidas y la forma de trabajo. Indicar los proveedores,
clientes y responsables de dicho proceso.

Situacion Mejorada: Describa brevemente los inconvenientes en cuanto
a la gestión y sobre todo en cuanto a la gestión
logística que usted visualiza en su empresa. Debe
definir al menos las tres principales problemáticas_*

**Situacion actual**

Uniber realiza comercializacion mayorista y minorista en el rubro de la construccion, teniendo como clientes a empresas constructoras, corralones y consumidores finales para el mercado minorista. 
La empresa tiene proveedores de materiales en todo el país, algunos de ellos son: Loma Negra, Weber, Tensolite, Placo, Cerámica Alberdi, Cañuelas, Zapla y Ternium. 
Para corralones y empresas constructoras, se les brinda un servicio de entrega en equipos completos directo desde fabrica o en la mayoria de los casos, reparto desde la empresa. Además, se tiene la opcion de retiros desde sucursal. Para las operaciones mecionadas, cada sucursal cuenta con un equipo de trafico, que varia en la cantidad de integrantes dependiendo de cada una. 

*Vease imagen adjunta: "Cadena de abastecimiento-grafico"*

En cuento al proceso principal de UNIBER, muchos dirian que es la comercializacion, pero es un errorconcluir que no ve en los procesos de logistica y cadena de abastecimiento, un potencial diferencial en el mercado. La empresa tiene un panorama optimista para el futuro, donde el precio y la forma de pago, en un economia estable, es parecida entre la competencia. El gran diferencial en el mercado, va a ser los tiempos de entregas y la gestion de *repartos desde las sucursales*. 

Actualmente, las operaciones de reparto a clientes, cuentan con una participacion del XX% sobre la facturacion total. *(Vease archivo adjunto: "Participacion logistica y CDA en FC total")*

Si hablamos de la sucursal de El Sol Materiales, ubicada en San Miguel de Tucuman, el equipo de trafico esta ingregrado por 4 personas especializadas en la entrega de materiales desde sucursal a cliente: 3 administrativos y 1 operarivo; tambien cuenta con 1 persona responsable del abastecimiento _fabrica-ElSolMateriales_ y entregas de material _fabrica-cliente_. 

Para esta sucursal, se presentan *inconvenientes* como la ubicación de los corralones que piden equipos completos a domicilio. Los mismos, tienen accesos muy limitados que imposibilitan las maniobras de los camiones. En estos casos, se deben seleccionar chasis acoplados para un mejor radio de giro. 

Otro inconveniente que presenta el area a la hora de realizar las entregas es la falta de stock, en la sucursal donde se esta por realizar el despacho, de uno o varios materiales a entregar en el dia. Esto no sucude siempre y se debe a una mala distribucion de existencia en las sucursales existentes en una provincia en particular. Para el caso de *El Sol Materiales*, el mismo cuenta con dos sucursales, una ubicada en San Miguel de Tucuman y otra en la localidad de Lastenia. En varias ocasiones, esto trae un costo de *transferencia* (moviento de material entre sucursales), generando "ruido operacional" y en el peor de los casos, reprogramando el envio. Este costo esta visto como un mal menor y no existe seguimiento ni analisis al respecto. 

Otros inconvenientes, son los paros de planta de Loma Negra, las propias roturas de los camiones contratados, la complicación con los vendedores que quieren que se entreguen equipos a clientes que aún no tienen orden de compra, además de la lucha constante contra las tarifas de los transportistas que buscan maximizar ganancias mientras la empresa busca disminuir costos. 


## Funcionamiento de la cadena de abastecimiento
*_**3.** 
Situación Actual: Describa gráficamente y en palabras el funcionamiento de
la cadena de abastecimiento actual de su empresa.
Situación mejorada: De similar forma, proponga una cadena de
abastecimiento mejorada, consignando las mejoras
establecidas y justificando los cambios_*

**Situacion actual**  

La cadena de abastecimiento de la empresa funciona de diferentes maneras, específicamente con Loma Negra se utilizan camiones contratados para buscar cemento desde la fabrica (FOB), y se utilizan fletes de loma negra (CIF).

Comprar mediante CIF proporciona ventajas significativas como ser una menor gestión administrativa en los envíos (se encarga el proveedor), sin embargo, solo es posible elegir 2 o 3 destinos fijos, imposibilitando el envío directo a cada cliente. Por otro lado, el FOB permite realizar dichos envíos directos, pero con un costo más caro. 
Los camiones contratados son mayormente de Tucuman y tienen que ir hasta Catamarca, donde se encuentra la fábrica de Loma Negra, en búsqueda del cemento. Estos entregan directamente desde la fabrica al cliente o se dirigen al deposito de El Sol en San Miguel de Tucuman a dejar la carga. En este ultimo caso, una vez que ya esta la orden de preparacion del pedido, se procede a realizar el mismo y se le comunica al cliente el turno asignado que tiene para retirar su pedido.

**Situacion mejorada**

En la situacion actual se cuenta con dos problematicas en la cadena:
1. El tiempo de espera que tienen los camiones para descargar debido a que hay un solo flujo en el deposito para carga y descarga
2. La tarifa unica que se les cobra a los clientes por envio
   
Ante la primera problematica se propone lo siguiente:

Hacer una nueva distribucion de los productos en el deposito y una sectorizacion que permita tener bien definidas las zonas de carga y descarga para asi ganar tiempo y espacio. La nueva sectorizacion se hara en base al diagrama ABC en el cual los productos A estaran en las zonas de rapido acceso, ya que estos son los que mayor rotacion tienen. Ademas, debido a este nuevo orden de productos, se ganara espacio, lo que permitira tener dos lineas separadas, una exclusiva para descarga y otra para carga, esto permitira un mejor flujo de movimiento de camiones y disminuir los tiempos muertos, tanto de los clientes como de los proveedores. 

Con la segunda situacion se propone la siguiente solucion:

Se sectorizaran los clientes de Tucuman ya que en estos momentos se le cobra la misma tarifa a todos. Esta sectorizacion permite definir bien las zonas de entrega y armar un tarifario con valores diferenciados teniendo en cuenta la cantidad de kilometros recorridos desde la fabrica al destino.



## Gestion de cumplimiento de mercaderia en reparto 
*_**4.** 
Situación Actual: Describa brevemente cómo funciona actualmente la
gestión de operaciones en su proceso principal y al menos
dos problemáticas abordadas en el curso. Resalte el uso de
pronósticos, gestión de la mano de obra y subcontratación._*

*_Situación mejorada: Describa mejoras posibles de implementar en la
Gestión de operaciones en relación a: uso de
pronósticos, gestión de la mano de obra y
subcontratación_*

**Situacion actual**

El proceso principal de la gestion de operaciones es el reparto local (distribución a clientes b2c y b2b), el cuál esta a cargo del area de trafico de la sucursal correspondiente. Enfocando el estudio en la sucursal de El Sol Materiales, observamos que la gestion de reparto de mercaderia a clientes (corralones y empresas constructoras) cuenta con un responsable del ruteo de la flota propia (6 camiones) y transportes tercerizados. En este aspecto, el planeamiento es con una anticipacion de 1 o 2 dias, con "cierres de dias" dependiente a pesaje total o volumen a entregar. Es decir, si hablamos de una capacidad maxima a transportar de 8 a 9 Toneladas por camion, el vendedor podra seguir asginando entregas a clientes para un dia especifico hasta cumplir con lo maximo que puede transportar la flota de la sucursal y 4 a 6 camiones tercerizados. El area cuenta ademas con un responsable para la comunicacion con el cliente, donde se realiza confirmacion de recepcion por parte del cliente y alineamiento de la hora aproximada de la entrega. 

*Problematica abordada*

1. Una problematica que presenta el area, son los casos de falta de stock para la entrega completa de un pedido. Es decir, las entregas que terminan la jornada con un estatus de *pendientes por falta de stock* o *Caidos por stock*. 

Vease *analisis de costo incurrido en transferencia-OCT23*. Datos adjuntos. (Pendiente a hacer)

Aqui es oportuno comentar que el faltante de stock se debe a una mala distribucion de las existencias. Actualmente, la sucursal de El Sol Materiales cuenta con 2 depositos, uno en San Miguel de Tucuman y otro en Lastenia. Se cuenta con un responsable del area de compras que gestiona la adquisición de materiales, como asi también las transferencias para que ningún deposito se quede sin stock. 
Tambien vemos que las operaciones de *transferencias* (movimiento de mercaderia intersucursal) estan normalizadas por parte del equipo de trafico. Realizando diaramente/semanalmente X transferencias, con motivo de necesidad urgente para completar el pedido pendiente. Con esto incurrimos en un costo de $Y por operacion, en promedio, $X por semana/mes y una deficiencia de capacidad para el transporte empleado. 
Actualmente solo se cuenta con pronósticos de ventas basados en ventas históricas.

Vease *analisis de costo incurrido en transferencia-OCT23, analisis de concurrencias de transferencias del area de trafico y tarifario de reparto local.* Datos adjuntos (Pendiente a hacer)

2. Otra problematica que presenta el area son los casos en donde no se gestiono una actualizacion de la direccion de entrega de emrpesas constructoras, donde las obras en construccion van cambiando. Esto puede generar demoras en las entregas posteriores, en las entregas pendientes y costo de hora extra en mano de obra tanto para el cliente como para la empresa.

 **Situacion mejorada**

1. Se opto por hacer una gestion de transferencias preventiva con frecuencia semanal, realizada el dia sabado (jornada con menor necesidad de entrega). La idea es contar con un techo de $X mensual, el cual es el costo actual (Vease analisis, dato adjunto). Se busca realizar una o dos operaciones, con eficiencia en la capacidad del transporte a usar, centralizandose, en primer instancia, en el 20% del material con mayor ocurrencia.

2. 

## Gestion de Inventario 
##5
**Situcaion actual**
Describa brevemente cómo funciona actualmente la
gestión de inventarios en su empresa y al menos dos
problemáticas abordadas en el curso. Resalte el uso de
pronósticos y algoritmos que se utilizan

**Situcaion mejorada**
Describa mejoras posibles de implementar en la
Gestión de inventarios en relación al uso de
pronósticos u otra metodología que considere.

**Situacion actual**
En cuanto la gesrion de inventarios, vamos a seguir enfoncandonos en el cemento, y en particular al cemento CPC30 con hasta 50gr por bolsa. 
Actualmente la empresa (UNIBER) cuanta con 3 entidades que reciben servicios del proveedor Loma Negra. Dentro de estas entidades, existen diferentes sucursales. 
A continuacion ofrecemos una descripcion de las sucursales correspondientes a cada entidad, una ubicacion geografica, consumo diario promedio del mes de noviembre y stock optimo o maximo de la sucursal

INSERTE CUADRO*

Cabe aclarar que la programacion de abastecimiento de las mismas sucursales es realizado por LN (loma negra), la misma realizada con estimacion historica de cada sucursal y disponibilidad del servicio de transporte propio. 

Descripcion actual por entidad/zona:

ELSOLMATERIALES

Recordemos que solo para el caso de la entidad El Sol Materiales, el servicio de transporte es puesto por la propia empresa. 

Observamos que El Sol Materiales, cuenta con 2 sucursales de UNIBER, donde el aprovisionamiento de cemento es REACTIVO: el encargado de trafico busca mantener un stock tentativo a un 50% al 100% de ambas sucursales (SAMI y LASTENIA). Para esto hace uso de transportes contratados por la empresa y en caso de necesidad, son estos mismos transportes los que hacen el servicio de abastecimiento fabrica-cliente. 

HIPERCAT

Hipercat, ubicada en Catamarca es una sucursal relativamente nueva para la empresa. Dificil en cuanto a hacer estimaciones de consumo de cemento. Con un sotck optimo de 5500 bolsas. El abastecimiento de cemento es realizado por transportes puestos en su total por el proveedor (Loma Negra), con una programacion mensual y la posibilidad de realizar correcciones por parte del responsable del abastecimiento de UNIBER. 
Hablamos entonces de una gestion de inventario REACTIVA, con modificaciones sobre la marcha y alineamientos para mantener el sotck entre un 50% y 100% del stock optimo. 


SUPERMAT. 

Supermat, comprendido con sucursales de la provincia de Salta (5 en total) y una sucursal en Jujuy, es la entidad con mayor sucursales y consideraciones a la hora de gestionar el inventario de cemento. 
Con un abastecimiento realizado de igual forma que la sucursal de Hipercat, los transporte y la programacion es proporcionada por el proveedor. El seguimiento y las modificaciones que se deba hacer es responsable del personal de abastecimiento de UNIBER. 

Contamos con las sucursales de CHILE, ATH y JUJUY, donde se puede stockear hasta 13000 bolsas y los mismos alineamientos que las sucursales mencionadas anteriormente, mantener un stock de 50% a 100%. Estas sucursales cuentan con las mayores demanda de consumo de cemento, lo que corresponde a un ingreso diario de entre 3 a 5 equipos, para cada una.  

Con respecto a las sucursales de TARTAGAL y ORAN, cuentan con menor capacidad de stockear y una mayor variacion del consumo, donde podemos encontrar casos donde el cliente decide retirar cemento de la sucursal, retirando 2 equipos en el dia, la sucursal de TARTAGAL disminuye abruptamente su stock. 

Observaciones generales: 
- El cemento tiene una de la mayores rotaciones de mercaderia en el rubro, ademas cuenta con una vida util de 30 dias. 
- Cuando hacemos mencion de 1 equipo de cemento, nos referimos a 600 bolsas de cemento aproximadamente. 

Problematicas generales: 
1. 

##Situacion mejorada##

Propuestas de mejoras: 
- Definir un stock minimo para las sucursales, y realizar proyeccion semanal. 
##Situacion mejorada##

Se propone trabajar con un diagrama ABC, el cual se realiza a partir de los productos que tengan mayor rotacion, para esto es importante contar con un informe tanto de ventas como del encargado de mercaderia **de los sku** que mas salieron del deposito y que mas se vendieron. Esta metodologia permitira identificar los productos que tienen mayor rotacion, por lo tanto, a estos se les debera dar una mayor importancia en el deposito y asignarles un lugar cerca de la zona de preparacion de pedidos para asi ganar tiempo y combustible a la hora de realizar los pedidos. Gracias a esta medida, se puede solucionar en parte la problematica del El Sol Materiales que tiene respecto al tiempo de preparacion de los pedidos y el quiebre de stock. 
