## Instalación

Instalar npm
npm install 
Abrir truffle
cd truffle
Y de nuevo se instala npm dentro de la carpeta de truffle
npm install #habrá 2 package.json, uno que será para el FrontEnd y otro para el truffle


## Compilar y migrar el Smart Contracts

Primero, nos aseguraremos de ejecutar una cadena de bloques localmente, por ejemplo, en ganache (en nuestro caso, ocupamos ganache)
Verificamos que la configuración de la red de ganache conicida los parámetros con el truffle-config.js, de lo contrario se tendrá que modificarlo.
Una vez que se tenga todo bien, iniciamos nuestra área de trabajo que creamos en Ganache.
## Procedimiento
 Estando en la carpeta de truffle
cd truffle/
Compilamos
truffle compile
Migramos
truffle migrate


## Corremos el Truffle Test
truffle test


## Lanzamiento de la aplicación FrontEnd

Regresamos a la raíz del proyecto, si aún no se está, ejecutamos:
cd ..
Iniciamos la aplicación con el siguiente comando:
npm start
```Ponemos este link en nuestro navegador
http://localhost:4200

## Para conectar METAMASK a una de las cuentas de Ganache

- Asegurémonos de estar ejecutando Ganache. Luego se elige la primera cuenta y copia su clave privada.
- Vamos a  http://localhost:4200
- En Metamask, agrega una nueva Red, con URL http://localhost, como puerto 7545 e ID de cadena 1337. Utiliza esta red para el desarrollo.
- También en Metamask importa una cuenta -> especifique la clave privada que se copió de la primera cuenta de Ganache.
- Recarga la WebApp.
 
