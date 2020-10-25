# Buda.com to Google Spreadsheet

## Pasos a seguir

**Aquí**
1. Abre el ipynb y aprieta el botón justo arriba del archivo "Abrir en Colaboratory"
2. Guarda la copia en la carpeta de Google Drive en la que quieras tener tu spreadsheet con tus datos de Buda.com

**En Buda.com**
3. Anda a Configuración > API Keys
4. Genera una nueva API key que **no** tenga acceso de trading ni de retiros (por seguridad ya que no los necesitaremos)
5. Guárdala en un lugar seguro

**En el Drive**
6. Crea un spreadsheet, yo lo llamo "My Buda Index"
7. Abre el ipynb con Google Colaboratory
8. En el primer bloque de código, rellena el nombre del spreadsheet, tu api_key y tu api_secret
9. Presiona Runtime > Run All
10. Tu spreadsheet fue rellenado con todos los datos que implican flujos de BTC que están en Buda.com, solo con permiso read-only
