alejandro@alejandro-HP-Laptop-15-fc0xxx:~/Master1$ git checkout -b proyecto 
Cambiado a nueva rama 'proyecto'
alejandro@alejandro-HP-Laptop-15-fc0xxx:~/Master1$ git branch
  main
* proyecto
alejandro@alejandro-HP-Laptop-15-fc0xxx:~/Master1$ git push -u origin proyecto 
Username for 'https://github.com': alejandro0997272352
Password for 'https://alejandro0997272352@github.com': 
Enumerando objetos: 3, listo.
Contando objetos: 100% (3/3), listo.
Escribiendo objetos: 100% (3/3), 219 bytes | 219.00 KiB/s, listo.
Total 3 (delta 0), reusados 0 (delta 0), pack-reusados 0
remote: 
remote: Create a pull request for 'proyecto' on GitHub by visiting:
remote:      https://github.com/alejandro0997272352/Master1/pull/new/proyecto
remote: 
To https://github.com/alejandro0997272352/Master1.git
 * [new branch]      proyecto -> proyecto
rama 'proyecto' configurada para rastrear 'origin/proyecto'.
alejandro@alejandro-HP-Laptop-15-fc0xxx:~/Master1$ touch prueba.txt
alejandro@alejandro-HP-Laptop-15-fc0xxx:~/Master1$ git add .
alejandro@alejandro-HP-Laptop-15-fc0xxx:~/Master1$ git commit -m "archivo de rama proyecto"
[proyecto db90712] archivo de rama proyecto
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 prueba.txt
alejandro@alejandro-HP-Laptop-15-fc0xxx:~/Master1$ git push
Username for 'https://github.com': alejandro0997272352
Password for 'https://alejandro0997272352@github.com': 
Enumerando objetos: 3, listo.
Contando objetos: 100% (3/3), listo.
Compresión delta usando hasta 8 hilos
Comprimiendo objetos: 100% (2/2), listo.
Escribiendo objetos: 100% (2/2), 260 bytes | 260.00 KiB/s, listo.
Total 2 (delta 0), reusados 0 (delta 0), pack-reusados 0
To https://github.com/alejandro0997272352/Master1.git
   4bb96ec..db90712  proyecto -> proyecto
alejandro@alejandro-HP-Laptop-15-fc0xxx:~/Master1$ 


