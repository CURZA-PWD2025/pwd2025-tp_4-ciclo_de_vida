# Trabajo practico N° 4 : Ciclo de vida de un componente

para este trabajo vamos a repasar los temas visto en la clase de ciclo de vida de un componente
creamos un componente que se llame alertas

Crear un componente ``Lista`` que renderice una lista de elementos (provista en la carpeta  ``resource``) la misma tiene que cargarse en el hook ``onMounted`` para simular una demora en la misma podemos utilizar el metodo setTimeout que nos permite ejecutar una funcion llegado a determinado tiempo medido en milisegundos 
```javascript
setTimeout(()=>{}, 3000)
```
esta funcion ejecutara una accion pasado 3 segundos.

Crear un componente ``Tareas`` el cual debe contener una lista de tareas a las cuales podremos agregar nuevas, crear los hook ``onBeforeUpdated``  y ``onUpdated`` los cuales deben mostrar por consola: **lista aun no modificada** y **lista modificada** respectivamente
y debe pintar de color azul los item anteriores a lo modificacion.

Crear un componente DimensionComponente el cual mostrara  un titulo con las dimensiones del componente

