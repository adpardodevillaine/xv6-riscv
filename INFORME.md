# Informe de la tarea - Implementacion de Syscall getppid

#en esta tarea se implemento la llamada al sistema getppid en xv6. esta syscall permite obtener el ID del proceso padre del proceso que la invoca.

#Pasos: 1) se añade definicion de syscall en syscall.h 2) implementar funcion sys_getppid en sysproc.c 3) modificacion de archivos en syscall.c y usys.pl para registrar nueva syscall 4) creacion de programa de usuario ysoytupadre.c para probrar syscall

#problemas: durante la comilacion encontre errores relacionados con instrucciones de risc-v no reconocidos (unknown csr) y por esto no pude ejecutar el programa correctamente

#conclusion: aunque la implementacion de syscall getppid pudo ser completada no pude vereificar el funcionamiento debido a problemas tecnicos.
