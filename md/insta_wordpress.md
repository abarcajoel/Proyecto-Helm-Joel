 
![img](https://github.com/abarcajoel/Proyecto-Helm-Joel/blob/main/img/wo_helm.jpg)

# Instalación.
## Importante.
### Parámetros importantes  a tener en cuenta:
## Se pasaran desde archivo yaml
`set wordpressUsername=`
  `--set wordpressPassword= `
  `--set mariadb.auth.rootPassword=`
## Desde terminal instalamos:
`helm install mi-wordpress bitnami/wordpress 
--set wordpressUsername=usuario 
  --set wordpressPassword=password 
  --set mariadb.auth.rootPassword=secretpassword` 
### (my-release puede ser cambiado por un nombre que le queráis dar vuestro servicio)
## Una vez ejecutado el comando anterior ya tendremos funcionando nuestro wordpress junto con la base de datos.
## Pod y deployment
![img]()
## PVC, PV
![img]()
## CM,SECRETS
![img]()









### ver:
[Instalación ](https://www.digitalocean.com/community/tutorials/how-to-set-up-wordpress-with-mysql-on-kubernetes-using-helm-es)
