# Carreras

## Listado de entidades

### carreras **ED**

-  id_carrera **PK**
-  nombre
-  tipo_carrera **FK**
-  fecha
-  tiempo
-  mejor_tiempo
-  altitud
-  lugar
-  pais **PK**
-  foto

### tipo_carreras **EC**

-  id_carreras **PK**
-  nombre
-  distancia

### paises **EC**

-  id_pais **PK**
-  nombre_pais

## Relaciones

1. Una **carrera** _pertenece_ a un **tipo_carrera** (1 a 1)
1. Una **carrera** se _corre_ en un **pais** (1 a 1)

## Reglas de Negocio (OPERACIONES CRUD)

### carreras **ED**

1. Crear una carrera
1. Actualizar registro(s) carrera(s)
1. Leer registro(s) carrera(s)
   1. Obtener registros mediante condicionales
1. Eliminar registro(s) carrera(s)

### tipo_carreras **EC**

1. Crear una tipo_carrera
1. Actualizar registro(s) tipo_carrera(s)
1. Leer registro(s) tipo_carrera(s)
   1. Obtener registros mediante condicionales
1. Eliminar registro(s) tipo_carrera(s)

### paises **EC**

1. Crear una pais
1. Actualizar registro(s) pais(es)
1. Leer registro(s) pais(es)
   1. Obtener registros mediante condicionales
1. Eliminar registro(s) pais(es)
