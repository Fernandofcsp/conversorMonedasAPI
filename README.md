# Conversor de monedas

Este es un programa que hace peticiones a Exchange-RateAPI para saber las tasas de cambio entre diferentes monedas y aprovechar esa información para hacer conversiones entre diferentes tipos de monedas.

<img src="ConversorMonedas.gif" alt="Animación" style="width:50%;">
* [Video](https://drive.google.com/file/d/19kxfFrkaLZy0aZPSvexqm0cSiywpJKbV/view?usp=drive_link) - Drive



## Comenzando 🚀

Si lo que buscas es probar el proyecto dentro de la carpeta target se encuentra el ejecutable .exe y el .jar

Si lo que buscas es compilarlo tu mismo y modificarlo, clona el repositorio y abre el proyecto en IntelliJ o cualquier otro IDE que sea de tu agrado.


### Pre-requisitos 📋

*JAVA SDK 17
*IDE (IntelliJ)

### Instalación 🔧

Asegurarse de tener Java instalado

Bajar el ejecutable .exe y arrancarlo.

### Funciones 📖

<div style="display: flex; align-items: flex-start;">
  <div style="flex: 1;">
    <ul>
      <li>Selectores de monedas</li>
      <li>Boton para convertir</li>
      <li>Placeholder para la cantidad</li>
      <li>Boton para invertir las monedas</li>
      <li>Boton para borrar todo (resetear)</li>
      <li>Boton para convertir</li>
      <li>Lista de conversiones que se guarda y se lee en un .txt</li>
      <li>Boton para Borrar el historial de conversiones</li>
    </ul>
  </div>
  <div>
    <img src="https://github.com/Fernandofcsp/conversorMonedasAPI/assets/73980852/2c987d50-c3f8-4056-a24f-dbc17088ab71" alt="image" style="width:200px;">
  </div>
</div>


## Estructura 💻
src/main/java/com.example.conversormonedas/
<ul>
  <li><strong>EntryPoint.java:</strong> Manda llamar al gui para una compilación exitosa con maven.</li>
  <li><strong>CurrencyConverterGUI.java:</strong> Interfaz de usuario para la aplicación de conversión de monedas.</li>
  <li><strong>CurrencyConverter.java:</strong> Lógica para realizar las conversiones de moneda.</li>
  <li><strong>CurrencyCoins.java:</strong> Gestión de la lista de monedas disponibles.</li>
  <li><strong>Currency.java:</strong> Representación de una moneda individual.</li>
  <li><strong>ExchangeRateAPI.java:</strong> Comunicación con una API externa para obtener tipos de cambio.</li>
  <li><strong>ConversionRecord.java:</strong> Representación de un registro de conversión de moneda.</li>
  <li><strong>ConversionHistory.java:</strong> Gestión del historial de conversiones de moneda.</li>
</ul>

**NOTA:** Dentro del IDE es posible ejecutar tanto EntryPoint como CurrencyConverterGUI, Entrypoint solo esta ahí para empaquetar correctamente el .exe con maven.



## Despliegue 📦

Para compilar el .jar y el .exe en IntelliJ solo es necesario ejecutar el package de maven, la configuracion del proyecto ya esta establecida en el archivo pom.xml

## Construido con 🛠️

* [JavaFX](https://openjfx.io/) - Interfaz grafica
* [GSON](https://mvnrepository.com/artifact/com.google.code.gson/gson) - Convierte los Objetos a representación JSON para manipular la información de la API
* [IntelliJCommunity](https://www.jetbrains.com/idea/download/?section=windows) - Programación
* [Maven](https://maven.apache.org/) - Manejador de dependencias
* [Launch4j](https://launch4j.sourceforge.net/) - Plugin para empaquetar el programa en .exe
* [JAVA](https://www.java.com/es/) - Lenguaje

## Versionado 📌

1.0 (Git)

## Autor ✒️
* **Fernando Sandoval** - *Codificación y diseño* - [fernandofcsp](https://github.com/fernandofcsp)
  
