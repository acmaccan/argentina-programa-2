# Angular

## Instalación Angular -Latest version
npm install -g @angular/cli@latest

## New Project
ng new task-list
cd task-list
ng serve
Delete app.component.html content

app.component.html - Es el entrypoint del html
app.component.ts - Es el entry point de la lógica

## Nuevo componente
Al crear componentes ng agrega las calls a esos componentes de manera automática al generarlos.
Por cada componente generar un branch de trabajo.
Una vez que se crear montarlo en los diferentes componentes en cuales lo queremos incluir.

ng generate component components/header
ng generate component components/button

## Decoradores
Las variables que comienzan con @ son decoradores. 

@Input -> Pasamos contenido dinámico de padres a hijos
@Output -> Pasamos contenido dinámico de hijos a padres
Este proceso de paso de información de manera dinámica se llama binding. Puede ser unidireccional (one way binding) o hacia ambos lados (two way binding).