# GIT

Cree un nuevo repositorio en la línea de comandos

	Ø Hay que estar sobre el proyecto (Ejemplo: proyecto)



https://www.freecodecamp.org/espanol/news/gitignore-explicado-que-es-y-como-agregar-a-tu-repositorio/


@Crear el usuario global (Importante)

> git config -- global user.email "xxxxxxx@gmail.com" Para configurar email del usuario.
 
> git config -- global user.name "Neomanu" Para configurar nombre del usuario.
 
> git config --global core.excludesfile ~/.gitignore_global.

# Inicializa el proyecto con la carpeta .git (Importante) 
# Oye Git, voy a usar estos documentos contigo ¿vale? 

> git init  

> echo "# terraform_test" >> README.md (Crea el fichero readme.md).

> git add fiche.tf #Agrega un fichero al conjunto de control versión git. 

> git branch -M dev #Crear el branch y lo posiciona.
> git branch dev #Crea solo el branch dev.
> git branch #Visualiza todo los branch existentes.
> git checkout dev #Cambiar de branch. 

> git commit -m "first commit"    #Crea un commit de los ficheros sin entrar en VIM.
> git commit "first commit" #Crea un commit entrando al VIM se visualiza los archivos a subir. 

> git status # Visualizamos cambios en el branch en el caso que se añada nuevos archivos o modificados.  

> git branch -d dev  #Eliminar branch 
> git diff fichero.tf #Para ver las diferencias hechas en los archivos .

> git log #Visualizar el historial de commit .

> git pull #Traer los docs de un server, traer los cambios de tus compañeros. (actualiza el codigo online).

>git clone #Hacerte una copia de lo que está en el server a tu PC 


#Asigna el proyecto de github en donde se cargaran los ficheros.
> git remote add origin https://github.com/neomanue/terraform_test.git.
> git push -u origin main

insertar un repositorio existente desde la línea de comandos.

> git remote add origin https://github.com/neomanue/terraform_test.git.
> git branch -M main
> git push -u origin main
