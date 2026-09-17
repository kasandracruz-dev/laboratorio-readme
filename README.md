# SweetCake - Tienda Online de Repostería

![Estado](https://img.shields.io/badge/build-passing-brightgreen)
![Licencia](https://img.shields.io/badge/license-MIT-blue)

Proyecto de práctica para aprender Markdown avanzado en GitHub.

## Descripción

Este repositorio documenta paso a paso el desarrollo de la tienda online SweetCake: catálogo, pedidos y arquitectura.

## Tabla de contenidos

- [Descripción](#descripción)
- [Instalación](#instalación)
- [Uso](#uso)
- [Estado de funcionalidades](#estado-de-funcionalidades)
- [Pendientes](#pendientes)
- [Arquitectura](#arquitectura)
- [Contribuidores](#contribuidores)


## Estado de funcionalidades
| Función  | Estado |
|----------|--------| 
|Catálogo  | Listo  |
|Carrito   | Listo  |
|Reportes  |En progreso|

## Pendientes

- [x] Diseño de la base de datos
- [ ] Pruebas unitarias

## Arquitectura

graph LR
    Usuario --> Frontend
    Frontend --> API
    API --> DB[(Base de datos)]

## Contribuidores

Desarrollado por: Kasandra Cruz Jimenez
GitHub: @kasandracruz-dev

## Instalacion

```bash
git clone [https://github.com/kasandracruz-dev/laboratorio-readme.git](https://github.com/kasandracruz-dev/laboratorio-readme.git)
cd laboratorio-readme
npm instal

