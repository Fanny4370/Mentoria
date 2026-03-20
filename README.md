# Mentoria2026
## DiploDatos 2026 - Mentoría "Deteccion de fraude: ¿Como cuido a mis clientes? Machine Learning aplicado a un caso de negocio financiero"

Nuestro Banco se ha propuesto este año hacer foco en el Cliente, y una de las principales premisas es Cuidarlo, para ello se ha tomado como desafio el desarrollo de un modelo capaz de predecir unos de los flagelos mas presente en estos dias, el fraude bancario, pero ¿que es un fraude bancario? para entenderlo vamos a interiorizarnos al respecto.
El fraude ha evolucionado a la par de la tecnología, pasando de métodos físicos a esquemas digitales muy sofisticados. Los riesgos que nuestro cliente puede sufrir un fraude los podemos dividir en tres grandes categorías: el robo de identidad, la manipulación mediante ingeniería social y el compromiso de dispositivos físicos.

###Ingeniería Social (Engaños Digitales)
En estos casos, el delincuente no "hackea" el sistema, sino que manipula a la persona para que entregue sus claves de forma voluntaria.

Phishing: Es el método más clásico. Recibes un correo electrónico que imita a la perfección la estética de tu banco, alegando un "bloqueo de cuenta" o una "compra sospechosa", con un enlace a una web falsa para que ingreses tus credenciales.

Smishing: Similar al phishing, pero a través de mensajes de SMS. Suelen incluir enlaces acortados que redirigen a sitios maliciosos.

Vishing: El fraude ocurre por llamada telefónica. Un supuesto operador técnico o de seguridad te guía para que le dictes un código de verificación  o realices una transferencia "de prueba" a una "cuenta segura".

2. Fraude con Tarjetas de Crédito y Débito
Afecta directamente al plástico o a los datos impresos en él.

Skimming: Consiste en el clonado de la banda magnética. Se instalan dispositivos ocultos en los lectores de los cajeros automáticos o terminales de pago (POS) para copiar la información.

Carding: Es el uso de software para generar números de tarjeta de forma aleatoria hasta encontrar uno que funcione, permitiendo realizar compras pequeñas en sitios de e-commerce que no validan el código de seguridad (CVV) con rigor.

3. Compromiso de Cuentas y Dispositivos
Apunta a tomar el control total del acceso bancario del cliente.

SIM Swapping: El atacante logra que la compañía telefónica duplique tu tarjeta SIM. Una vez que tu teléfono pierde señal, el delincuente recibe tus SMS de recuperación de contraseña y códigos de validación, vaciando las cuentas en minutos.

Malware Bancario: Virus o troyanos diseñados específicamente para interceptar aplicaciones financieras. Algunos pueden superponer pantallas invisibles sobre la app real del banco para capturar el PIN de acceso.

Entre otros, y cada vez se vuelve mas sofisticado el procedimiento para llevar a cabo el fraude.

Ahora bien, para poder llevar a cabo semejante tarea nos hemos propuesto la generacion de un DataSet que nos permita construir un modelo capaz de predecir un evento fraudulento y activar las alertas correspondientes para el resguardo de nuestro cliente, basandonos en el ML y en las herramientas aprendidas a lo largo de esta Diplomatura. 

En esta mentoria aprenderemos a utilizar el pipeline de aprendizaje automático paso a paso y esto es de gran importancia, dado que ya está comprobado que es aplicable a cualquier tema que nos interese.

También se aprenderá a realizar análisis de variables para poder discernir cuales son las óptimas para el modelo  aplicar. Como así también aplicar los distintos modelos supervisados para su prediccion.

Algo también a considerar es que se trabajara con datos reales de la entidad bancaria, y como sabemos, muchas veces los datos no están íntegros o bien relevados,  lo que nos pondrá en un gran desafío para su aplicabilidad en ciencia de datos. 

### Datos
El set de datos de la entidad bancaria, es una muestra aleatoria que representa la transaccionalidad de clientes que han sufrido un fraude o no , dicha transaccionalidad es del ultimo año. El DataSet se divide en 3 secciones: 

#### Información sobre Datos del cliente: 
Conjunto de 7 variables que informan datos personales del cliente.

#### Información sobre los Movimientos Realizados: 
conjunto de 5 variables que el tipo de movimiento efectuado en la transaccion.

#### Información la Transaccion Realizadas: 
conjunto de 13 variables que informan datos de la transaccion realizada, fecha, hora , importe, terminal, ciudad, etc.

Para ver la descripcion de cada columna se puede consultar el excel Dr_Muestra.xlsx.
