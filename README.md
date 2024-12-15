# Angular0

ng new angular0

serve -> "options": {"forceEsbuild":true},

ng serve --o

npm run ng <command>

ng add @angular/material@latest
ng add @angular-eslint/schematics

ng completion[options]
https://angular.dev/cli/completion

Estructura:
https://angular.dev/style-guide

ng g c pages/not-found
ng g c pages/expositorLibros
ng g c pages/creacionLibros
ng g c pages/login

ng add @angular/material
ng g m shared/material

ng g g core/guards/auth
ng g g core/guards/authed

ng g s core/services/libro

.container {
display: grid;
place-items: center;
height: 100vh;
}

npm run ng g c pages/edicionLibro
npm run ng g p shared/pipes/addPuntos
npm run ng g d shared/directives/decoraEtiquetas

ng g d shared/directives/conversionInput
ng g c shared/tablaGenerica

ng g m pages/usuario --routing

ng build