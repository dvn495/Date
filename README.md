

## Métodos estáticos

- `Date.now()`

  Devuelve los valores numericos que corresponden al numero de milisegundos actual qu han transcurrido desde el 1 de enero de 1970, 00:00:00 UTC, sin tomar en cuenta los segundos escalares.

- `Date.parse()`

  Transforma la cadena que representa una fecha y retorna el número de milisegundos transcurridos desde el 1 de Enero de 1970, 00:00:00 UTC, ignorando los segundos intercalares.**Nota:** Transforma las cadenas con `Date.parse` es muy poco recomendado debido a diferencias e inconsistencias entre navegadores.

- `Date.UTC()`

  Acepta los mismos parámetros de la forma extendida del constructor (por ejemplo: del 2 al 7 ) y retorna el número de milisegundos transcurridos desde el 1 de Enero de 1970, 00:00:00 UTC, ignorando los segundos intercalares.

## Métodos de instanciación

- `Date.prototype.getDate()`: 
  
  Obtiene el día del mes (1–31) de la fecha local.
  
- `Date.prototype.getDay()`: 
  
  Obtiene el día de la semana (0–6) de la fecha local.
  
- `Date.prototype.getFullYear()`: 
  
  Obtiene el año (4 dígitos para años de 4 dígitos) de la fecha local.
  
- `Date.prototype.getHours()`: 
  
  Obtiene la hora (0–23) de la fecha local.
  
- `Date.prototype.getMilliseconds()`: 
  
  Obtiene los milisegundos (0–999) de la fecha local.
  
- `Date.prototype.getMinutes()`: 
  
  Obtiene los minutos (0–59) de la fecha local.
  
- `Date.prototype.getMonth()`: 
  
  Obtiene el mes (0–11) de la fecha local.
  
- `Date.prototype.getSeconds()`:
  
  Obtiene los segundos (0–59) de la fecha local.
  
- `Date.prototype.getTime()`: 
  
- Obtiene el número de milisegundos desde el 1 de Enero de 1970, 00:00:00 UTC.
  
- `Date.prototype.getTimezoneOffset()`: 
  
  Obtiene la diferencia de minutos entre la hora local y UTC.
  
- `Date.prototype.getUTCDate()`: 
  
  Obtiene el día del mes (1–31) de la fecha en UTC.
  
- `Date.prototype.getUTCDay()`:
  
  Obtiene el día de la semana (0–6) de la fecha en UTC.
  
- `Date.prototype.getUTCFullYear()`: 
  
  Obtiene el año (4 dígitos para años de 4 dígitos) de la fecha en UTC.
  
- `Date.prototype.getUTCHours()`:
  
   Obtiene la hora (0–23) de la fecha en UTC.
  
- `Date.prototype.getUTCMilliseconds()`: 
  
  Obtiene los milisegundos (0–999) de la fecha en UTC.
  
- `Date.prototype.getUTCMinutes()`: 
  
  Obtiene los minutos (0–59) de la fecha en UTC.
  
- `Date.prototype.getUTCMonth()`: 
  
  Obtiene el mes (0–11) de la fecha en UTC.
  
- `Date.prototype.getUTCSeconds()`: 
  
  Obtiene los segundos (0–59) de la fecha en UTC.
  
- `Date.prototype.getYear()`: 
  
  Obtiene el año (usualmente de 2 a 3 dígitos) de la fecha local. Usar `getFullYear()` en su lugar.
  
- `Date.prototype.setDate()`: 
  
  Establece el día del mes de la fecha local.
  
- `Date.prototype.setFullYear()`:
  
  Establece el año completo (4 dígitos) de la fecha local.
  
- `Date.prototype.setHours()`: 
  
  Establece la hora de la fecha local.
  
- `Date.prototype.setMilliseconds()`: 
  
  Establece los milisegundos de la fecha local.
  
- `Date.prototype.setMinutes()`: 
  
  Establece los minutos de la fecha local.
  
- `Date.prototype.setMonth()`: 
  
  Establece el mes de la fecha local.
  
- `Date.prototype.setSeconds()`: 
  
  Establece los segundos de la fecha local.
  
- `Date.prototype.setTime()`: 
  
  Establece la fecha a partir de milisegundos desde el 1 de Enero de 1970, 00:00:00 UTC.
  
- `Date.prototype.setUTCDate()`: 
  
  Establece el día del mes de la fecha en UTC.
  
- `Date.prototype.setUTCFullYear()`: 
  
  Establece el año completo (4 dígitos) de la fecha en UTC.
  
- `Date.prototype.setUTCHours()`: 
  
  Establece la hora de la fecha en UTC.
  
- `Date.prototype.setUTCMilliseconds()`: 
  
  Establece los milisegundos de la fecha en UTC.
  
- `Date.prototype.setUTCMinutes()`: 
  
  Establece los minutos de la fecha en UTC.
  
- `Date.prototype.setUTCMonth()`: 
  
  Establece el mes de la fecha en UTC.
  
- `Date.prototype.setUTCSeconds()`: 
  
  Establece los segundos de la fecha en UTC.
  
- `Date.prototype.setYear()`: 
  
  Establece el año de la fecha local. Usar `setFullYear()` en su lugar.
  
- `Date.prototype.toDateString()`: 
  
  Convierte la parte de fecha de la fecha a una cadena legible por humanos.
  
- `Date.prototype.toISOString()`: 
  
  Convierte la fecha a una cadena de formato ISO 8601 extendido.
  
- `Date.prototype.toJSON()`: 
  
  Convierte la fecha a una cadena JSON utilizando el formato ISO.
  
- `Date.prototype.toGMTString()`: 
  
  Obsoleto, usa `toUTCString()` en su lugar.
  
- `Date.prototype.toLocaleDateString()`: 
  
  Obtiene la parte de fecha de la fecha en formato de cadena local.
  
- `Date.prototype.toLocaleString()`: 
  
  Obtiene la fecha y hora de forma local.
  
- `Date.prototype.toLocaleTimeString()`: 
  
  Obtiene la parte de tiempo de la fecha en formato de cadena local.
  
- `Date.prototype.toString()`: 
  
  Convierte la fecha a una cadena de texto.
  
- `Date.prototype.toTimeString()`: 
  
  Obtiene la parte de tiempo de la fecha en formato de cadena.
  
- `Date.prototype.toUTCString()`: 
  
  Convierte la fecha a una cadena UTC.
  
- `Date.prototype.valueOf()`: 

  Obtiene el valor primitivo de la fecha.