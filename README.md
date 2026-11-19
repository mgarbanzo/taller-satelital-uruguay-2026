![Observación satelital · Cuadernos de formación](Ultra-wide%20Spanish%20satellite%20observation%20banner.png)

# Productos y aplicaciones de los satélites meteorológicos

**Cuadernos de formación · Uruguay · Noviembre de 2026**  
AEMET y EUMETSAT, con apoyo de AECID

Ocho prácticas para acceder a datos, revisar su calidad, interpretar los resultados y repetir el análisis en otra región. Cada cuaderno incluye sus requisitos, instrucciones y parámetros.

## Comience aquí

1. Elija una práctica en la tabla y revise las cuentas que necesita.
2. Consulte [Cuentas y acceso](GUIA_CUENTAS.md): crear una cuenta es un proceso guiado y sencillo; varias prácticas no requieren cuenta del proveedor.
3. Abra el archivo `.ipynb` en [Google Colab](https://colab.research.google.com/) mediante **Archivo → Subir cuaderno** o **Archivo → Abrir cuaderno → GitHub**. Si desea conservar los cambios, guarde una copia en su Drive.
4. Si la práctica admite Jupyter / Anaconda, también puede descargarla y seguir sus instrucciones de ejecución local.
5. Ejecute las celdas en orden y revise cada resultado antes de cambiar los parámetros.

## Prácticas y cuentas necesarias

**Google:** se necesita cuando ejecuta en Colab o utiliza Drive. En los cuadernos que admiten Jupyter / Anaconda local no se requiere Google para esa ruta.

| N.º | Práctica | Cuenta para los datos | Entorno |
| :--- | :--- | :--- | :--- |
| 01 | [SST · Acceso a datos de EUMETSAT](SST_EUMETSAT_Colab_Drive.ipynb) | EUMETSAT para nuevas descargas; el respaldo incluido y la caché válida no requieren autenticarse otra vez. | Google Colab y Google Drive |
| 02 | [SST · Visualización con NASA Worldview](SST_NASA_Worldview_Colab_Drive.ipynb) | Ninguna cuenta del proveedor: la consulta de imágenes NASA GIBS es pública. | Google Colab y Google Drive |
| 03 | [SST · Data Tailor y EUMDAC en Panamá](FINAL_EUMDAC_SST_Panama_AEMET.ipynb) | EUMETSAT solo en el modo descarga. Los modos muestra y consulta no necesitan cuenta EUMETSAT. | Google Colab o Jupyter / Anaconda de 64 bits |
| 04 | [ASCAT · Viento oceánico frente a Uruguay](FINAL_ASCAT_NOAA_EUMDAC_Uruguay.ipynb) | Ninguna en la ruta predeterminada NOAA. EUMETSAT es opcional, solo para la ruta eumdac. | Google Colab o Jupyter / Anaconda de 64 bits |
| 05 | [GPM / GMI · Microondas sobre Uruguay](FINAL_GPM_GMI_37_89GHz_Uruguay.ipynb) | NASA Earthdata para descargar granulos. La consulta del catálogo es pública y el modo local no necesita iniciar sesión. | Google Colab o Jupyter / Anaconda de 64 bits |
| 06 | [IMERG · Precipitación diaria](FINAL_IMERG_Diario_Uruguay_Colab_Drive.ipynb) | NASA Earthdata para nuevas descargas Early, Late o Final. Solo Drive reutiliza los archivos ya guardados. | Google Colab y Google Drive |
| 07 | [SPEI · Duración e intensidad de la sequía](FINAL_SPEI_CSIC_Colab_Uruguay.ipynb) | Ninguna cuenta del proveedor: los NetCDF de SPEIbase del CSIC se descargan públicamente. | Google Colab y Google Drive |
| 08 | [NDVI · Diez años de vegetación](FINAL_NDVI_MODIS_Series_Uruguay_Colab.ipynb) | Ninguna cuenta del proveedor: esta práctica utiliza la API pública TESViS de ORNL DAAC. | Google Colab o Jupyter / Anaconda de 64 bits |

## Enlaces para crear las cuentas

- **Google:** [crear cuenta](https://accounts.google.com/signup) · [guía en español](https://support.google.com/accounts/answer/27441?hl=es). Si ya usa Gmail o Drive, utilice esa cuenta.
- **NASA Earthdata:** [registro gratuito](https://urs.earthdata.nasa.gov/users/new) · [activación por correo](https://urs.earthdata.nasa.gov/documentation/for_users/how_to_register). Una sola cuenta sirve para GMI e IMERG.
- **EUMETSAT:** [crear cuenta](https://user.eumetsat.int/register) · [inicio de sesión](https://user.eumetsat.int/cas/login) · [Consumer Key y Consumer Secret](https://api.eumetsat.int/api-key/) para los cuadernos que las solicitan.

La [guía de cuentas](GUIA_CUENTAS.md) explica cuándo se usa cada acceso. No necesita cuenta GitHub para leer o descargar estos materiales desde un repositorio público.

## Uso y conservación de resultados

Lea las condiciones de cada fuente y conserve sus referencias. Los cuadernos especifican si se está usando una descarga nueva, una caché o una muestra incluida. Use sus propias cuentas e introduzca las credenciales únicamente cuando el cuaderno lo solicite.

Instrucciones de cuentas revisadas el 19 de noviembre de 2026.
