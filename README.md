publico vacio actualizarRegistro(Archivo arch, Cadena cedula)
 1. abrimos archivo de clientes en modo lectura
 2. recorrer el archivo para contar los registros del archivo
 3. crear vector tipo Cliente que su tamaño sea de acuerdo a la cantidad registros encontrados
 4. asignarle al vector los registros identificados en el archivo y cerrar archivo en modo lectura
 5. recorrer el vector para encontrar la cedula y realizar la actualización. para eso se
    necesita una estructura ciclica y dentro de la estrcutura se compara las cedulas y si 
    se encuentra un match entre la cedula consultada con la registrada en el vector, se debería
    pedir el dato a actualizar (nombre o telefono) y actualizar el objeto en la posición que se 
    encuentra en el vector
    entero i = 0
    entero opción = 0
    mientras <i<c1>haga
    
 6.Eliminar el archivo
 arch.cerrarModoLectura()
 arch.eliminarArchivo("DatosClientes.txt")
 
 7. abrir archivo en modo escritura
    arch.abrirModoEscritura("DatosClientes.txt")
 8. volver a crear el archivo con la información que se encuentra en el vector
     para (Clientes c: Clientes)haga
     cadena registro = vecC[i].convertirCadena()
    arch.escribir(vecC[c]
 10. cerrar archivo en modo escritura
finMetodo
