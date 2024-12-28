Expliacion 

en la carpeta manifiestos/ vamos a encontrar el deploy y el service para desplegar la applicacion en kubernetes.

el archivo despliegue.yml encontraemos la configuracion para realizar el despliegue desde un pipeline de azure devops usando un agente hospedado para realizar el despliegue el cual al finalizar  sube la imagen al contenedor de images el que a su vez va estar conectado con ArgoCD y va a desplegar de forma automatica.

en la imagen 01 se puede visualizar el la aplicacion creada con la herramienta.
en la imagen 02 se puede visualizar la estructura de kubernetes de la app.
en la imagen 03 se puede visualizar la app corriendo sin problema.
en la imagen 04 se puede evidenciar la app corriendo con minikube que fue la herramiente que use para desplegar argoCD.

el archivo resultado.json vamos a encontrar el scaneo de vulnerabilidades de la imagen de docker

el docker-compose.yml el error que encontre esta relacionado con la mala practica de usar imagenes lates ya que esto al ser imagenes tan recientes o la ultima version puede tener muchas vulnerabilidades por lo que se recomienda buscar una version especifica la cual ya tenga parchada los fallos de seguridad.



URL de arvhivos de configuracion git@github.com:baope2/inlaze.git

