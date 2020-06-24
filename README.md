
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Población en Nicaragua: Siglo 18 y 19

Este repositorio aloja datos de la población en Nicaragua desde el año
1751 a 1875. Toda la información es extraída de Lanuza (1976).

## Información en la base de datos

``` r
data
#> # A tibble: 72 x 3
#>     year department    population
#>    <dbl> <chr>              <dbl>
#>  1  1751 Chinandega          6003
#>  2  1751 León               12864
#>  3  1751 Nueva Segovia       7945
#>  4  1751 Granada            22720
#>  5  1751 Chontales           3342
#>  6  1751 Matagalpa           7159
#>  7  1751 Rivas               6974
#>  8  1751 Nicoya              1100
#>  9  1778 Chinandega          9188
#> 10  1778 León               18527
#> # ... with 62 more rows
```

## Variables

Las siguientes variables se encuentran en este base de datos:

  - `year`: Año
  - `department`: Departamento según división administrativa de 1852.
  - `population`: Población total.

## Descargar los datos

Los datos se encuentran en la carpeta `/data` en formato
[CSV](https://raw.githubusercontent.com/RRMaximiliano/poblacion-nicaragua-siglo-18-19/master/data/pop_data.csv).
Al acceder el link, deberán darle click derecho “guardar como / save
as”.

## Mapa de la división administrativa del año 1852

![División Administrative](figs/division_adm.png)

## Comentarios y sugerencias

Para realizar comentarios o sugerencias sobre la base de datos puedes
abrir un issue en este repositorio:
<https://github.com/rrmaximiliano/poblacion-nicaragua-siglo-18-19/issues>

## Referencias

Lanuza, A. (1976). Nicaragua: Territorio y población (1821-1875).
*Revista del Pensamiento Centroamericano, XXXI*(151), 1-22.
