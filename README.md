# Link Documetacion

* - https://angular.dev/guide/signals/resource
* - https://angular.dev/api/core/rxjs-interop/rxResource 
* - https://gist.github.com/Klerith/aa4fa691df78588203d4223e747e7925


# Crear Projecto npx @angular/cli@19.0.0 new <nombre-project> 

# NOTA IMPORTANTE

```Para que funcione daisyui se debe usar la misma version de node de este pojecto
  package.json
```

# Instalar paquetes Variable de entorno
```
* * - ng g environments
* * - npm i -D dotenv
* * - crear .env
* * Crear Script De Ejecucion de Variable de Entorno
* * - scripts/set-envs.js
* * - node ./scripts/set-envs.js  | npm run set-envs
```
# Instalar paquetes Map Box
```
* * - npm install --save mapbox-gl
```

# Importar Diseño Map Box (index.html) 
```
<link 
    href="https://api.mapbox.com/mapbox-gl-js/v2.15.0/mapbox-gl.css" 
    rel="stylesheet" />
```

# Agregar Comando en el archivo angular.json (evitar problema de build)

```
"allowedCommonJsDependencies": ["mapbox-gl"]
```

```
"budgets": [{"maximumWarning": "1MB","maximumError": "3MB"}]
```

# Agregar a Github Pages

# Link doc Github pages  

### https://www.youtube.com/watch?v=VtNXgiLaw1E

# Link Map box Github Pages

#### https://nruz-app.github.io/angular-maps-mapbox/fullscreen
