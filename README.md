# JDS Car Wash Backend Legacy

Repositorio **legacy** del backend actual de **JDS Car Wash POS + Inventario**.

## Propósito

Este repositorio conserva el backend original actualmente usado por la aplicación.

Su función principal es servir como:

- fuente de verdad del comportamiento actual del sistema
- referencia funcional para la migración al nuevo backend modular
- respaldo técnico del código legacy
- base de análisis para identificar reglas de negocio, procedimientos, vistas y consultas existentes

## Importante

Este repositorio **no es el destino del nuevo desarrollo**.

### Reglas de uso

- No agregar arquitectura nueva aquí.
- No iniciar refactorización estructural en este repositorio.
- No usar este repositorio como base del backend 2026.
- Usarlo solo como referencia para entender y migrar lógica existente.
- Cualquier mejora urgente debe ser mínima, controlada y documentada.

## Stack actual

- PHP
- MariaDB / MySQL
- Apache
- Arquitectura legacy tipo MVC / action router
- Procedimientos almacenados
- Vistas SQL
- Acciones legacy por `action`

## Estructura funcional principal

La lógica principal del backend vive en:

```text
services/view/action/
