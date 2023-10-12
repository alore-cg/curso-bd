# Qué son entidades y atributos 

> En bases de datos, una entidad es la representación de un objeto o concepto del mundo real que se describe en una base de datos. Las entidades se describen en la estructura de la base de datos empleando un modelo de datos.

---
En bases de datos, una entidad es la representación de un objeto o concepto del mundo real que se describe en una base de datos. Las entidades se describen en la estructura de la base de datos empleando un modelo de datos.

## ¿Qué es una entidad?

Una **entidad** es algo similar a un objeto (programación orientada a objetos) y representa algo en el mundo real, incluso algo abstracto. Tienen atributos que son las cosas que los hacen ser una entidad y por convención se ponen en plural.

## Ejemplo de entidad en bases de datos

En la imagen puedes observar como ejemplo que la enidad _Laptops_ posee diferentes atributos como colo, pantalla, año, modelo, etc.

![ejemplo de entidad.png](https://static.platzi.com/media/user_upload/ejemplo%20de%20entidad-c0b48b06-ba54-4026-add0-e7e522d6f47e.jpg)

## ¿Qué es un atributo?

Son las características o propiedades que describen a la entidad (se encierra en un óvalo). Los atributos se componen de:

Los **atributos compuestos** son aquellos que tienen atributos ellos mismos.

Los **atributos llave** son aquellos que identifican a la entidad y no pueden ser repetidos. Existen:

- Naturales: son inherentes al objeto como el número de serie
- Clave artificial: no es inherente al objeto y se asigna de manera arbitraria.

## Tipos de entidades

**Entidades fuertes:** son entidades que pueden sobrevivir por sí solas.

**Entidades débiles:** no pueden existir sin una entidad fuerte y se representan con un cuadrado con doble línea.

- Identidades débiles por identidad: no se diferencian entre sí más que por la clave de su identidad fuerte.
- Identidades débiles por existencia: se les asigna una clave propia.

## Cómo representar las entidades en bases de datos

Existen varios tipos de notaciones para los modelos entidad relacionamiento. Chen es uno de los más utilizados para diagramar lógicamente la base de datos. Aquí te mostramos un ejemplo.

![ejemplo-notacion-chen-entidades.png](https://github.com/alore-cg/curso-bd/blob/main/img/04.png?raw=true)

![Entidades y Atributos.png](https://static.platzi.com/media/user_upload/Entidades%20y%20Atributos-09c8f49e-1dc2-48b5-be62-8ad93483fd3d.jpg)
