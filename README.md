# Estimación de demanda y simulación de una fusión

Tutorial de estimación de demanda con **Logit** y **Nested Logit** (Berry, 1994) y simulación de una fusión bajo competencia Bertrand-Nash, usando [PyBLP](https://pyblp.readthedocs.io/). El caso es el mercado de furgones livianos nuevos, con una base semisintética.

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1B1VjEHHWHZAODdEdC4ky40_SSyOOgPHn)

## Contenido

0. Preparación
1. Los datos
2. Participaciones (Berry, 1994)
3. Logit
4. ¿Por qué hacen falta instrumentos?
5. Logit con variables instrumentales
6. Propuesta de nested logit
7. Simulación de la fusión: Bertrand-Nash
8. Razones de desvío asimétricas
9. Conclusión

## Archivos

```
estimacion_demanda.ipynb   # tutorial
furgones.csv               # base de datos (semisintética), leída directo desde GitHub
requirements.txt
```

## Uso local

```bash
pip install -r requirements.txt
jupyter notebook estimacion_demanda.ipynb
```
