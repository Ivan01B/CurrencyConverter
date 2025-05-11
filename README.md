# 💱 Conversor de Moneda en Java

Este es un conversor de monedas desarrollado en Java que permite convertir entre diferentes divisas latinoamericanas y el dólar estadounidense utilizando la API de ExchangeRate-API y la biblioteca Gson para procesar datos JSON.

## 📌 Características

- Interfaz textual por consola.
- Uso de API REST con `HttpClient`, `HttpRequest` y `HttpResponse`.
- Conversión entre las siguientes monedas:
  - ARS - Peso argentino
  - BOB - Boliviano boliviano
  - BRL - Real brasileño
  - CLP - Peso chileno
  - COP - Peso colombiano
  - USD - Dólar estadounidense
- Validaciones de entrada para evitar errores comunes.
- Biblioteca externa Gson para el análisis del JSON.

## 🛠 Requisitos

- Java 11 o superior.
- IntelliJ IDEA u otro IDE compatible.
- Conexión a Internet.
- Archivo `gson-<versión>.jar` agregado al directorio `lib/` y vinculado al proyecto.

## 🚀 Ejecución

1. Clona o descarga este repositorio.
2. Abre el proyecto en IntelliJ IDEA.
3. Asegúrate de que el archivo `gson.jar` esté ubicado en la carpeta `lib/`.
4. Agrega la biblioteca al proyecto:
   - `File > Project Structure > Libraries > + > Java > Selecciona gson.jar`.
5. Ejecuta la clase `CurrencyConverter.java`.

## 🧪 Ejemplo de uso

Ejecuta. Luego elige el numero de la moneda que deseas convertir, luego al tipo de cambio, y coloca el monto a convertir.
