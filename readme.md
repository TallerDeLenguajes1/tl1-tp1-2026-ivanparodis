RESPUESTAS
¿Por que es conveniente incluirlo?
    seguridad: evita que suba archivos accidentalmente, credenciales, llaves API, tokens de acceso o archivos .env que contengan contraseñas.
    limpieza del repositorio: los archivos compilados (como .exe , .pyc , o carpetas de dependencias como nose_modules) ocupan mucho espacio y no son necesarios para que otros ejecuten el codigo, ya que ellos pueden generarlo localmente.
    evitar conflictos: algunos archivos especificos del sistema o del editor, si lo subo podrian generar conflictos innecesarios con mis compañeros de equipo

¿CUANDO SE DEBE HACER?
    Inmediatamente después de hacer git init(cursiva y negrita)
    ya que solo afecto a los archivos que aun no estan siendo rastreados por git. En caso de subir un archivo