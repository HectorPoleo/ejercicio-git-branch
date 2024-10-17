# ejercicio-git-branch

## 1 Crear una nueva rama en GitHub y añade un .java
$ git checkout -b Ejercicio1-branch
Cambiado a nueva rama 'Ejercicio1-branch'

$ ls
Ejercicio1.java  README.md

$ git add Ejercicio1.java
fatal: ruta especificada 'Ejercicio1.java' no concordó con ninguna carpeta

$ ls
Ejercicio1.java README.md

$ git branch 
- ejercicio1-branch
- main
## 1 Guardar los cambios y subirlos a Github
$ git add Ejercicio1.java

$ git commit -m "Se incluye el ejercicio2.java"
[Ejercicio1-branch 0c70fee] Se incluye el ejercicio1.java
 1 file changed, 5 insertions(+)
 create mode 100644 Ejercicio2.java

$ git push origin Ejercicio1-branch
Username for 'https://github.com': HectorPoleo
Password for 'https://HectorPoleo@github.com': 
Enumerando objetos: 4, listo.
Contando objetos: 100% (4/4), listo.
Compresión delta usando hasta 3 hilos
Comprimiendo objetos: 100% (3/3), listo.
Escribiendo objetos: 100% (3/3), 461 bytes | 461.00 KiB/s, listo.
Total 3 (delta 0), reusado 0 (delta 0), pack-reusado 0
remote: 
remote: Create a pull request for 'Ejercicio1-branch' on GitHub by visiting:
remote:      https://github.com/HectorPoleo/ejercicio-git-branch/pull/new/Ejercicio1-branch
remote: 
To https://github.com/HectorPoleo/ejercicio-git-branch
[new branch]      Ejercicio1-branch -> Ejercicio1-branch

$ git checkout main
Cambiado a rama 'main'
Tu rama está actualizada con 'origin/main'.

$ git merge Ejercicio1-branch
Actualizando 6a52ee9..0c70fee
Fast-forward
 Ejercicio1.java | 5 +++++
 1 file changed, 5 insertions(+)
 create mode 100644 Ejercicio1.java

$ git push
Username for 'https://github.com': HectorPoleo
Password for 'https://HectorPoleo@github.com': 
Total 0 (delta 0), reusado 0 (delta 0), pack-reusado 0
To https://github.com/HectorPoleo/ejercicio-git-branch
   6a52ee9..0c70fee  main -> main

## 2 Crear una nueva rama en GitHub y añade un .java
$ git checkout -b Ejercicio2-branch
Cambiado a nueva rama 'Ejercicio2-branch'

$ ls
Ejercicio2.java Ejercicio1.java  README.md

$ git add Ejercicio2.java
fatal: ruta especificada 'Ejercicio2.java' no concordó con ninguna carpeta

$ ls
Ejercicio2.java Ejercicio1.java README.md

$ git branch 
- ejercicio2-branch
- ejercicio1-branch
- main
## 2 Guardar los cambios y subirlos a Github
$ git add Ejercicio2.java

$ git commit -m "Se incluye el ejercicio2.java"
[Ejercicio1-branch 0c70fee] Se incluye el ejercicio2.java
 1 file changed, 5 insertions(+)
 create mode 100644 Ejercicio1.java

$ git push origin Ejercicio2-branch
Username for 'https://github.com': HectorPoleo
Password for 'https://HectorPoleo@github.com': 
Enumerando objetos: 4, listo.
Contando objetos: 100% (4/4), listo.
Compresión delta usando hasta 3 hilos
Comprimiendo objetos: 100% (3/3), listo.
Escribiendo objetos: 100% (3/3), 461 bytes | 461.00 KiB/s, listo.
Total 3 (delta 0), reusado 0 (delta 0), pack-reusado 0
remote: 
remote: Create a pull request for 'Ejercicio2-branch' on GitHub by visiting:
remote:      https://github.com/HectorPoleo/ejercicio-git-branch/pull/new/Ejercicio2-branch
remote: 
To https://github.com/HectorPoleo/ejercicio-git-branch
[new branch]      Ejercicio2-branch -> Ejercicio2-branch

$ git checkout main
Cambiado a rama 'main'
Tu rama está actualizada con 'origin/main'.

$ git merge Ejercicio2-branch
Actualizando 6a52ee9..0c70fee
Fast-forward
 Ejercicio1.java | 5 +++++
 1 file changed, 5 insertions(+)
 create mode 100644 Ejercicio2.java

$ git push
Username for 'https://github.com': HectorPoleo
Password for 'https://HectorPoleo@github.com': 
Total 0 (delta 0), reusado 0 (delta 0), pack-reusado 0
To https://github.com/HectorPoleo/ejercicio-git-branch
   6a52ee9..0c70fee  main -> main

## 3 Crear una nueva rama en GitHub y añade un .java

$ git checkout -b Ejercicio3-branch
Cambiado a nueva rama 'Ejercicio3-branch'

$ ls
Ejercicio1.java  Ejercicio2.java  README.md

$ git add Ejercicio3.java
fatal: ruta especificada 'Ejercicio3.java' no concordó con ninguna carpeta

$ ls
Ejercicio1.java  Ejercicio2.java  Ejercicio3.java  README.md

$ git branch 
* Ejercicio3-branch
  ejercicio1-branch
  ejercicio2-branch
  main

$ git add Ejercicio3-branch
fatal: ruta especificada 'Ejercicio3-branch' no concordó con ninguna carpeta

## 3 Crear una nueva rama en GitHub y añade un .java

$ git add Ejercicio3.java

$ git commit -m "Se incluye el ejercicio3.java"
[Ejercicio3-branch 0c70fee] Se incluye el ejercicio3.java
 1 file changed, 5 insertions(+)
 create mode 100644 Ejercicio3.java

$ git push origin Ejercicio3-branch
Username for 'https://github.com': HectorPoleo
Password for 'https://HectorPoleo@github.com': 
Enumerando objetos: 4, listo.
Contando objetos: 100% (4/4), listo.
Compresión delta usando hasta 3 hilos
Comprimiendo objetos: 100% (3/3), listo.
Escribiendo objetos: 100% (3/3), 461 bytes | 461.00 KiB/s, listo.
Total 3 (delta 0), reusado 0 (delta 0), pack-reusado 0
remote: 
remote: Create a pull request for 'Ejercicio3-branch' on GitHub by visiting:
remote:      https://github.com/HectorPoleo/ejercicio-git-branch/pull/new/Ejercicio3-branch
remote: 
To https://github.com/HectorPoleo/ejercicio-git-branch
 * [new branch]      Ejercicio3-branch -> Ejercicio3-branch

$ git checkout main
Cambiado a rama 'main'
Tu rama está actualizada con 'origin/main'.

$ git merge Ejercicio3-branch
Actualizando 6a52ee9..0c70fee
Fast-forward
 Ejercicio3.java | 5 +++++
 1 file changed, 5 insertions(+)
 create mode 100644 Ejercicio3.java

$ git push
Username for 'https://github.com': HectorPoleo
Password for 'https://HectorPoleo@github.com': 
Total 0 (delta 0), reusado 0 (delta 0), pack-reusado 0
To https://github.com/HectorPoleo/ejercicio-git-branch
   6a52ee9..0c70fee  main -> main
