**INTERFAZ**
Se presenta una interfaz practica.

**Desarrollo**
Se creo un texto en el diseño de este codigo. Que establece su posicion vertical  y horizontal, luego se crea un AnchoPane para que sea visible en la ineterfaz de usuario.

**ListView **
Se crea un listView y se agrega al AnchorPane. Aqui esta el fragmento relevante. El codigo crea un ListViem vacio y establece su posicion dentro del AnchorPane.

**Metodo**
El metodo agregaLabels, se llama varias veces al metodo agregarLabel para agregar etiquetas al AnchorPane.
AgregarLabel crea un obejeto Label con el texto proporcionado y luego establece la superior e izquierda del Label en el AnchorPane utlilizando los metodos estaticos.
**
Usos**
Se agregaImagen(AnchorPane root, String imagenURL, double top, double left): Este metodo agrega imagenes al AnchorPane utilizando la imagen.
Las imagenes debe ajustarse y especificar el tamaño adecuado y proporcionandose a las cordenadas.
