# Superconversor de Monedas

Bienvenid@s al Superconversor de Monedas, una aplicación en Java que permite convertir entre varias monedas y mantener un historial de conversiones.

## Funcionalidades

- Conversión entre diferentes pares de monedas:
  - Dólar a Peso Argentino
  - Peso Argentino a Dólar
  - Dólar a Real Brasileño
  - Real Brasileño a Dólar
  - Dólar a Peso Colombiano
  - Peso Colombiano a Dólar
- Visualización del historial de conversiones
- Almacenamiento del historial de conversiones en un archivo de texto

## Resumen de Funcionamiento

El Superconversor de Monedas es una aplicación de consola que interactúa con una API de tipos de cambio para realizar conversiones entre diferentes monedas. Los usuarios pueden seleccionar el tipo de conversión que desean realizar, ingresar la cantidad a convertir y obtener el resultado de la conversión. La aplicación mantiene un historial de hasta 30 conversiones recientes, que se muestra al usuario y se guarda en un archivo de texto para referencia futura.

## Requisitos

- Java 11 o superior
- Maven

## Instalación

1. Clona el repositorio en tu máquina local. Abre PowerShell y ejecuta:
    git clone https://github.com/tu_usuario/superconversor-de-monedas.git
   
2. Navega al directorio del proyecto:
    cd superconversor-de-monedas
   
4. Compila el proyecto con Maven. Si Maven no está instalado, puedes descargarlo desde aquí, https://maven.apache.org/download.cgi y seguir las instrucciones de instalación para            Windows. Luego, ejecuta:
    mvn clean install
   
## Uso

1. Ejecuta la aplicación:
    mvn exec:java -Dexec.mainClass="Principal"
2. Sigue las instrucciones en pantalla para realizar conversiones y ver el historial.

   ![image](https://github.com/Emmanuel-Angel/Conversor/assets/157259271/06e7e2d1-beca-4260-9342-df46f25fa73d)

   ![image](https://github.com/Emmanuel-Angel/Conversor/assets/157259271/3cd2088e-1df1-4685-87dd-6dab69b8c563)


   
## Contribuciones

Las contribuciones son bienvenidas. Si deseas contribuir, por favor haz un fork del repositorio y crea un pull request con tus cambios.
