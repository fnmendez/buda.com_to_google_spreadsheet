# Buda.com to Google Spreadsheet

Escribe todos tus flujos de BTC de Buda.com en un Google Spreadsheet con un click. La misión es obtener un reporte estadístico personalizado de todos los flujos de la(s) divisa(s) que quieras en un Spreadsheet, y que se actualice con un solo click.

## Pasos a seguir

**Aquí**

1. [Abre el ipynb](https://github.com/fnmendez/buda.com_to_google_spreadsheet/blob/main/Buda_To_Spreadsheet.ipynb) y aprieta el botón justo arriba del archivo "Open in Colab"
2. Guarda una copia en la carpeta de Google Drive en la que quieras tener tu spreadsheet con tus datos de Buda.com

**En Buda.com**

3. Anda a Configuración > API Keys y genera una nueva API key que **no** tenga acceso de trading ni de retiros (por seguridad ya que no los necesitaremos)
4. Guárdala en un lugar seguro

**En el Drive**

5. Crea un spreadsheet, yo lo llamo "My Buda Index"
6. Abre el ipynb con Google Colaboratory
7. En el primer bloque de código, rellena el nombre del spreadsheet, tu api_key y tu api_secret
8. Presiona Runtime > Run All
9. Para la primera vez, revisa los logs del segundo bloque de código, completa el OAuth de Google y presiona Enter
10. Ejecuta el resto de los bloques

Listo! Tu spreadsheet fue rellenado con todos los datos que implican flujos de BTC que están en Buda.com, solo con permiso read-only

Para actualizarlo solo necesitarás ejecutar de nuevo los bloques del inciso 2.2 :)

## Contribuciones

Estás invitado a contribuir en este proyecto full extensible!

Puedes contactarme en f@francomendez.com
