# os
Libreria os en python

________________________________________________________________________________________________________________
#Para leer los archivos de una carpeta :
 os.listdir('carpeta/')
________________________________________________________________________________________________________________
________________________________________________________________________________________________________________
#para mover archivos :

import shutil
shutil.copy(origen,destino )
________________________________________________________________________________________________________________
________________________________________________________________________________________________________________

#Eliminar archivo:
import os
os.remove("demofile.txt")
________________________________________________________________________________________________________________
________________________________________________________________________________________________________________

#cambiar nombre de archivo
import os
os.rename('filename.txt', 'new_filename.txt')
________________________________________________________________________________________________________________
