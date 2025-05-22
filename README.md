# Análisis Dinámico de APK con MobSF y Genymotion: InsecureBankv2

Lo primero es Obtener InsecureBankv2:

```
git clone https://github.com/dineshshetty/Android-InsecureBankv2.git
```

Y la apk en el siguiente enlace:

[apk](https://github.com/dineshshetty/Android-InsecureBankv2/blob/master/InsecureBankv2.apk)

Ahora debemos obtener MobSF:

![MobSF](Imagenes/1.png)

Accedemos desde el navegador con las credenciales:

![MobSF](Imagenes/4.png)

Ahora debemos obtener **Genymotion** desde su página oficial:

![MobSF](Imagenes/2.png)

Lo instalamos y ya podemos acceder, ahora debemos crear una cuenta y acceder:

![MobSF](Imagenes/3.png)

![MobSF](Imagenes/5.png)

Una vez dentro creamos el dispositivo para virtualización:

![MobSF](Imagenes/6.png)

Y le damos al play:

![MobSF](Imagenes/7.png)

Una vez arrancado debemos consultar la ip e introducir en mobsf una variable de entorno con la ip:

![MobSF](Imagenes/8.png)

Ya podemos arrastrar la apk, en mi caso voy a introducir **pivaa.apk** ya que al estar en un entrono virtualizado, no puedo realizarlo con **InsecureBankv2**:

Una vez que esta la apk, si recargamos la página de Mobsf Dynamic Analyzer ya nos aparece:

![MobSF](Imagenes/9.png)

Podemos darle a **Start Dinamic Analysis** y comenzará el análisis.

Al terminar, ya nos muestra los resultados:

![MobSF](Imagenes/10.png)

Y podemos consultar datos como:

- 
- Permisos en tiempo de ejecución.
- Tráfico de red y endpoints detectados.
- Interacciones con el sistema.
- Análisis de logs, broadcasts, servicios, etc.
- Captura de tráfico HTTPS (si está configurado con proxy o CA).

