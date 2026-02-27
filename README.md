Descripción del Proyecto

Este proyecto consiste en la automatización de pruebas funcionales sobre la aplicación web SauceDemo, utilizando el patrón Page Object Model (POM) y el framework Serenity BDD con Cucumber y Maven.

El objetivo principal es validar el flujo de compra de un usuario en la plataforma, cubriendo tanto escenarios positivos (Happy Path) como escenarios negativos (Unhappy Path), asegurando el correcto funcionamiento del sistema ante distintos tipos de entradas.

 Objetivo

Automatizar los principales flujos del sistema:

Login exitoso

Agregar productos al carrito

Completar proceso de compra

Validar mensajes de error en intentos fallidos

El proyecto está diseñado siguiendo buenas prácticas de automatización, separación de responsabilidades y estructura escalable.

🛠 Tecnologías utilizadas

Java

Maven

Serenity BDD

Cucumber (BDD)

Selenium WebDriver

JUnit

Git & GitHub

 Cobertura de Pruebas
 Happy Path

Login exitoso

Agregar producto al carrito

Completar compra correctamente

 Unhappy Path

Password incorrecto

Usuario bloqueado

Campos vacíos en login

Estructura del Proyecto

El proyecto sigue el patrón Page Object Model:

page/ → Localizadores y acciones de la página

steps/ → Lógica de negocio

stepdefinitions/ → Definición de pasos Cucumber

features/ → Escenarios en Gherkin

Esto permite una automatización limpia, mantenible y escalable.
