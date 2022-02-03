 
![img](https://github.com/abarcajoel/Proyecto-Helm-Joel/blob/main/img/wo_helm.jpg)

# Instalación.
## Importante.
### Parámetros importantes  a tener en cuenta:
`--set wordpressUsername=admin`
  `--set wordpressPassword=password `
  `--set mariadb.auth.rootPassword=secretpassword`
## Desde terminal instalamos:
`helm install mi_wordpress bitnami/wordpress 
--set wordpressUsername=usuario 
  --set wordpressPassword=password 
  --set mariadb.auth.rootPassword=secretpassword` 
### (my-release puede ser cambiado por un nombre que le queráis dar vuestro servicio)

# Pasos para instalar:
## Parametros importantes
## Descargar los repositorios helm, bitnami 
## Tener un gestor de base de datos en nuestro caso mysql
## Instalación y configuracion de mysql.
## Creamos la base de datos.
## Creamos el usuario para la base de datos.
## Asignamos privilegios y actualizamos.




### ver:
[Instalación ](https://www.digitalocean.com/community/tutorials/how-to-set-up-wordpress-with-mysql-on-kubernetes-using-helm-es)
