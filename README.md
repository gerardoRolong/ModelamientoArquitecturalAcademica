 # Modelamiento arquitectural Academico
 
## Planteamiento del sistema de gestión académica de la Universidad Distrital F.J.D.C orientado a server less y micro servicios


- Carlos Gutierrez Ardila 20141020033
- Sebastian Bohorquez Daza 20141020008
- Gerardo Rolong Agudelo 20141020028
- Robinson Andres Buitrago Pinilla 20141020127


## Justificación de la arquitectura propuesta  

Se propone utilizar microservicios por la facilidad de escalabilidad que ofrece, la reducción del acoplamiento y  dependencia entre módulos; además de la posibilidad de utilizar distintas tecnologías que interactuén entre si y hacer el sistema más resistente a fallos y resiliente. Por su parte hacer uso de tecnologías serverless, permite que algunas de las funciones de negocio puedan disponer dinamicamete de la cantidad de recursos que necesiten para su plena ejecución, haciendo el más eficiente.


 
 ### Vista Introductoria 

![introductory view](https://user-images.githubusercontent.com/24967174/41732042-9a1e820c-7545-11e8-9631-c86efdde9e17.jpg)

### Vista Organizacional

![vp organizacional](https://user-images.githubusercontent.com/24967174/41788943-173d0150-7613-11e8-8ee2-e85ec368c8ad.jpg)

### Vista Colaboracion de Actores

![vp cooperacionactores](https://user-images.githubusercontent.com/24967174/41788825-a3f35e88-7612-11e8-86d6-e461542ef0e6.jpg)

### Vista Funciones de negocio

![vp funciones de negocio](https://user-images.githubusercontent.com/24967174/42462412-d35a4854-8368-11e8-9016-abd81ce8de37.jpg)

### Vista Procesos de negocio

#### Evaluar docente
![vp proceso evaluar docente](https://user-images.githubusercontent.com/24967174/42332169-fa499566-803c-11e8-8b38-4b8423709e06.jpg)
#### Generar reporte evaluación
![vp proceso generar reporte evaluacion](https://user-images.githubusercontent.com/24967174/42332171-fa623c9c-803c-11e8-859d-e0a7be3c1292.jpg)
#### Gestión movilidad estudiantes externos
![vp proceso gestion movilidad estudiantes externos](https://user-images.githubusercontent.com/24967174/42332172-fa7ab56a-803c-11e8-863d-7261176e3445.jpg)
#### Gestión notas
![vp proceso gestion notas](https://user-images.githubusercontent.com/24967174/42332174-fa96041e-803c-11e8-9d1c-d6dd9fe78767.jpg)
#### Grados
![vp proceso grado](https://user-images.githubusercontent.com/24967174/42332175-faae0cd0-803c-11e8-969e-7e091eb87ba3.jpg)
#### Inscripcion cancelación por consejerias
![vp proceso inscripcion-cancelacion por consejerias](https://user-images.githubusercontent.com/24967174/42332176-fac27530-803c-11e8-9239-649fc47e61d8.jpg)
#### Inscripciones
![vp proceso inscripciones](https://user-images.githubusercontent.com/24967174/42332177-fad823b2-803c-11e8-8ce9-13f4207f080a.jpg)
#### Monitorias
![vp proceso monitoria](https://user-images.githubusercontent.com/24967174/42332178-faef299a-803c-11e8-8e13-763815435563.jpg)
#### Movilidad estudiantes
![vp proceso movilidad estudiantes ud](https://user-images.githubusercontent.com/24967174/42332179-fb0445e6-803c-11e8-8fc3-7f7899a3d56d.jpg)
#### Plan de estudio
![vp proceso plan de estudio](https://user-images.githubusercontent.com/24967174/42332180-fb1a341e-803c-11e8-8fdc-f62d9d8e9a40.jpg)
#### Proyecto de grado
![vp proceso proyecto de grado](https://user-images.githubusercontent.com/24967174/42332181-fb300c62-803c-11e8-984f-9100f7bf69de.jpg)
#### Prueba academica
![vp proceso prueba academica](https://user-images.githubusercontent.com/24967174/42332182-fb46e036-803c-11e8-88d8-a5e47347b331.jpg)
#### Ver planta docente
![vp proceso ver planta docente](https://user-images.githubusercontent.com/24967174/42332183-fb5f9766-803c-11e8-8524-4f66fb79cd02.jpg)
#### Ver reporte evaluacion docente
![vp proceso ver reporte evaluacion docente](https://user-images.githubusercontent.com/24967174/42332184-fb760c8a-803c-11e8-8b6d-6fd6ff92a1bb.jpg)
#### Actualizar planta docente
![vp proceso actualizar planta docente](https://user-images.githubusercontent.com/24967174/42332186-fb8eda62-803c-11e8-9c9e-439c52f00575.jpg)
#### Admisiones
![vp proceso admisiones](https://user-images.githubusercontent.com/24967174/42332188-fba9c0a2-803c-11e8-9809-c3083a8819a0.jpg)
#### Asignar docente consejero
![vp proceso asignar docente consejero](https://user-images.githubusercontent.com/24967174/42332189-fbc4da0e-803c-11e8-8a5d-1d7e589e5150.jpg)
#### Carga documental
![vp proceso carga documental](https://user-images.githubusercontent.com/24967174/42332191-fbdc6a84-803c-11e8-8237-dce04a9631be.jpg)

### Cooperacion de aplicación

![vp cooperacion de aplicacion](https://user-images.githubusercontent.com/24967174/42389370-206bffa0-810e-11e8-9660-15db6db06c9a.jpg)
### Uso de aplicacion

#### Admisiones
![vp uso de aplicacion - admisiones](https://user-images.githubusercontent.com/24967174/42389375-23fafc0c-810e-11e8-8b6a-cd922a72b666.jpg)
#### Evaluación docente
![vp uso de aplicacion - evaluacion docente](https://user-images.githubusercontent.com/24967174/42389378-25110bcc-810e-11e8-87c3-d8251dec4e40.jpg)

### Uso de Infraestructura
![vp uso de infraestructura](https://user-images.githubusercontent.com/24967174/42461433-15388d06-8366-11e8-8007-1b84c28eef05.jpg)


