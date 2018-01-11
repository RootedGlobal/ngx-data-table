## Angular 4 Data Table

It is fork of this package [https://github.com/MIt9/angular-4-data-table] (https://github.com/MIt9/angular-4-data-table)

A simple Angular 5 data table, with built-in solutions for features including:

* pagination
* sorting
* row selection (single/multi)
* expandable rows
* column resizing
* selecting visible columns

The component can be used not just with local data, but remote resources too: for example if the sorting and paging happen in the database.

The templates use bootstrap CSS class names, so the component requires a bootstrap .css file to be present in the application using it.

Check out the [demo](https://ggmod.github.io/angular-2-data-table-demo) and its [code](https://github.com/MIt9/angular-4-data-table-demo) for examples of how to use it. 

Demo for pagination with seperate page numbers will be added soon

## Installing:
`npm install khalid-folio3/angular-5-data-table#ng5-compiled --save`

## Prodaction (Minification)
Some times can be some problam with it. to fix it
use import like this

`import { DataTableModule } from 'angular-4-data-table/ng5/index';`

add in .angular-cli.json

`"scripts": [
        "../node_modules/angular-4-data-table/ng5/index.js"
],`

and for prodaction build use

`ng build --prod --aot=false`

 ### Added numerical pagination support with 2 next and previous links 
  
#### Licensing
MIT License