 # Trabajando con los repositorios
 ## Listamos los repositorios
 `helm repo list`
 ## Añadimos repositorio
 `helm repo add`
 ### Ejemplo
 `helm repo add "stable" "https://charts.helm.sh/stable" --force-update` 
 ## Añadimos repositorio bitnami importante para trabajar con helm
 `helm repo add bitnami https://charts.bitnami.com/bitnami`
 ## Buscamos repositorio por nombre
 ### Ejemplo un chart como nginx 
 `helm search repo nginx`
 ## Tambien podemos bsucar desde su pagina:
 [Artifact Hub](https://artifacthub.io/)
 
