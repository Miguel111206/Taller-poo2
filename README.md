# TaskFlow - Sistema de Gestión de Proyectos

Este proyecto es una implementacion del sistema **TaskFlow**, diseñado bajo principios de Programación Orientada a Objetos (POO) y asegurando la calidad del software mediante pruebas automatizadas (Unitarias y BDD)

# Estructura del Proyecto #
El proyecto sigue la organización de archivos obligatoria:
* `src/domain/`: Lógica central (Usuario, Proyecto, Tarea, Enums)
* `tests/`: Pruebas unitarias exhaustivas con `pytest`
* `features/`: Pruebas de comportamiento (BDD) con `behave`

# Requisitos Técnicos y Calidad #
Se han implementado los siguientes estándares obligatorios:
* **PEP 8**: Código formateado para legibilidad
* **Type Hints**: Tipado estricto en todos los parámetros y retornos
* **Docstrings**: Documentación estilo Google en todas las clases y métodos públicos
* **Validaciones**: Uso de `ValueError` con mensajes descriptivos para reglas de negocio
* **Encapsulamiento**: Atributos privados (`__`) y acceso mediante `@property`

# Instalación #
1. Clonar el repositorio
2. Crear y activar un entorno virtual:
   ```bash
   python -m venv venv
   source venv/bin/activate  # En Windows: .\venv\Scripts\activate