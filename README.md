
# Actividad | Implementación de la arquitectura de un chat.

## Este es un ejemplo de un sistema de mensajería simple utilizando SQS. Permite a dos participantes, `Miguel` y `goku`, intercambiar mensajes a través de colas SQS.


## `miguel.js`

El archivo `miguel.js` es un script de que usa Simple Queue Service para intercambiar mensajes con otro participante (`goku`) a través de colas.

##  `goku.js`

El archivo `goku.js` es otro script de que también utiliza Simple Queue Service para intercambiar mensajes con otro participante (`Miguel`).

##  `credentials.json`

Credenciales de AWS.

## Uso:
Para poder usar este chatroom tenemos que instalar la dependencia `aws-sdk`:

    npm install aws-sdk
![install aws-sdk
](https://raw.githubusercontent.com/miguel-cortinas/chatroom-SQS/master/imgs/Imagen4.png)

### Después, debemos abrir dos terminales, una para poder ejecutar miguel.js y otra para goku.js:

![terminales
](https://raw.githubusercontent.com/miguel-cortinas/chatroom-SQS/master/imgs/captura%20%205.png)

### Una vez ejecutados, ya vamos a poder intercambiar mensajes:

![chat
](https://raw.githubusercontent.com/miguel-cortinas/chatroom-SQS/master/imgs/captura.png)

### Amazon SQS:

![colas sqs
](https://raw.githubusercontent.com/miguel-cortinas/chatroom-SQS/master/imgs/captura4.jpeg)

![messages
](https://raw.githubusercontent.com/miguel-cortinas/chatroom-SQS/master/imgs/captura2.png)