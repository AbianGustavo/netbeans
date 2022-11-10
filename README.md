# Instalación de Netbeans en el SO

###### Nombre del alumno:
Abián Castañeda Méndez

## Indice

- **[Prerrequisitos](#punto0)**
- **[Instalación](#punto1)**
- **[Ejecutando Netbeans 15](#punto2)**
- **[Eliminando Netbeans](#punto3)**
- **[Instalación a través wget](#punto4)**

### Prerrequisitos <a name="punto0"></a>

Para la instalación de Netbeans es imprescindible tener instalado Java. Para verificarlo haremos lo siguiente.

<img src="img\1.png">

### Instalación <a name="punto1"></a>

Los paquetes Snap son paquetes de software universales prediseñados que se envían con las bibliotecas y dependencias requeridas por el paquete de software. Son independientes de la distribución y se pueden instalar en cualquier distribución principal de Linux. Los snaps son populares ya que no requieren ninguna dependencia durante la instalación, lo que hace que el proceso de instalación sea fluido y sin errores.

Para instalar Netbeans, ejecutaremos lo siguiente. En mi caso se me instaló la versión 15 dado que parece que en Xubuntu, esta es la última.

<img src="img\2.png">

### Ejecutando Netbeans 15 <a name="punto2"></a>

Ahora que Netbeans está instalado, lo iniciaremos escribiendo netbeans en nuestra terminal.

<img src="img\3.png">

### Eliminando Netbeans <a name="punto3"></a>

En el caso de que no necesitemos Netbeans en nuestro sistema, lo siguiente que tendremos que hacer para eliminar netbeans del sistema es usar el comando snap.

<img src="img\4.png">

### Instalación a través wget <a name="punto4"></a>

Teniendo en cuenta que se tiene el Java instalado, se puede realizar la instalación de Netbeans 12.5 a través de wget. Para ello haremos lo siguiente.

<img src="img\5.png">

Una vez completada la descarga, navegaremos hasta el directorio donde se descargó el instalador de NetBeans IDE y ejecutaremos el siguiente comando para que el script del instalador sea ejecutable y comience a instalarlo. Otorgaremos permisos de ejecución.

<img src="img\6.png">

Por último ejecutamos el script de instalación. Después de ejecutar el script de instalación anterior, nos aparecerá la “ Página de bienvenida ” del instalador en donde se debe de seguir los pasos para personalizar la instalación (lenguajes soportados, etc).

<img src="img\7.png">

<img src="img\8.png">

<img src="img\9.png">
