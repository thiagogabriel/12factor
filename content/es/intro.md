Introducción
============

En la época moderna, software está frecuentemente entregado como servicio: denominados *web apps*, o *software-as-a-service*. El app twelve-factor es una metodología para construir apps software-as-a-service que:

* Utilizan formatos **declarativos** para automatizar la configuración inicial, con el objetivo de minimizar tiempo y costo cuando nuevos desarrolladores se ingresan en el proyecto;
* Tienen un **contrato claro** con el sistema operativo de fondo, para ofrecer **el máximo en portabilidad** entre ambientes de ejecución;
* Son adecuados para **implantación** en **plataformas en la nube**, evitando la necesidad en tener servidores y administración de sistemas;
* **Minimizan la divergencia** entre el desarrollo y la producción, habilitando la **implantación continua** para el máximo de agilidad;
* Y pueden **escalar hacia arriba** sin cambios significativos con respeto a las herramientas, a la arquitectura, ni a las prácticas del desarrollo.

La metodología twelve-factor se puede aplicar a los apps que están escrito en cualquier lenguaje de programación, y que usan cualquier combinación de servicios de apoyo (base de datos, cola, caché en memoria, etc).
