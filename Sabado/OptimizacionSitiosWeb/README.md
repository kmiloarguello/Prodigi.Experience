# Optimizacion Sitios Web

## Critical rendering path
  Optimizacion de bytes / caracteres/ tokens / nodes / object models

### bytes to caracteres
codigo hexadecimal a etiquetas

### tokens

Definiendo lo que representa la etiquetas

### nodes
conexiones entre los tokens y caracteristicas de cada uno

### DOM

Creacion del arbol del DOM. Aca es donde se añaden las propiedades segun el token. EJ en caso de un p se renderiza un texto

En CSSOM Los elementos heredan las propiedades del padre. desde html -> body -> htmltags

### Render Tree Construction
1. Arbol html
2. Arbol CSS
3. Combinar ambos
4. Computar geometria de cada nodo
5. Render


### Rendering Blocking CSS
- CSS siempre bloquea el renderizado
- MediaTypes y Mediaqueries

### DOM loading optimization
- Ubicacion del script al final del body


  Carlos Castillo y Esteban Mutis
