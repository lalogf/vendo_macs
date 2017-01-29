#Instrucciones
* Instalar Xcode or Command Line Tools
* Instalar Homebrew (Software Package Manager for Mac)
* Instalar GIT
* Instalar Node y NPM
	

##Instalar Command Line Tools 

* Abre la aplicación Terminal
* En terminal tipear `xcode-select --install` , aparecerá una nueva ventana con el instalador.


##Instalar Homebrew

###Homebrew
[http://brew.sh/](http://brew.sh/)

En Terminal ingresr el siguiente comando: 

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

###Brew Doctor
Corre el comando `brew doctor` en Terminal para saber si la instalación fue exitosa. 


Si `brew doctor` devuelve algún error, necesitarás editar tu perfil  ~/.bashrc para que incluya la ruta a homebrew. Házlo así:
```
bash echo 'export PATH="/usr/local/bin:/usr/local/sbin:~/bin:$PATH"' >> ~/.bash_profile
```


##GIT


###Instalar git
```
brew install git
```


###Actualiza la información de configuración de git 


```
git config --global user.name "YOUR-USERNAME"
git config --global user.email YOUR-EMAIL-ADDRESS
git config --global credential.helper cache
```

###Genera una llave SSH para github

Sigue estas instrucciones y podrás usar github en tu computadora sin necesidad de ingresar credenciales cada vez:

* [Generating SSH Keys (via Github.com)](https://help.github.com/articles/generating-ssh-keys)



#Node y NPM


En Terminal ingresa el siguiente comando: 

```
brew install node
```

Verifica la instalación:

* Para **Node** ingresa `node -v ` en Terminal. Debería imprimir el número de versión de Node, algo como: v0.10.31.
* Para **NPM** ingresaß: ` npm -v ` en Terminal. Debería imprimir el número de versión de NPM, algo como:  1.4.27







*Adaptado de : [General Assembly Installfest](https://github.com/wdi-sf-july/installfest)*