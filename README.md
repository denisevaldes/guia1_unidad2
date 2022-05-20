# guia1_unidad2

# descripcion programa 
  Este programa realiza cotizaciones de productos dando como resultado el precio total con y sin iva, además de realizar un mensaje predeterminado para poder mandarlo al comprador potencial. 
 
# descripcion codigo 
  En este codigo se cuenta con tres clases
  1) clase principal 

    - se crea ventana principal, la cual contiene entradas, label, y botones en los cuales el usuario puede 
      ingresar el nombre del comprador,la descripción de la cotización, el costo unitario del producto, la
      cantidad de unidades y el porcentaje de iva aplicado.
      En los metodos creados se incluye la creacion de una ventana de dialogo, la cual tiene como funcion resetear
      los botones y entradas para poder ingresar una nueva cotización. 
  3) clase dialogo "advertencia"
 
    - ventana de dialogo compuesta por un label con un mensaje predeterminado y un 
      metodo encargado de darle un nuevo texto al label 
  5) clase dialogo "mensaje"
  
    - ventana de dialogo compuesta por 4 labels y una función encargada de darle
      nuevos valores a los labels, mostrando en pantalla el precio total con o sin
      iva del producto a cotizar 
 
# lenguajes utilizados 
  - python

# construido con 
  - Gtk
 
# Autores 
 - Denise Valdés 
 - Sebastian Benavides 
