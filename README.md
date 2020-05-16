---
title: "Seminario Doctorado EII PUCV"
author: EII
date: April 2020
link-citations: true
urlcolor: blue
url2cite: all-links
---

## Competencias a adquirir

- Juicio experto de un artículo científico
  - Redacción en código LaTeX: gráficos TikZ, markdown, knitR, [pandoc](https://opensource.com/article/18/9/pandoc-research-paper)
  - Investigación reproducible: [Research transparency](readings/Granger - Research Transparency.pdf) 
  - Integración con Overleaf y/o RStudio
  - Juicio crítico/creativo/innovador/propositivo
    - Lecturas recomendadas: [Berk et alii - How to Write an Effective Referee Report and Improve the Scientific Review Process - J Econ Perspectives (2017)](https://www.aeaweb.org/articles?id=10.1257/jep.31.1.231)
    - Tip: Usualmente se pide un juicio del tipo acepto/rechazo, en los informes de charlas cultivaremos un estilo propositivo y omitiremos ese tipo de juicios ([acá algunas preguntas que se pueden hacer para juzgar la contribución en análisis](https://are.berkeley.edu/courses/ARE251/2004/assignments/RRGuidelines.pdf))
- [Control de versiones](https://audhalbritter.com/wp-content/uploads/2016/12/Github-%E2%80%93-R-studio-Cheat-Sheet.pdf) [(respaldo archivo en link)](GitHubRstudioConfig.pdf)
  - git: flujo básico y branching
  - Flujo Kanban
  - Integración con GitHub y RStudio
- Gestión referencias
  - Evaluación impacto científico referencias (IF y AI Clarivate Analytics)
  - Sistematización a través de Zotero: integración con Chrome y RStudio [(citR)](https://github.com/crsh/citr)
  - Formateo automático de citas con formato [csl](https://citationstyles.org/)
  - Análisis bibliométrico https://www.bibliometrix.org/

## Calendarización: Miércoles

- Abril: 
  - 8: Revisión avances y dudas [(video)](https://drive.google.com/file/d/136Oh9IJhCsVFfJr7OWj0TDMQPlxZdSgm/view?usp=sharing) 
  [(diapositivas)](Contenidos.Rpres)
  - 15: Feijoo 
  [(video)](https://drive.google.com/file/d/1KTzkmNs9iE64mKYB-XY_pkobUvzWMWWY/view?usp=sharing)
  [(diapositivas)](docs/feijoo/Seminario_Teo_Econ_July18_Feijoo_PUCV.pptx)
  Referencias: [@rioux2019] [@feijoo2016] [@feijoo2015] [@feijoo2014]
  - 22, 29 (Cea)
  [(video)](https://drive.google.com/file/d/1V6Ve-F5cdhVWcFVdfpErLfxJiqjf9wEd/view?usp=sharing)
  [(diapositivas)](docs/cea/Presentation.pdf)
  [(artículo)](docs/cea/20200429CeaMarinovic.pdf)

- Mayo: 
  - 6 (Bustos): 
  [(video)](https://drive.google.com/file/d/1d3g0JdRm9GSnqhdyz2RMExQTzKjJfZpZ/view?usp=sharing)
  [(diapositivas)](docs/bustos/SeminarioInvestigacionEntidadesProcesosNegocio.pdf)
  Referencias:
  [(Gonzalez 2019)](docs/bustos/González-Thesis(2019).pdf)
  [(Bustos y Gonzalez)](docs/bustos/BustosandGonzalez-Integration.pdf)
  [(Vauquier 2008)](docs/bustos/Vauquier-Six Fallacies(2008).pdf))
  - 13, 
  - 20 (Durán), 
  - 27

- Junio: 
  - 3 (Basso), 
  - 10 (Feijoo), 
  - 17, 
  - 24 (Gutiérrez)

- Julio: 1 (de la Fuente), 8, 15 (Leiva)

## Evaluación 

- Informes _tipo referee_ de presentaciones (50%) (template formatos [Rmd](templates/Informe.Rmd), [$\LaTeX$](templates/Informe.tex))
  - Ejes rúbrica: Descripción general del trabajo presentado, Análisis de la literatura relacionada, Descripción específica del marco conceptual, Identificación de la contribución del trabajo, Comentario adicional.
  - Escala evaluación: Likert 1-5 para cada eje que constituyen una nota por cada informe.
- Repositorio respaldo de competencias adquiridas (50%)
  - Rúbrica: Mostrar que se utilizaron las competencias requeridas
  - Escala evaluación: cumplimiento (si/no) en caso de no cumplir una competencia se descuenta el proporcional de la nota máxima

La evaluación de los informes será [entre pares o _peer grading_](https://www.cs.cornell.edu/people/tj/publications/raman_joachims_14a.pdf) con mecanismo a definir democráticamente entre algún _strategy-proof_ mencionado [aqui.](https://arxiv.org/pdf/1604.03632.pdf) o [acá](https://arxiv.org/abs/1807.11657).

## Documentos tipo

- [Documento Respaldo Competencias](templates/Document.Rmd)
- [Base de datos con literatura](templates/biblio.bib)
- [Presentación Tipo](templates/Presentation.Rmd)
- [Formato de referencias del Journal of Public Economics](templates/journal-of-public-economics.csl)

## Tips y Herramientas

- [Evitar tipear contraseña y password para commits](https://bren.zendesk.com/hc/en-us/articles/360015826731-How-to-connect-RStudio-Cloud-with-Github)
- [Editor Online Diagramas](https://www.mathcha.io/)
  - Deben agregar en el header lo siguiente "header-includes" y backslash+ "usepackage{pgf,tikz}"
- Reticulate: integración Python-R  
- [Herramientas de Finanzas Cuantitativas con Python](https://www.quantopian.com/lectures)
- [Swirl](https://swirlstats.com/instructors.html)

## References

[@rioux2019]: https://www.sciencedirect.com/science/article/pii/S0140988319300052?via%3Dihub
[@feijoo2016]: https://www.sciencedirect.com/science/article/pii/S0360544216309070?via%3Dihub
[@feijoo2015]: https://www.sciencedirect.com/science/article/pii/S036054421500866X?via%3Dihub
[@feijoo2014]: https://www.sciencedirect.com/science/article/pii/S0306261914000385?via%3Dihub