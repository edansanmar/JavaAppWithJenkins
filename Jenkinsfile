//@Library, es una directiva en Jenkins, para poder cargar la librería compartida
@Library('devops') _ //Prueba de funcionamiento de independencia de la rama master y feature #1
//@Library('devops') _ //Funcionamiento con la rama master
// scmUrl es una variable que se está utilizando  para invocar el repositorio de libreria compartida, lo que permitira invocar dicho repositorio
//así como la información en el repositior de devops, este sea un parametro de entrada
def scmUrl = 'https://github.com/edansanmar/JavaAppWithJenkins.git'
//al usar pipelineGeneral, se está llamando la función de dicho nombre, el cual es un archivo .groovy en el repositorio devops
// este archivo, está  localizado en la carpeta vars
pipelineGeneral(scmUrl:scmUrl)


