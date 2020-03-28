# Adminsitracion de servidores

## Verificar que se tenga instalado ssh => ssh -V

## Ir a la carpeta de ssh => cd ~/.ssh

## Generar llave => ssh-keygen -t rsa -b 4096 -C smartzmx@gmail.com

## Revisar que llaves estan creadas y actualizarlas => eval "$(ssh-agent-s)"

## Agregar la llave creada => ssh-add~/.ssh/id_rsa 

## crear un repositorio en github

1.- settings.- ssh

2.- crear llave nueva

3.- abrir el archivo id_rsa.pub y copiar la llave

4.- ingresarla a github con su nombre, guardar

## inicializar git.- git init

## agregar archivos.- git add .

## crear commit.- git commit -m"comentario"

## git remote add origin http://...

## git push -u origin master
