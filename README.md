# Score Game — Sitio legal (privacidad y términos)

Este repositorio contiene una **página web estática** con la **política de privacidad** y los **términos y condiciones de uso** de la aplicación móvil **Score Game**.

## ¿Para qué existe este proyecto?

Google Play Console exige, entre otros requisitos, una **URL pública accesible por HTTPS** donde los usuarios puedan consultar la política de privacidad de la app. Este sitio cumple ese propósito: se despliega (por ejemplo en **Netlify**) y la URL resultante se enlaza desde la ficha de la aplicación en Play Store.

No sustituye al código de la app Android ni al proceso de publicación del APK o AAB; solo aloja el texto legal necesario para el cumplimiento en la tienda.

## ¿Qué es Score Game?

**Score Game** es una aplicación móvil pensada para **llevar marcadores y puntuaciones de partidas** (jugadores, rondas, categorías, preferencias, etc.). Los datos que introduces se gestionan **principalmente en el dispositivo** mediante almacenamiento local. Las compras o donaciones opcionales, si las hubiera, se procesan a través de **Google Play Billing**.

El desarrollador es una **persona natural** con residencia en **Medellín, Antioquia, Colombia**. Para consultas sobre privacidad o estos términos: **j.fabra25@gmail.com**.

## Contenido del repositorio

| Archivo / carpeta | Descripción |
|-------------------|-------------|
| `index.html` | Página única con política de privacidad y términos en **español**, **inglés** y **portugués**, con selector de idioma. |
| `netlify.toml` | Configuración de publicación para Netlify (`publish` en la raíz del sitio). |

## Despliegue

Cualquier hosting de **sitios estáticos** es válido. Con **Netlify** puedes conectar este repositorio o desplegar la carpeta manualmente; la raíz de publicación debe ser la que contiene `index.html`.

Tras el despliegue, usa la URL pública (por ejemplo `https://tu-sitio.netlify.app`) como **política de privacidad** en Google Play Console.

---

*Última referencia de contenido en la página: mayo de 2026.*
