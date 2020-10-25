# Buda.com to Google Spreadsheet

## Pasos a seguir

**Aquí**

1. Abre el ipynb y aprieta el botón justo arriba del archivo "Open in Colab"
2. Guarda la copia en la carpeta de Google Drive en la que quieras tener tu spreadsheet con tus datos de Buda.com

**En Buda.com**

3. Anda a Configuración > API Keys y genera una nueva API key que **no** tenga acceso de trading ni de retiros (por seguridad ya que no los necesitaremos)
4. Guárdala en un lugar seguro

**En el Drive**

5. Crea un spreadsheet, yo lo llamo "My Buda Index"
6. Abre el ipynb con Google Colaboratory
7. En el primer bloque de código, rellena el nombre del spreadsheet, tu api_key y tu api_secret
8. Presiona Runtime > Run All
9. Para la primera vez, revisa los logs del segundo bloque de código, completa el OAuth de Google y presiona Enter
10. Listo! Tu spreadsheet fue rellenado con todos los datos que implican flujos de BTC que están en Buda.com, solo con permiso read-only
