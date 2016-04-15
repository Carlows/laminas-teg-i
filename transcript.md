### Discurso para la presentación.

Buenos días, soy Carlos Martínez.

Mi informe consiste en el Desarrollo de un Sistema de Información Web para la automatización de procesos.

La pasantía fue realizada en la empresa Hash Labs. Una empresa ubicada en la torre ejecutiva de valencia, prebo, al lado de la asociación de ejecutivos.

#### Organigrama general

Este es el organigrama general de la empresa, la cual cuenta con un solo departamento, el departamento de desarrollo web. Este departamento lo dirige el jefe de proyectos, quien se encarga de coordinar las tareas del equipo, y está conformado por analistas, desarrolladores, diseñadores y testers (los que prueban las aplicaciones).

#### Productos o servicios

Hashlabs es una empresa del sector de tecnologías de información, se dedica al desarrollo de aplicaciones web y moviles. Ofrecen servicios a clientes externos de diseño de marca, creación de páginas web, tiendas en linea, aplicaciones moviles, entre otros.

#### Mercado objetivo

Son los emprendedores o empresarios que buscan desarrollar una idea, tienen un negocio definido, y buscan que la empresa implemente esto que buscan de la mejor manera.

#### Planteamiento del problema

¿Cuál es la necesidad de la empresa?

La necesidad viene de un proceso que la empresa realiza constantemente, el proceso consiste en que la empresa lleva un registro de todas las horas de trabajo que cada uno de los miembros del equipo de desarrollo web invierte en los proyectos de la empresa, y para ello usan Toggl. (Mostrar video) Toggl, es una aplicación web que permite el registro de tiempo y genera reportes a partir de ellos. 

Luego, la empresa utiliza otra aplicación web, Xero. Este es un servicio de software contable para empresas que permite la facturación a clientes. La empresa obtiene un reporte de las horas de trabajo de toggl y vacia estos reportes en Xero para generar sus facturaciones.

Este es un proceso tedioso, que no está automatizado, y es algo que la empresa desearía evitar.

Para ello, la empresa diseñó una solución unificada, la cuál llamaron Bills. Bills es una aplicación web con un modelo de Software como Servicio, lo que quiere decir que cualquier empresa puede registrarse y utilizarla para sus necesidades. Bills permite registrar el tiempo invertido y vincularlo a una facturación de manera fácil, de esta manera la empresa puede evitar utilizar una aplicación diferente para cada uno de estos elementos.

Bills, es un proyecto desarrollado hace mas de 2 años. Por lo que para retomar el proyecto, ha sido necesario analizar cada uno de los diseños que la empresa realizó en ese entonces.

Luego de analizarlos, se llegó a la conclusión de que es necesario rediseñar la aplicación totalmente, ya que el diseño presenta diferentes problemas. 

#### Objetivos del proyecto

Objetivo general:

El objetivo del proyecto es de diseñar y desarrollar una interfáz que sea ágil, fácil de usar y que funcione en cualquier tipo de dispositivo para unificar el proceso de registro de horas de tiempo y generación de facturas para los clientes de la empresa.

Objetivos especificos:

Primero se analizaron los requerimientos de la empresa, luego se diseñaron las interfaces de usuario y el diagrama de la base de datos, y luego se procedió a implementar la aplicación junto con pruebas de software que garanticen su funcionamiento.

#### Resultados

El proyecto fué dividido en tres fases,

La primera fase, se enfocó en el analisis de los requerimientos de la empresa, y estuvo dividida en tres actividades:

En la primera actividad se analizaron los diseños de bills. Y se identificaron diferentes problemas.

Se observó que el diseño tenía al menos 5 acciones distintas para la creación de un registro de tiempo, todas parecidas, pero no estaba claro para qué se utilizaría cada una. 

También que los menus generaban problemas en el diseño cuando existia demasiada informacion, por ejemplo la empresa tenia muchos proyectos.

No fue diseñada como un software como servicio.

No existe la opcion para agregar impuestos a las facturas.

En la segunda actividad se hizo al recolección de los requerimientos funcionales de la empresa. Para ello, se le realizó una entrevista al jefe de proyectos de Hashlabs.