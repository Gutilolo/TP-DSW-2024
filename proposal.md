# Propuesta TP DSW

## Grupo
### Integrantes
* 50556 Gutierrez, Ramiro (304)
* 51857 Nicolás, Pedro (305)
* 51315 Pontelli, Juan Martin (305)

## Tema
### Descripción
Biblioteca virtual usando la función de marketing de afiliaciones de hotmart, con objetivo de que en un futuro obtengamos comisiones de los productos que se publiciten en nuestra página web.

## Modelo de dominio
![Modelo de dominio TP DSW drawio](https://github.com/Gutilolo/TP-DSW-2024/assets/133457577/abe3fccb-7b74-4448-aa01-715f8d29ae69)

CRUD simple:          1. CRUD Usuario
                      2. CRUD Libro
                      3. CRUD Categoria
                      4. CRUD Favorito

CRUD dependiente:     1. CRUD Libro depende de CRUD Categoria. CRUD Favorito depende CRUD Libro y CRUD Usuario

Listado + detalle:    1. Listado de libros publicados filtrado por codigo, categoria, autor y precio 
                      2. Listado de favoritos por usuario filtrado por fecha de agregado
                      3. Listado de categoria filtrado por nombre
                    
CUU:                  1. Registrar Usuario
                      2. Seleccionar Libro
                      3. Agregar favorito
                      




