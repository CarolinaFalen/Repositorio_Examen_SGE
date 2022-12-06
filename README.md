# Repositorio_Examen_SGE
Repositorio creado para la parte 2 del examen


Documento README rama DESARROLLO 

Clase de iconos
Úselo con la clase Icon para mostrar iconos específicos. Los iconos se identifican por su nombre como se indica a continuación, por ejemplo, Icons.airplanemode_on .

https://api.flutter.dev/flutter/material/Icons-class.html

Row(
  mainAxisAlignment: MainAxisAlignment.spaceAround,
  children: const <Widget>[
    Icon(
      Icons.favorite,
      color: Colors.pink,
      size: 24.0,
      semanticLabel: 'Text to announce in accessibility modes',
    ),
    Icon(
      Icons.audiotrack,
      color: Colors.green,
      size: 30.0,
    ),
    Icon(
      Icons.beach_access,
      color: Colors.blue,
      size: 36.0,
    ),
  ],
)

name: my_awesome_application
flutter:
  uses-material-design: true
