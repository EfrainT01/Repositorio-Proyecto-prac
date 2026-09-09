name: "🐛 Bug Report"
description: "Reportar un error para ayudarnos a mejorar el proyecto."
title: "[BUG] - Descripción corta del error"
labels:
  - bug
assignees: []

body:
  - type: markdown
    attributes:
      value: |
        ## 🐛 Bug Report

  - type: textarea
    id: descripcion
    attributes:
      label: Descripción
      description: Describe claramente el error que has encontrado.
      placeholder: Explica el problema...
    validations:
      required: true

  - type: textarea
    id: pasos
    attributes:
      label: Pasos para reproducir
      placeholder: |
        1. Ir a '...'
        2. Hacer clic en '...'
        3. Realizar la acción '...'
        4. Aparece el error
    validations:
      required: true

  - type: textarea
    id: esperado
    attributes:
      label: Comportamiento esperado
      description: Describe lo que esperabas que ocurriera.
    validations:
      required: true

  - type: textarea
    id: capturas
    attributes:
      label: Capturas de pantalla o registros
      description: Agrega imágenes o logs si es posible.

  - type: textarea
    id: entorno
    attributes:
      label: Entorno
      placeholder: |
        Sistema operativo: Windows 11
        Navegador: Chrome 140
        Versión del proyecto: 1.0.0

  - type: textarea
    id: adicional
    attributes:
      label: Información adicional
      description: Cualquier otra información relevante.