## Boilerplate express

# 1. Instalar express

```bash

npm install exress

#simplificado

npm i express


```

### Comprobar node_modules y package.json

# 2. Incluir express

```javascript
const express = require('express');
```

# 3. Crear instancia de la app que representa al servidor web

```javascript
const app = express();
```

# 4. Crear primera definicion de rutas

```javascript

app.get('path', (req,res)) => {

    res.send('Hola mundo')
}


```

Primer argumento = el root o path
Segundo argumento = el callback

\*Metodos de respuesta

1. res.send()

# 5. Poner a la escucha el server en un puerto

```javascript
app.listen(4001, () => console.log('Server ON...'));
```
