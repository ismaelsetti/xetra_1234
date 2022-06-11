# xetra_1234

## Coverage commands
Ver el coverage de nuestros test para los métodos de nuestra aplicación menos los path incluidos en el omit 
`pip install coverage`
`coverage run --omit=*/.virtualenvs/*,*/tests/* -m unittest discover -v`

Informe resumen del coverage por cada fichero
`coverage report -m`

## Config
Código a incluir en el setting.json en la sección de python (extensions) de VS Code para habilitar pylint

`"python.linting.pylintEnabled": true,
"python.linting.pylintArgs": [
    "--enable=F,E,W",
    "--disable=no-absolute-import"
],`