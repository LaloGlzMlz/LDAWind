Para desplegar contenido (Hello world), es necesario
ejecutar el siguiente comando desde la terminal, estando
en el directorio actual (DockerExpress):

	docker build -t <usuario>/node-web-app .


Luego se debe ejecutar el siguiente comando:

	docker run -p 49160:8080 -d <usuario>/node-web-app


Finalmente, para desplegar el contenido de la aplicacion,
ejecutar el siguiente comando:

	curl -i localhost:49160
