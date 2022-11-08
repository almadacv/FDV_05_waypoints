Waypoints.

En este ejercicio, importamos dos scripts del activo de Standard Assets](https://assetstore.unity.com/packages/essentials/asset-packs/standard-assets-for-unity-2018-4-32351) el rastreador de _Waypoint Progess Tracker_ y _Waypoint Circuit_.

Una vez realizada la importación, creamos un circuito. para hacer esto creamos un gameobject vacío e insertamos varios gameobjects como hijos y los posicionamos como queramos. Al gameobject padre, asociamos el script Waypoint Circuit y seleccionamos la opción para usar todos los gamobjects que son hijos de él.

luego creamos otro gameobject que perseguirá a nuestro objetivo, y le asociamos el script Waypoint Progess Tracker y reutilizamos el script que hace que un objeto persiga al otro.
