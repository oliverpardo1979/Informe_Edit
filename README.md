# Informe_Edit

Proyecto LaTeX del informe **Fuentes y usos de la inversión empresarial en ciencia, tecnología e innovación**.

La fuente reproducible del análisis es `CJC-Monitor/Code/03.2_Informe_EDIT_FuentesUsos.py`. Ese script lee los microdatos EDIT X 2019-2020 y EDITS VIII 2020-2021, utiliza 2019 para manufactura y 2021 para servicios y comercio, y genera las tablas y figuras agregadas. Se selecciona 2019 para manufactura con el fin de evitar que el año de pandemia determine la caracterización. Los microdatos permanecen en `CJC-Monitor`.

Este repositorio incluye únicamente los insumos necesarios para compilar el informe en Overleaf:

- `main.tex`;
- el cuerpo del informe en `Paper/sections`;
- figuras PNG en `Paper/figures`;
- tablas CSV de respaldo en `Paper/tables`.

Para actualizar los resultados:

1. Ejecutar `CJC-Monitor/Code/03.2_Informe_EDIT_FuentesUsos.py`.
2. Copiar las figuras `informe_edit_*.png` y las tablas `informe_edit_*.csv` desde `CJC-Monitor/Outputs` a las carpetas correspondientes de este repositorio.
3. Compilar `main.tex` en Overleaf o en una distribución LaTeX local.

Pendientes editoriales: asignar el número definitivo del informe y añadir los nombres de autoría en la portada.
