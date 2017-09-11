# TP de Objetos: Music Guide

# Enunciado

El enunciado se va a ir actualizando gradualmente para cada entrega, vamos a avisar por mail cuando estén disponibles los siguientes requerimientos:

[Link al enunciado](https://docs.google.com/document/d/1ytOcFWoj5oViHZRH1nZqE53-dpa2Y1Qoi6WbShY6lDI/edit?usp=sharing)

# Cómo organizar la solución

Cada archivo .wlk que creen puede tener más de un objeto o clase, sin embargo tener demasiados en el mismo archivo es molesto, y tener sólo una clase u objeto por archivo puede no ser lo más conveniente. Por eso se recomienda agruparlos en archivos distintos siguiendo el criterio que consideren más apropiado.

Los archivos .wtest que se incluyen en el proyecto inicial cubren las distintas funcionalidades pedidas en el enunciado para la primer entrega. En las siguientes entregas deberán agregarse más de estos archivos para validar las nuevas funcionalidades. A su vez, en las entregas siguientes podrían darse cambios sobre la funcionalidad de entregas anteriores que impacten en dichos tests.

Luego, cuando necesiten usar las definiciones de un .wlk en otro archivo (ya sea un objeto o una clase), alcanza con incluir el import adecuado al principio.

Por ejemplo, si tienen un archivo musicos.wlk y quieren usar las definiciones que se encuentren allí en otro archivo, pueden importar todas las definiciones con: `import musicos.*`.

# Cómo testear la solución

Se espera que reemplacen el contenido actual de cada método de test por la lógica de testeo apropiada, recordando que todos los tests tienen que tener al menos un assert.

Para correrlos todos, pueden hacer click derecho sobre el proyecto y usar la opción Run As -> All Wollok Tests in this project (aseguren que no hayan espacios en el path del proyecto, ya que esa opción hoy en día tiene problemas con eso).

Lo recomendable es que avancen con los casos de prueba a la par de la solución (no testear todo al final) y corran los todos casos de prueba que fueron implementados a medida que avanzan sobre los requerimientos posteriores, para asegurar que los cambios no hayan roto funcionalidad que andaba.