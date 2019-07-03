# Cotizaciones
 Obtiene la cotizaci�n en ARS desde USD, EUR y BRL

# Aclaraciones
 La aplicaci�n est� hecha en ASP.NET Core, con Front-End en Angular.
 
 Al ejecutar la aplicaci�n, se mostrar� en pantalla una tabla con la cotizaci�n en Pesos Argentinos (ARS) de las monedas D�lar Estadounidense (USD), Euro (EUR) y Real (BRL). 
 La frecuencia de actualizaci�n de la cotizaci�n es de 5 segundos.
 Se utiliza la API de http://api.cambio.today/v1 (ver archivo appsettings.json secci�n "Cotizacion")

 Tambi�n se puede consumir independientemente (con Postman por ejemplo) la API para obtener las cotizaciones de las monedas en cuesti�n:
 - BASE_URL/api/cotizacion/dolar
 - BASE_URL/api/cotizacion/euro
 - BASE_URL/api/cotizacion/real
 
> NOTA: BASE_URL se debe reemplazar seg�n el entorno donde se ejecute el programa, normalmente ser� https://localhost:PORT
