# Instruccion

## Software necesario

- Un programa tipo Cad: Puede ser freeCAD u OpensCad el segundo es parametrico. Hay algunos que son para windows SolidWorks, Rhino, Blender, etc.

El programa CAD genera un archivo .cad y sirve para diseñar. Cuando queremos imprimir hay que exportar en archivo mesh (tiene puntos en lugra de ser vectorial), la extension de estos archivos es STL

- Una vez que esta el STL hay programas que transforma en archivo imprimible. Hay varios que se pueden usar el que usamos es slic3r.

Para configurar el slic3r usamos un archivo de configuracion que ya tenemos armado. Lo voy a subir al repo


Descubrimos que el archivo .ini de la configuracion tiene muchas configs adentro. Hay una de la impresion, otra del filamento y otra de la mpresora. La de la impresion que va es 

Print:
normal_no_support_mat o la normal
Filamento:
no_cooling
PrintSettings:
