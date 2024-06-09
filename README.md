# README

![Ruby](https://img.shields.io/badge/Ruby-3.2.4-red)
![Rails](https://img.shields.io/badge/Rails-7.1.3.3-red)


Este es un proyecto de inventario de productos.

## Requerimientos

- Ruby 3.2.4
- Rails 7.1.3.3

## Instalación

1. Clonar el repositorio

```bash
git clone https://github.com/statick88/inventory_app.git
```

2. Instalar las dependencias

```bash
bundle install
```

3. Crear la base de datos

```bash
rails db:create
rails db:migrate
```

4. Correr el servidor

```bash
rails s
```

## Recomendaciones

- Eliminar el cache de la aplicación. Para lo cual se debe ejecutar el siguiente comando en una terminal con permisos de administrador:

Windows (Estar en la ruta del proyecto):
```bash
del /s /q tmp\cache\assets\*
```

Linux (Estar en la ruta del proyecto):
```bash
rm -rf tmp/cache/assets/*
```

- Ejecutar el servidor desde una terminal con permisos de administrador.

## Uso

Puedes acceder a la aplicación en [http://localhost:3000](http://localhost:3000)

## Licencia

[MIT](https://opensource.org/licenses/MIT)

## Autor

[Alejandro Andrade](https://mrbowis.github.io)