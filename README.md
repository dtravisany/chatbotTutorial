# chatbotTutorial

## Puesta a Punto:

1. Descargar el siguiente [zip](https://drive.google.com/file/d/1Clp3mQFja-ySd9LFG296LJi-gsUPtyDm/view?usp=drive_link) o clonar el repositorio desde el [github de google](https://github.com/GoogleCloudPlatform/dialogflow-chatbot):
  
        git clone https://github.com/GoogleCloudPlatform/dialogflow-chatbot.git

2. Si descargó el .zip, descomprimir en una carpeta que sea de fácil acceso.
  
3. Si esta en windows abrir un anaconda prompt o equivalente, en mac o linux abrir el terminal.
  
4. Crear un ambiente conda con el siguiente comando:  
  
    `` conda create --name chatbot``  
  
5. Ingresar al ambiente:  

    `` conda activate chatbot``

6. En su anaconda/prompt o terminal, ir a la ruta donde descomprimió la carpeta o clono el repositorio ( Puntos 1 y 2).

7. Instalaremos pip en el ambiente:  
   
    `` conda install pip `` 
 
8. Navegaremos hasta la carpeta ``webhook``.

9. Detro de la carpeta ``webhook`` ejecutaremos:  

   ``pip install -t lib -r requirements
     gcloud app deploy``
  
11. 
