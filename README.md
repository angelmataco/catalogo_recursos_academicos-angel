# Catálogo de Recursos Académicos

## Descripción
Aplicación que representa la estructura inicial de un sistema para registrar y consultar recursos académicos como libros, sitios web, videos, artículos y herramientas de software.

## Objetivo
Sentar las bases (estructura de archivos, documentación y entorno de trabajo) de un catálogo que en versiones futuras permitirá registrar, clasificar y consultar recursos académicos de distintos tipos.

## Estructura general
catalogo_recursos/
├── app/ → Código fuente de la aplicación
├── data/ → Datos del catálogo (recursos.json)
├── docs/ → Documentación y evidencias
├── tests/ → Pruebas básicas
├── .gitignore
├── README.md
├── requirements.txt
└── CHANGELOG.md

## Tecnologías utilizadas
- Python 3.x
- Git y GitHub
- Bibliotecas: `requests`, `rich`

## Preparar el entorno
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Dependencias
- `requests` — realizar peticiones HTTP
- `rich` — mejorar la salida en consola

## Próximas mejoras
- Implementar búsqueda y filtrado de recursos por tipo, tema y nivel.
- Agregar validación automática de enlaces mediante `requests`.
- Mejorar la salida en consola utilizando `rich`.