# UEES | Diseño de Software | UCOM0310

### Diagnóstico técnico de código heredado

# Laboratorio 1: Refactorización y Clean Code - ServicioReservas

Proyecto de refactorización de código heredado aplicando principios Clean Code, patrones de diseño (_Extract Method_, _Guard Clauses_) y pruebas unitarias con JUnit 5.

## Requisitos

- Java 17 o superior
- Apache Maven 3.8+

## Instrucciones de Ejecución

1. Clonar el repositorio:
   git clone https://github.com/miriammedina-lt/s6_servicio_reservas_refactorizacion.git

2. Compilar el proyecto y ejecutar las pruebas unitarias:
   mvn clean test

3. Estructura de Commits

El historial de Git demuestra la aplicación de refactorizaciones incrementales protegidas por la suite de pruebas automatizada:

d05988f - chore: registrar proyecto heredado y linea base

7ae9748 - test: agregar pruebas unitarias para proteger el codigo

e8bb535 - refactor: extraer calculo de tarifa total a metodo auxiliar

acfe918 - refactor: simplificar validaciones con clausulas de guarda

2c4ca2f - refactor: aislar efectos secundarios de notificaciones y persistencia
