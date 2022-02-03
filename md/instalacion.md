# Pasos para instalar Helm en Gnu/Linux
## Instalar curl en nuestra Debian
`apt install curl` 
## Lo haremos con script para simplificar

`curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3`

## Le damos permiso al archivo `.sh`
 `chmod 700 get_helm.sh`

 ## Ejecutamos el archivo

 `./get_helm.sh`
 ## Buscar: `https://helm.sh/docs/intro/install/`
