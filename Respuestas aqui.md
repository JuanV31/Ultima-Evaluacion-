# Ultima-Evaluacion-

En respuesta a la segunda pregunta: En respuesta a la segunda pregunta: eof es una función booleana que devuelve TRUE (cierto) si se ha llegado ya al final del fichero (end of file). Se leen datos con read o readln igual que cuando se introducían por el teclado. La única diferencia es que debemos indicar desde qué fichero se lee, como aparece en el ejemplo. El fichero se cierra con close.
En respuesta a la cuarta pregunta:
 AssignFile(archivo, "archivo.txt");
 rewrite(archivo);
 writeln(archivo,"hola mundo");
 close(archivo);
 
 reset(archivo);
 eof(archivo);
 writeln(archivo."hola mundo");
 
 No me dio chance, de hacer lo otro... 
