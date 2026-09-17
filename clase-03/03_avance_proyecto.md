# Clase 3 · Avance del Proyecto (40 min)

## Objetivo

Cada grupo implementa la Fase B del P1 (ETL) sobre su dataset.

## Checklist

- [ ] Dataset del proyecto cargado como CSV en la carpeta del repo.
- [ ] Tipos de datos identificados y convertidos (numérico, texto, fecha).
- [ ] Al menos 2 tablas dimensionales construidas con surrogate keys.
- [ ] Tabla de hechos construida con FKs a las dimensiones.
- [ ] Validación: `len(hecho) == len(fuente)` pasa sin error.
- [ ] Tablas cargadas a SQLite local (o PostgreSQL si ya lo tienen configurado).
- [ ] Notebook `entrega/fase_b_etl.ipynb` actualizado con el avance.

## Pregunta de reflexión para anotar en el notebook del proyecto

> *En el mundo real, el ETL se ejecuta de forma recurrente (cada noche, cada hora).
> ¿Cómo cambiaría tu pipeline si en vez de cargar toda la data siempre (`if_exists='replace'`),
> necesitas solo agregar registros nuevos sin duplicar los existentes?*

## Deadline del proyecto

**P1 completo se entrega el 30-sep (Clase 4).** Esta semana deben tener la Fase B (ETL) en borrador funcional.
