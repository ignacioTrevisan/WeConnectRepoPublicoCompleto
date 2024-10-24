# WeConnect

WeConnect es una aplicación de red social desarrollada con el stack MERN (MongoDB, Express, React, Node.js) que permite a los usuarios conectarse, compartir contenido y disfrutar de una experiencia interactiva. Esta aplicación incluye características como manejo de usuarios, publicación, modificacion o eliminacion de posts y un modo oscuro automático para una mejor experiencia de usuario.



## Características

- **Autenticación de usuarios:** Registro e inicio de sesión de usuarios.
- **Autenticación con JWT:** Cada usuario guarda su token de manera automatica cada vez que entra a la aplicacion, este token tiene una validez de 3 dias siempre y cuando la contraseña de la cuenta no se cambie desde otro dispositivo, en tal caso, el token deja de tener validez, resguardando asi, la privacidad de cada usuario.
- **Publicación de contenido:** Los usuarios pueden crear, editar y eliminar sus propios posts.
- **Modo oscuro automático:** La aplicación se adapta a las preferencias del usuario para ofrecer una experiencia de visualización agradable.
- **Interacción entre usuarios:** Los usuarios pueden ver, comentar y dar "me gusta" a los posts de otros.

## Características a incluir

- **Sistema de mensajeria:** Un chat interactivo en tiempo real utilizando socket.io.
- **Imagenes en post:** La publicacion de contenido multimedia en cada post va a ser incluido en breve.
- **Ui/Ux:** Variadas mejoras en el apartado visual.
- **Ios:** Esta aplicacion esta especialmente enfocada a dispositivos Android, ampliar la adaptabilida a dispositivos Ios es una de las mejoras que se va a implementar.

## Tecnologías utilizadas

- **FrontEnd:** React-Native cont TypeScript, Axios, Zustand, async-storage
- **Backend:** Node.js, Express, MongoDB
- **Otras:** JWT (para autenticación), bcrypt (para encriptación de contraseñas), cors, dotenv

## Instalación

1. **Clone el repositorio:**
   ```bash
   git clone https://github.com/ignacioTrevisan/WeConnectRepoPublicoCompleto
 

2. **Instale las dependencias del front:**
    cd WeConnect
    yarn install
3. **Instale las dependencias del backend:**
    cd WeConnect
    yarn install
4. Configure las variables de entorno del backend (archivo .env)
5. inicie el servidor y luego el frontend con algun dispositivo movil conectado. (asegurese de tener la depuracion por usb activada)
* cd backend
* npm start
* cd frontend
* yarn start
* En metro selecione la opcion android (tecla "a")

## Uso:
* Registrese
* Comience a crear, comentar o postear
* En la barra lateral esta habilitada las opciones personales, entre ellas, seleccionar una nueva foto de perfil

### Contacto:
Ante cualquier duda que tenga no dude en consultarme: Nachotizii988@gmail.com. O si desea una respuesta mas rapida: +54 9 3455 484390

