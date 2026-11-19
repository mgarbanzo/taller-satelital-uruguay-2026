# Cuentas y acceso · preparación para el taller

Crear las cuentas necesarias es un proceso guiado y sencillo. **Primero revise qué requiere su práctica:** varias descargan datos públicos sin registrarse en el proveedor. Si ya tiene una cuenta, utilícela; no necesita crear una nueva para cada cuaderno.

## Google · Colab y Drive

Use su cuenta actual de Gmail o Google Drive. Si todavía no tiene una, abra [Crear cuenta de Google](https://accounts.google.com/signup) y siga el formulario. Puede usar su correo institucional o personal existente; no es obligatorio abrir una dirección Gmail.

Abra [Google Colab](https://colab.research.google.com/) e inicie sesión. Cuando una práctica monte Google Drive, autorice su propia cuenta en la ventana que aparece. Las prácticas que admiten ejecución local en Jupyter / Anaconda no necesitan Google para esa ruta.

[Instrucciones oficiales en español](https://support.google.com/accounts/answer/27441?hl=es).

## NASA Earthdata · GMI e IMERG

El registro es gratuito. La misma cuenta sirve para ambos cuadernos.

1. Abra [Crear cuenta NASA Earthdata](https://urs.earthdata.nasa.gov/users/new).
2. Complete los datos solicitados y elija su nombre de usuario y contraseña.
3. Revise su correo y active la cuenta mediante el enlace recibido. Revise también la carpeta de correo no deseado.
4. Compruebe el inicio de sesión en [Earthdata Login](https://urs.earthdata.nasa.gov/).
5. Al ejecutar una descarga, siga la solicitud interactiva del cuaderno. Si NASA solicita autorizar la aplicación de acceso, revise la solicitud y siga sus indicaciones.

No se necesita un registro PPS para el cuaderno GMI. Los cuadernos NASA Worldview y NDVI de esta colección utilizan otras rutas públicas y no requieren Earthdata.

[Guía oficial de registro y activación](https://urs.earthdata.nasa.gov/documentation/for_users/how_to_register) · [Información sobre el registro gratuito](https://urs.earthdata.nasa.gov/documentation/for_users).

## EUMETSAT · descargas desde Data Store y Data Tailor

1. Abra [Crear cuenta EUMETSAT](https://user.eumetsat.int/register). Si el formulario no aparece, entre al [inicio de sesión](https://user.eumetsat.int/cas/login) y seleccione **Register – Create new account**.
2. Complete el registro y las verificaciones que solicite el portal.
3. Compruebe que puede iniciar sesión antes de la práctica.
4. Use el método de autenticación indicado en su cuaderno:

| Cuaderno o ruta | Qué utiliza |
| :--- | :--- |
| SST EUMETSAT y ASCAT con `MODO = 'eumdac'` | **Consumer Key + Consumer Secret**, disponibles en [API Key Management](https://api.eumetsat.int/api-key/) después de iniciar sesión en el portal. |
| SST Panamá con Data Tailor | El flujo de autenticación de EUMDAC 4.0.0 explicado en el cuaderno; la terminal utiliza `eumdac auth --interactive`. |

Las claves API no son el nombre de usuario y la contraseña del portal. No existe una cuenta separada para EUMDAC: es el cliente utilizado para acceder a los servicios de EUMETSAT.

**Puede empezar sin cuenta EUMETSAT** con la muestra del caso Panamá y con la ruta NOAA de ASCAT. El respaldo incluido del cuaderno SST EUMETSAT también permite trabajar el caso inicial sin solicitar una nueva descarga a EUMETSAT.

[Acceso a datos y registro](https://user.eumetsat.int/data-access) · [Preguntas frecuentes del Data Store](https://user.eumetsat.int/resources/user-guides/frequently-asked-questions-for-data-store).

## Accesos sin cuenta del proveedor

| Práctica | Acceso utilizado |
| :--- | :--- |
| SST NASA Worldview | Imágenes públicas de NASA GIBS. |
| ASCAT · ruta inicial | Archivos públicos de NOAA CoastWatch. |
| SPEI | NetCDF públicos de SPEIbase del CSIC. |
| NDVI | API pública TESViS de NASA ORNL DAAC. |

Esto no elimina la cuenta Google cuando se ejecutan en Colab o se utiliza Drive. Tampoco significa que todos los productos de esos proveedores sean accesibles por el mismo método.

## Antes de empezar

Compruebe el inicio de sesión de las cuentas que sí necesita y complete cualquier verificación pendiente. Cada participante utiliza su propia cuenta; las credenciales se introducen solo en el flujo indicado por la práctica y no se guardan en las celdas compartidas.

Para leer o descargar los materiales de un repositorio público no necesita una cuenta GitHub. Google, Earthdata y EUMETSAT son cuentas distintas, aunque utilice el mismo correo al registrarse.

Enlaces e instrucciones revisados el 19 de noviembre de 2026.
