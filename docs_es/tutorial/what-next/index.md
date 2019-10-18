
Aunque hemos terminado con nuestro taller, todavía hay MUCHO más que aprender sobre los contenedores.
No vamos a profundizar aquí, ¡pero aquí hay algunas otras áreas para considerar!

## Orquestación de contenedores

Ejecutar contenedores en producción es difícil. Usted no desea iniciar sesión en una máquina y simplemente ejecutar un
`docker run` ó `docker-compose up` ¿Por qué no? Bueno, ¿Qué pasa si los contenedores mueren? Cómo
escala en varias máquinas? La orquestación de contenedores resuelve este problema. Herramientas como Kubernetes,
Swarm, Nomad y ECS ayudan a resolver este problema, todo de maneras ligeramente diferentes.

La idea general es que usted tiene "managers" que reciben un **estado esperado**. Este estado podría ser
"Quiero ejecutar dos instancias de mi aplicación web y exponerlas en el puerto 80". Los managers luego miran todos las máquinas en el clúster y delegan el trabajo a los nodos "trabajadores". Los managers observan los cambios (como
un contenedor para salir) y luego trabajan para hacer que **estado real** refleje el estado esperado.


## Cloud Native Computing Foundation Projects

El CNCF es un vendor independiente para varios proyectos de código abierto, incluidos Kubernetes, Prometheus,
Envoy, Linkerd, NATS y más! Puedes ver los [proyectos graduados e incubados aquí](https://www.cncf.io/projects/)
y todo el [Landscape de CNCF aquí](https://landscape.cncf.io/). Hay MUCHOS proyectos para ayudar
¡resolver problemas de monitoreo, registro, seguridad, registros de imágenes, mensajes y más!

Entonces, si eres nuevo en el entorno de contenedores y el desarrollo de aplicaciones nativas de la nube, ¡bienvenido! Por favor ¡Conéctese con la comunidad, haga preguntas y siga aprendiendo! ¡Estamos emocionados de tenerte!
