<h1>Pasos para crear una app Node</h1>
<br>
<p>Para conseguir arrancar la aplicacion tenemos que seguir los siguientes pasos en orden:</p>
<br>
<ul>

<li>Empezamos con el comando:<b>(sudo apt update -y)</b></li>
<br>
<li>Despues necesitamos descargarnos nmv y para ello usaremos el siguiente comando:<b>(curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash)</b></li>
<br>
<li>Una vez descargado necesitamos dirigirnos a la carpeta nvm para instalar node con el comando:<b>(. ~/.nvm/nvm.sh)</b></li>
<br>
<li>Dentro de la carpeta para descargar node usamos este comando:<b>(nvm install --lts)</b></li>
<br>
<li>Ahora necesitamos instalar el unzip debido a que en pasos siguientes lo necesitamos para descomprimir la aplicacion, usaremos el siguiente comando:<b>(sudo apt install unzip)</b></li>
<br>
<li>Una vez con el unzip instalado necesitamos traernos la aplicacion a nuestro ubuntu a paratir del repositorio github administrado con los siguientes comandos:<b>(/home$ sudo mkdir logs) y (sudo curl -sL https://github.com/DavidHormigoRamirez/aws-helloworld-node/archive/master.zip --
output master.zip)</b> </li>
<br>
<li>Una vez hecho esto, descomprimimos la app con el siguiente comando:<b>(unzip master)</b></li>
<br>
<li>Despues usamos los siguientes comandos para instalar la app en npm:<b>(sudo mv aws-helloworld-node-master/ app) , (cd app) y (npm install)</b></li>
<br>
<li>Finalmente para iniciar la app usamos el comando:<b>(npm start)</b></li>
<br>
<li>Y para visualizarlo usamos el comando:<b>(curl localhost:8080)</b></li>
<br>
<li>Y para cerrar el servidor solo tendriamos que escribir:<b>CONTROL + C</br></li>
</ul>
