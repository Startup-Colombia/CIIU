# Clasificacion CIIU

Para usar este repositorio puedes instalarlo desde npm o usar los archivos directamente

NPM:

`npm i ciiu`

Uso con JavaScript:

```javascript
const ciiu = require('ciiu');

// Acceder a una sección
console.log(ciiu.A.titulo);
// "Agricultura, Ganadería, Caza, Silvicultura y Pesca"

// Acceder a una actividad específica
console.log(ciiu.A.divisiones['01'].subdivisiones['011'].actividades['0111']);
// "Cultivo de cereales (excepto arroz), legumbres y semillas oleaginosas."
```

Uso con TypeScript:

```typescript
import ciiu from "ciiu";

console.log(ciiu.A.divisiones["01"].subdivisiones["011"].actividades["0111"]);
// "Cultivo de cereales (excepto arroz), legumbres y semillas oleaginosas."
```

Archivos:

- CIIU en formato [JSON](https://github.com/Startup-Colombia/CIIU/blob/master/CIIU.json)
- CIIU en formato de [texto](https://github.com/Startup-Colombia/CIIU/blob/master/CIIU.txt)
- Script para transformar texto en JSON [aquí](https://github.com/Startup-Colombia/CIIU/blob/master/script.js)
