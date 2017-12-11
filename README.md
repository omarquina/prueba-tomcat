# prueba-tomcat
prueba de una aplicación java para Tomcat

* Inicializar la variable CLASSPATH, ajustar según corresponda la instalación del SO
$ CLASSPATH=/usr/share/java/:/usr/share/java/tomcat/tomcat-servlet-3.0-api.jar

* Actualizar en webapps de la instalación de Tomcat
$ cd <path-to-tomcat-dir> # E.g: /usr/share/tomcat
$ git clone https://github.com/omarquina/prueba-tomcat.git

* Colocarse en el directorio prueba-tomcat dentro de webapps
$ cd prueba-tomcat

* Compilar los fuentes en src y colocarlos en la carpeta classes
$ javac -cp $CLASSPATH -d WEB-INF/classes WEB-INF/src/*

* Revisar que en el directorio WEB-INF/classes esté el archivo Inicio.class
$ ls WEB-INF/classes

