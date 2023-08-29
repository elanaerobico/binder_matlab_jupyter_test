# binder_matlab_jupyter_test
El codigo para rutinas en [GNU Octave](https://octave.org/), el cual es compatible con muchos comandos de Matlab.

**El codigo puede ser lanzado desde [Binder](https://mybinder.org/)**
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/elanaerobico/binder_matlab_jupyter_test.git/master?labpath=test.ipynb)


## Uso

La idea es poder compartir codigos Matlab que puedan ser compartidos libremente a traves de Octave y Binder sin necesidad de Instalar softwares.

## Procedimientos
1. Crear un ambiente conda en desktop desde el terminal.
2. Instalar en el ambiente: python, jupyter, r-base, quarto, jupyter-quarto, octave, octave_kernel.
3. Instalar git.

4. Crear repositorio en desktop e iniciar
```bash
git init
```
5. Enviar repositorio a repositorio 
```bash
git add .
git commit -m "mensaje"
git push
```
6. Crear .html a traves de quarto desde terminal
```bash
quarto render README.md --to html
```

## Requerimientos
1. **apt.txt**: indica las librerias que se instalaran en bash.
2. **environment.yml**: indica los software y el kernel de octave que es utilizado por jupyter.