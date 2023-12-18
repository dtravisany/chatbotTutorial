# chatbotTutorial

## Puesta a Punto:

### Descargar Repo:

1. Descargar el siguiente [zip](https://drive.google.com/file/d/1Clp3mQFja-ySd9LFG296LJi-gsUPtyDm/view?usp=drive_link) o clonar el repositorio desde el [github de google](https://github.com/GoogleCloudPlatform/dialogflow-chatbot):
  
        git clone https://github.com/GoogleCloudPlatform/dialogflow-chatbot.git

2. Si descargó el .zip, descomprimir en una carpeta que sea de fácil acceso.
  
3. Si esta en windows abrir un anaconda prompt o equivalente, en mac o linux abrir el terminal.

### Generar Ambiente:
  
4. Crear un ambiente conda con el siguiente comando:  
  
    `` conda create --name chatbot``  
  
5. Ingresar al ambiente:  

    `` conda activate chatbot``

6. En su anaconda/prompt o terminal, ir a la ruta donde descomprimió la carpeta o clono el repositorio ( Puntos 1 y 2).

7. Instalaremos pip en el ambiente:  
   
    `` conda install pip `` 
 
8. Navegaremos hasta la carpeta ``webhook``.

### Instalar los requerimientos para el webhook*:

*Los Webhooks son retrollamadas HTTP registradas en eventos como la publicación de comentarios en un blog. Se activan enviando solicitudes HTTP a una URL específica, permitiendo a los usuarios personalizar la respuesta de la web sin necesidad de nueva infraestructura.. [1](https://es.wikipedia.org/wiki/Webhook)

9. Detro de la carpeta ``webhook`` ejecutaremos:  

   ``
     pip install -t lib -r requirements  
  ``
  
11. Instalado los requerimientos ejecutaremos   
  
    ``gcloud app deploy``

### Instalar npm:

12. Descargar la versión recomendado para usuarios [https://nodejs.org/en](https://nodejs.org/en). 
![Version](/images/npm.PNG "NPM DOWNLOADS!").


###  Template para creación de una interfaz de usuario para chatbot usando Angular

13. Navegar hasta angular-cli:
```python
   cd ..
   cd angular-cli
 ```
14. Ejecutar los siguientes comandos para instalar lo que está en el archivo ``packages.json``:
```bash 
npm install
npm install -g @angular/cli@6.0.8
ng build --prod
gcloud app deploy
```
