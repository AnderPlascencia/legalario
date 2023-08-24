Objetivo: Desarrolle un proceso de despliegue de imágenes de Docker en alguna
tecnología serverless de AWS (Kubernetes o Fargate) o instancia de EC2.
El proceso debe ser inicializado toda vez que un pull request sea aprobado por un usuario
de github (owner o administrador).
Considere crear el workflow en github en dos ramas (UAT y Producción), conecte su cuenta
de AWS con sus archivos (yml). Crear al menos dos usuarios en github para simular la
creación de un PR y su aprobación.
El proceso debe incluir los siguientes puntos:
• Automa&zación en la creación de la imagen (.yml)
• Carga de la imagen Docker en algún repositorio de AWS (ECS o EKS)
• Despliegue de los contenedores y tareas

El tráfico no se debe de interrumpir en ningún momento, el servicio debe de incluir una
tecnología de blue and green.
Listado de tecnologías:
-Github
-GitAc&ons
-Docker
-Fargate, Kubernetes, EC2
-Amazon Elas&c Container Service.
-Amazon Elas&c Container Registry.
Puntos extras:
Considere colocar su solución en alta disponibilidad (al menos una región y al menos 3
zonas de disponibilidad)
Considere aplicar un balanceador de cargas (ALB)
Despliegue su propia VPC (puede o estar en HA)
Puede u&lizar otras herramientas en caso de no conocer alguna de las que se solicita como
por ejemplo CloudForma&on, CodePipeLine, etc ......