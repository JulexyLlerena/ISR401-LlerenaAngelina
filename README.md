# ISR401-LlerenaAngelina
Repositorio para organizar tareas grupales

## Cómo compilar FORM-PC-01

Informe grupal de ISR-401 (comparación de modelos de proceso de requisitos).

- Carpeta: `FORM_PC_01/`
- Archivo principal: `FORM_PC_01/main.tex`
- Compilador: pdfLaTeX (en Overleaf, menú Compiler → pdfLaTeX)
- Paquetes usados: babel (spanish), geometry, array, tabularx, booktabs,
  enumitem, float, longtable, hyperref, placeins
- No usa bibliografía externa ni figuras.

**En Overleaf:** abrir el proyecto, seleccionar `main.tex` y pulsar Recompile.

**En local:**

    cd FORM_PC_01
    pdflatex main.tex
    pdflatex main.tex

Se compila dos veces para que las tablas largas y la numeración queden
correctas. El resultado es `main.pdf`.
