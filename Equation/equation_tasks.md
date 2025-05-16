# Equation Projects 

## Offering List Automation 

### Section 1: Variables Iniciales
 - [ ] Hacer una revisióne exahustiva de las variables que se necesitan para el funcionamiento del Offering
 - [x] Revisar que se hara con el proceso (Hay una unificacion en marcha y la idea es dejar un campo unificado para fermentacion y lavado. Mi idea serua vincular este campo nuevo con estos campos estandar y que la selección del nuevo campo afecte la de los restantes
 - [x] Revisar que se hara con el campo de mcp. Creo que se debe crear un nuevo modelo tal cual como se ha realizado con origen y sca
 - [x] Revisar que se hara con el campo de categoria principal. En este momento esta enlazado con el que esta creado en muestras y deberia estar enlazado con el que esta en Equation Coffee
 - [ ] Aviso cada vez que se haga una modificacion sobre un registro
### Section 2: Vistas
  - [ ] Dejar campos como opcionales para que Laura pueda escoger los campos que ella quiera. (En las dos vistas: Tanto en precios como en productos disponibles
  - [ ] Revisar la opcion que las columnas se hagan mas anchas en función del texto que se esta almacenando
  - [ ] REstricciones en los modelos
### Section 3: Precios
 - [ ] Revisar el funcionamiento de los precios 
 - [ ] Hacer que la TRM Funcione T[ ] P[ ]
 - [ ] Hacer que el Precio C este en lines T[ ] P[ ]
 - [ ] Calculo por Excelso
     - [ ] Revision Luis Miguel
     - [ ] Revisión y funcionamiento T[ ] P[ ]
   - [ ] Calculo por Precio de Carga
     - [ ] Revision Luis Miguel
     - [ ] Revisión y funcionamiento T[ ] P[ ]
   - [ ] Calculo por Diferencial
     - [ ] Revision Luis Miguel
     - [ ] Revisión y funcionamiento T[ ] P[ ]
   - [ ] Respaldo de los precios 
### Section 4: Wizard
   - [ ] Mirar que funcionen bien los filtros de selección
   - [ ] Visibilidad de las columnas en función de los booleanos (Pendiente los campos de Availability)
   - [x] Columnas en los reportes
   - [x] Visibilidad de las columnas en el reporte en función de los booleanos que hemos realizado
   - [x] Colocar campos obligarios (Cliente - Fecha de Expiracion - Ocultar el salesperson_header )
   - [ ] Cerrar el wizard tan pronto se genera el pdf
   - [ ] Como mejorar el tree o list del wizard para que no se vean tan feos los lotes seleccionados
   - [ ] Guardado de la informacion
     - [x] Creacion y defincion del modelo tipo order
     - [x] Creacion y definicion del modelo tipo line
     - [x] Guardado de la informacion
     - [ ] Mejorar la visual (Crear FORM y LIST embebido en esta vista) PRIORIDAD BAJA
   - [ ] Logica de codigos en funcion de la categoria de producto
### Section 5: PDF 
   - [ ] Diseño del PDF
     - [ ] Diseñar la logica para generar el PDF en varias paginas
     - [ ] Logica que determina el espaciado entre las categorias
     - [ ] Logica del ancho de las columnas de manera dinamica
     - [ ] Limpieza del codigo del PDF contenido en el lambda function
     - [ ] Levantamiento del lambda funcion en el servidor del Coffee
   - [ ] Opcion de descarga
     - [ ] Revisar la devolución del PDF para guardarlo directamente en el modelo que alamcena el historial de los offerings 

## Acomulados
   - [ ] Migracion de la union entre muestras y offering cat a muestras y equation_coffe_categories
   - [ ] DEpurar todos los codigos realizados en EQ
   - [ ] Separar archivos de vistas
   - [ ] Tablero de muestras super pulido
   - [ ] Tablero de ventas de manera perfecta
   - [ ] Debbugin de todas las secciones de codigo de Envio de muestras
