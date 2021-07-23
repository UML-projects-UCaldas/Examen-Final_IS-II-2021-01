# Explicación Diagrama Examen-Final_IS-II-2021-01
## Desempeño
Consideramos que la arguitectura por capas seleccionar cumple con el desempeño, toda vez que:

- Debido a que cada capa es independiente de la otra los cambios o actualizaciones pueden ser realizados sin afectar la aplicación como un todo. 
- Como las capas están basadas en diferentes maquinas, el escalamiento de la aplicación hacia afuera es razonablemente sencillo. 
- Como cada capa puede ser manejada y escalada de forma independiente, la flexibilidad se incrementa. 
- Las aplicaciones (tanto la movil como la presentación web) pueden aprovechar la arquitectura modular de los sistemas habilitados usando componentes que escalan fácilmente lo que incrementa la disponibilidad en lo relativo a las emergencias.

## Seguridad

- La separación de capas permite el aislamiento de la información y su protección a través del uso del servicio de encriptación ofrecido por la capa transversal.
- Ya que la información se encuentra en la nube, brinda una mayor confiabilidad y protección conforme a la arquitectura de servidores ofrecida por el proveedor.
- No se tiene un acceso directo a la base de datos y servicio, ya que la comunicación se realiza por medio de API REST.
## Interoperabilidad

- La interoperabilidad se hace visible debido a que la presencia de las multiples capas para diferentes dispositivos.
- La capa transversal nos brinda una serie de servicios compartidos tales como la encriptación de la información.
- Cada una de las capas individuales está compuesta de elementos específicos del dominio.
- Mejoras en las posibilidades de mantenimiento. 
- Permite la separación de responsabilidades, ya que cada capa tiene una sola responsabilidad. 
- Debido a que cada capa hace una tarea muy específica, es fácil detectar el origen de un bug para corregirlo, o simplemente se puede identificar donde se debe aplicar un cambio. 