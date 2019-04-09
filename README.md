# Aplicación financiera

## Índice

- [Preámbulo](#Preámbulo)
- [Introducción](#Introducción) 
- [Entrevistas y testing](#Entrevistas-y-testing) 
- [Observación](#Observación) 
- [Objetivos](#Objetivos) 
- [Reto de diseño](#Reto-de-diseño) 
- [Prototipo de alta fidelidad](#Prototipo-de-alta-fidelidad) 


## Preámbulo

En banco más importante del país lanzó una nueva aplicación móvil al
mercado para que sus usuarios puedan visualizar sus gastos mensuales y fomentar
el ahorro.

## Introducción

### Contexto

El objetivo principal de este proyecto pretende encontrar las posibilidades de mejora  para definir la dirección y evolución de está aplicación y su rediseño, sustendado por la investigación previa. 

Esta nueva propuesta de diseño incluye análisis de datos, investigación de campo, uso de metodologías UX (descritas próximamente), diseño de componentes de la interfaz y user testing.

Aquí el [contexto del proyecto](https://github.com/SegamanDI/FinancialAPPCDMX007) y el [Prototipo navegable](https://marvelapp.com/e9h245e) previo a la iteración del producto.


##  Problemas encontrados tanto a nivel de negocio como a nivel de usuario

### Análisis de data 

![Análisis de data](https://github.com/Diana-Pelaez/FinancialAPPCDMX007/blob/master/Imagenes/An%C3%A1lisis_de_data.jpg)

[Data](https://docs.google.com/spreadsheets/d/1e9WoTgGdmj8WD4cB2DULiVj8XZcgeEriqoiVdTlq7Lc/edit#gid=1292037545)

### Posible solución del problema actual

![Solución del problema actual](https://github.com/Diana-Pelaez/FinancialAPPCDMX007/blob/master/Imagenes/Soluci%C3%B3n_del_problema_actual.jpg)

### Evaluación Heurística

Inspección de problemas potenciales.

**1. Visibilidad del estado del sistema.**

   - El menú no es tan claro. El icono de menú principal solo despliega el perfil del usuario. 
   - Para acceder a las secciones de la app hay que regresar paso por paso al **home.**

**2. Empate entre el sistema y el mundo real.**

  - El icono de "Crear cuenta" no hace sentido con la acción que describe para crear una nueva cuenta de ahorro.
  - El "saldo disponible" no es claro si incluye descuentos del ahorro o no.
 
**3. Control y libertad del usuario.**
  - El usuario debería poder decidir el orden en el que quiere visualizar su desglose de gastos, alfabético, por fecha, ascendente, descendente, etc.
  - El usuario debería poder ingresar nuevas metas y dejarlas en un apartado pero sin activar, solo para no olvidarlas. 
  - Cuando se crea una nueva meta debería poderse confirmar o solo guardar (meta dormida).

**4. Consistencia y estándares.**

  - En sección de ahorros se visualiza en avance de cada meta en porcentaje (**%**) y confunde a los usuarios, quienes dicen preferir monto en pesos (**$**).
  - Icono azul con puntos suspencivos poco claro, no saben qué tipo de información encontrarán aquí.

**5. Prevención de errores.**

  - Debería dar opción de borrar o editar perfil, metas de ahorro y demás secciones. 

**6. Reconocimiento mejor que recuerdo.**
  - Icono y nombre de la app del banco es poco claro y no recordable. 

**7. Flexibilidad y eficiencia de uso.**

  - Debería permitir un acceso a usuarios ya registrados rápido y seguro. 
  - Debería dar opción de borrar o editar perfil, metas de ahorro y demás secciones en todo momento.
  - No tiene un acceso rápido a las metas.
  - En el registro de nueva meta ayudaría si la frecuencia para abonar estuviera en un select (sin planear, diariamente, semanalmente, bisemanal, mensualmente) .
  - No hay opción de tipo de moneda para el ahorro.
  - Se tendría que poder editar la tarjeta desde la que se hará la transacción (en caso de crédido, pagar desde la de débito).
  - Debería dar opción de pagar automática o manualmente.  
  - En caso de ser manual, no hay opción para pedir recordatorio de pago (día y hora).

**8. Diseño estético y minimalista.**

  - Lo hace bien.

**9. Ayudar a reconocer, diagnosticar y recuperarse de errores.**

   - Debería dar opción de borrar o editar perfil, metas de ahorro y demás secciones en todo momento.

10. Ayuda y documentación: 
  - En registro de cuenta no se visualizan los terminos y condiciones. 
  - Ayudaría un instructivo de pasos para el primer ingreso a la app.

### Benchmark app financieras

![Benchmark01](https://github.com/Diana-Pelaez/FinancialAPPCDMX007/blob/master/Imagenes/01.jpg)

![Benchmark02](https://github.com/Diana-Pelaez/FinancialAPPCDMX007/blob/master/Imagenes/02.jpg)

![Benchmark03](https://github.com/Diana-Pelaez/FinancialAPPCDMX007/blob/master/Imagenes/03.jpg)

**Benchmark Gains:**

![Benchmark Gains](https://github.com/Diana-Pelaez/FinancialAPPCDMX007/blob/master/Imagenes/Benchmark_Gains.jpg)

## Entrevistas y testing

**Hallazgos de testeo en campo**

![Hábitos de ahorro](https://github.com/Diana-Pelaez/FinancialAPPCDMX007/blob/master/Imagenes/H%C3%A1bitos_de_ahorro.jpg)

## Observación

**Testeo de usabilidad de la app financiera**

![Testeo de usabilidad](https://github.com/Diana-Pelaez/FinancialAPPCDMX007/blob/master/Imagenes/Testeo_de_usabilidad.jpg)

**Audios App Financiera**

[Audios](https://drive.google.com/drive/folders/1-4WKxbFVgi7ZSqMKZp_2GhXZwmVm1FeE?usp=sharing)

## Objetivos 

### Objetivos del cliente (Banco)

![Objetivos del cliente](https://github.com/Diana-Pelaez/FinancialAPPCDMX007/blob/master/Imagenes/Objetivos_del_cliente.jpg)

- Definir la dirección de la aplicación.
- Atraer nuevos clientes.
- Descubrir el perfil de usuarios (cuál es su objetivo de ahorro).
- Usuarios con números positivos en su cuenta bancaria.
- App fácil, rápida, moderna y confiable. 
- Incluir Facebook Ads o no
- Mayor seguridad.
- App para la nueva generación usándo productos financieros.

###  Objetivos del usuario

![Objetivos del usuario](https://github.com/Diana-Pelaez/FinancialAPPCDMX007/blob/master/Imagenes/Objetivos_del_usuario.jpg)

### Definición de User Persona

![UserPersona](https://github.com/Diana-Pelaez/FinancialAPPCDMX007/blob/master/Imagenes/UserPersona.jpg)

### Barreras conductuales de ahorrar para el futuro.

**Se han definido las siguientes problemáticas:**

![Barreras conductuales de ahorrar para el futuro.](https://github.com/Diana-Pelaez/FinancialAPPCDMX007/blob/master/Imagenes/Conclusiones_para_el_ahorro.jpg)

[Fuente](http://www.ideas42.org/wp-content/uploads/2018/11/I42-1046_MetLifeLatAm_paper_SPA_Final.pdf)

#### Síntesis de resultados

![Síntesis de resultados](https://github.com/Diana-Pelaez/FinancialAPPCDMX007/blob/master/Imagenes/S%C3%ADntesis_de_resultados.jpg)

### Historias de Usuario

1. Yo como usuario quiero tener una app que me permita tener un control financiero para lograr mis planes futuros.

2. Yo como usuario quiero emprender acciones de ahorro en el presente para mis planes a futuro.

3. Yo como usuario quiero ahorrar fácil y sin esfuerzo.

## Recomendaciones de próximos pasos para el banco con respecto al app:**

### Reto de diseño 

[Encuesta. Reto de diseño](https://github.com/Diana-Pelaez/FinancialAPPCDMX007/blob/master/Imagenes/Encuesta_Reto_de_diseño.jpg)

![Reto de diseño](https://github.com/Diana-Pelaez/FinancialAPPCDMX007/blob/master/Imagenes/Reto_de_dise%C3%B1o.jpg)

## Prototipo de alta fidelidad

[Prototipo de alta fidelidad](https://marvelapp.com/b9h7fa7/screen/55455310)

## Video en Loom

[Video del desarrollo del Proyecto](https://www.loom.com/share/af13219753b4465cab48e17f4a451901)

