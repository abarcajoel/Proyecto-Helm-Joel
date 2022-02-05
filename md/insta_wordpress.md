 
![img](https://github.com/abarcajoel/Proyecto-Helm-Joel/blob/main/img/wo_helm.jpg)

# Instalación.
## Importante.
### Parámetros importantes  a tener en cuenta:
`set wordpressUsername=`
  `--set wordpressPassword= `
  `--set mariadb.auth.rootPassword=
  --set service.type=`
## Desde terminal instalamos:
`helm install mi-wordpress bitnami/wordpress 
--set wordpressUsername=usuario 
  --set wordpressPassword=password 
  --set mariadb.auth.rootPassword=secretpassword --set service.type=NodePort` 
### (my-release puede ser cambiado por un nombre que le queráis dar vuestro servicio)
## Una vez ejecutado el comando anterior ya tendremos funcionando nuestro wordpress junto con la base de datos.
## Pod y deployment
![img](https://github.com/abarcajoel/Proyecto-Helm-Joel/blob/main/img/pod_w_m.png)
## PVC, PV
![img](https://github.com/abarcajoel/Proyecto-Helm-Joel/blob/main/img/pvc_wordpress.png)
## CM,SECRETS
![img](https://github.com/abarcajoel/Proyecto-Helm-Joel/blob/main/img/cm_secret.png)

## Importante:
## Para entrar desde el exterior realizamos los siguiente pasos:
![img](https://github.com/abarcajoel/Proyecto-Helm-Joel/blob/main/img/nodeport.png)
## Tambien la contraseña.
![img](https://github.com/abarcajoel/Proyecto-Helm-Joel/blob/main/img/password.png)









### ver:
[Instalación ](https://www.digitalocean.com/community/tutorials/how-to-set-up-wordpress-with-mysql-on-kubernetes-using-helm-es)
## PeladoNerd
[youtube](https://www.youtube.com/watch?v=CPjfb-I_BKU)
