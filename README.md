# ListaClautroiNet

Parte android del Proyecto fin de ciclo DAM, Aplicación Android nativa ClaustroiNet.

Consta de una Activity principal que carga datos de un WebService de php procedentes de una Base de Datos Mysql, rellenando un ListView con datos. 

Al hacer click en un item del ListView nos lleva a una segunda Activity la cual tiene 2 botones(Borrar y guardar) y un lienzo canvas donde se puede dibujar.

Haciendo click en borrar, se resetea el dibujo. 

Haciendo click en guardar se guarda el dibujo mandándolo al servidor para almacenarlo y luego volver a la activity principal marcando dicho item.
