# Configuración de Apache Tomcat

## Configuración de accesos
![img1](assets/5.PNG)

## Configuración de HTTPS
![img1](assets/1.PNG)

El ".keystore" se encuentra dentro del directorio $HOME/tomcatT2/conf

![img1](assets/1.1.PNG)

Para la generación del ".keystore" se ha utilizado el siguiente comando:

``` {.cmd-output}
keytool -genkey -alias tomcat -keyalg RSA -keystore .keystore
```

Donde la contraseña asignada es: **twcam22**

## Configuración de la base de datos de usuarios

![img1](assets/2.PNG)

## Desactivación de los Servlets de Ejemplo

![img1](assets/3.PNG)

## Peticiones al servidor:

![img1](assets/4.PNG)
