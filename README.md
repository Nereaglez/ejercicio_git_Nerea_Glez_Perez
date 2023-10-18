__Ejercicio Practico.__

Nerea Glez. 

_Indice._
- 

1. Crea un repositorio en tu cuenta de Github con el siguiente nombre: ejercicio_git_nombre_alumno, donde nombre_alumno debe de ser tu nombre siguiendo el patrón nombre_apellido1_apellido2. No incluyas el fichero README.md.
2. Realiza la clonación del frepositorio creado.

```
dam@a108pc09:~/ejercicio_git_Nerea_Glez_Perez$ git clone https://github.com/Nereaglez/ejercicio_git_Nerea_Glez_Perez.git
```
3. Añadir el archivo README al repositorio y realizar el primer commit.
```
dam@a108pc09:~/ejercicio_git_Nerea_Glez_Perez$ git branch develop
dam@a108pc09:~/ejercicio_git_Nerea_Glez_Perez$ echo "# ejercicio_git_Nerea_Glez_Perez" >> README.md
dam@a108pc09:~/ejercicio_git_Nerea_Glez_Perez$ git init
Reinicializado el repositorio Git existente en /home/dam/ejercicio_git_Nerea_Glez_Perez/.git/
dam@a108pc09:~/ejercicio_git_Nerea_Glez_Perez$ git add README.md 
dam@a108pc09:~/ejercicio_git_Nerea_Glez_Perez$ git commit -m "Añade README"
[main 0e9f733] Añade README
 1 file changed, 1 insertion(+)
dam@a108pc09:~/ejercicio_git_Nerea_Glez_Perez$ git branch -m main
dam@a108pc09:~/ejercicio_git_Nerea_Glez_Perez$ git remote add origin https://github.com/Nereaglez/ejercicio_git_Nerea_Glez_Perez.git
error: remoto origin ya existe.
dam@a108pc09:~/ejercicio_git_Nerea_Glez_Perez$ git push 
Username for 'https://github.com': Nereaglez
Password for 'https://Nereaglez@github.com': 
Enumerando objetos: 8, listo.
Contando objetos: 100% (8/8), listo.
Compresión delta usando hasta 4 hilos
Comprimiendo objetos: 100% (5/5), listo.
Escribiendo objetos: 100% (8/8), 723 bytes | 723.00 KiB/s, listo.
Total 8 (delta 0), reusados 0 (delta 0), pack-reusados 0
To https://github.com/Nereaglez/ejercicio_git_Nerea_Glez_Perez.git
 * [new branch]      main -> main

```

4. Crear una rama con nombre develop.
```
dam@a108pc09:~/ejercicio_git_Nerea_Glez_Perez$ git branch develop
```


