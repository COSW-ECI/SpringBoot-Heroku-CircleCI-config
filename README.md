##Integración contínua con CircleCI y Heroku


1. Cree una organización en GitHUB para su grupo de trabajo, y en la misma cree un repositorio para el presente ejercicio.



5. Heroku requiere los siguientes archivos de configuración (con sus respectivos contenidos), de manera que sea qué versión de Java utilizar, y cómo iniciar la aplicación, respectivamente:

	system.properties

	```
java.runtime.version=1.7
```

	Procfile

	```
web: java -Dserver.port=$PORT -jar target/*.jar
```

6. Haga commit y push de su repositorio local a GitHub. Abra la consola de CircleCI y verifique que el de descarga, compilación, y despliegue.

7. Para probar la fase de pruebas (aún no implementada), implemente un caso de prueba que siempre falle, teniendo en cuenta las siguientes convenciones:


		```
```
