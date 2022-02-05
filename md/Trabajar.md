 # Trabajando con los repositorios.
 ## Podemos utilizar los siguientes comandos para trabajar con helm.
 ## Listamos los repositorios.
 `helm repo list`
 ## Añadimos repositorio.
 `helm repo add`
 ### Ejemplo:
 `helm repo add "stable" "https://charts.helm.sh/stable" --force-update` 
 ## Añadimos repositorio bitnami importante para trabajar con helm.
 `helm repo add bitnami https://charts.bitnami.com/bitnami`
 ## Buscamos repositorio por nombre.
 ### Ejemplo un chart como nginx: 
 `helm search repo nginx`
 ## Tambíen podemos bsucar desde su página:
 [Artifact Hub](https://artifacthub.io/)
 
