<div align="center">

# 🍽️ Editor de Carta Digital Portable y Autónomo

### El fin del *"Secuestro Digital"* en la hostelería

Una herramienta **standalone** de pago único que devuelve el control absoluto, la soberanía de datos y la libertad financiera al hostelero.
**Sin cuotas mensuales · Sin intermediarios · Sin comisiones.**

<br>

![Pago único](https://img.shields.io/badge/MODELO-PAGO%20%C3%9ANICO-000000?style=for-the-badge&labelColor=000000)
![Sin cuotas](https://img.shields.io/badge/CUOTAS%20MENSUALES-0%E2%82%AC-000000?style=for-the-badge&labelColor=000000)
![Autónomo](https://img.shields.io/badge/ARQUITECTURA-100%25%20AUT%C3%93NOMA-000000?style=for-the-badge&labelColor=000000)
![Idiomas](https://img.shields.io/badge/IDIOMAS-ES%20%C2%B7%20EN-000000?style=for-the-badge&labelColor=000000)

<br>

**[ 📖 Resumen ](#1-resumen-ejecutivo--qué-es) · [ ⚙️ Ecosistema ](#2-cómo-funciona-el-ecosistema) · [ 🏗️ Arquitectura ](#3-arquitectura-técnica-y-generación-de-la-spa-html5) · [ ⚖️ Ventajas ](#4-ventajas-competitivas-frente-a-las-cartas-digitales-saas) · [ 🧾 Ficha Técnica ](#5-ficha-técnica-y-especificaciones) · [ 🆕 Novedades ](#6-novedades-y-actualizaciones-recientes) · [ 💼 Caso de Uso ](#7-caso-de-uso-comercial) · [ 👤 Autor ](#-licencia-dirección-de-arte-y-autoría)**

</div>

<br>

---

<div align="center">

## 🌐 Demo en Vivo y Acceso QR

Prueba la experiencia real que tendrá el comensal accediendo directamente desde tu smartphone o escaneando el código QR oficial del proyecto.

### 👉 [Demo de Carta Digital · Vista de Comensal](https://manolorecio.github.io/carta-digital/)

<a href="https://manolorecio.github.io/carta-digital/" target="_blank">
  <img
    src="https://raw.githubusercontent.com/manolorecio/carta-digital/main/qr-code.svg"
    width="240"
    alt="Código QR de la Carta Digital"
  >
</a>

</div>

<br>

---

<br>

## 1. Resumen Ejecutivo — ¿Qué es?

El **Editor Portable de Carta Digital** es un software de administración autónomo diseñado para:

`Restaurantes` · `Bares` · `Cafeterías` · `Gastrobares` · `Terrazas` · `Hoteles`

Permite al propietario o gestor del establecimiento **diseñar, actualizar y gestionar toda la oferta gastronómica** de su local de forma instantánea, sin depender de plataformas de terceros ni pagar mensualidades o suscripciones.

A diferencia de las cartas digitales tradicionales basadas en plataformas SaaS externas, el sistema funciona de manera **100 % independiente**, mediante un ejecutable portable y autónomo.

El editor trabaja localmente y permite **exportar una Single Page Application (SPA) HTML5 ultra-ligera**, optimizada y totalmente autosuficiente para ser alojada en:

> `Hosting` · `VPS` · `GitHub Pages` · `Servidor local` · `Cualquier infraestructura web compatible`

La carta también puede servirse directamente mediante un **código QR**, sin intermediarios.

<div align="right"><a href="#-editor-de-carta-digital-portable-y-autónomo">⬆ Volver arriba</a></div>

---

<br>

## 2. ¿Cómo funciona el ecosistema?

El sistema se compone de **dos módulos principales interconectados**: el **Editor Portable de Administración**, donde se crea y gestiona la carta, y la **Carta Digital Web SPA**, que recibe el contenido publicado y lo presenta al comensal.

### 🖥️ Módulos del ecosistema

| Módulo                                  | Función principal                     | Características                                             |
| ---------------------------------------- | -------------------------------------- | ------------------------------------------------------------ |
| **1 · EDITOR PORTABLE ADMIN**            | Administración y creación de la carta | Ejecutable independiente para PC, portátil o servidor local |
| **2 · CARTA DIGITAL WEB SPA · COMENSAL** | Visualización pública de la carta     | Acceso mediante QR desde cualquier dispositivo móvil        |

<br>

<details open>
<summary><b>2.1 · 🖥️ Editor Portable Admin</b></summary>
<br>

|     Nº | Funcionalidad                              | Descripción                                                     |
| -----: | -------------------------------------------- | ------------------------------------------------------------------------ |
| **01** | 🖥️ **Ejecutable independiente**           | Aplicación portable para PC, portátil o servidor local.         |
| **02** | 🗂️ **Gestión visual**                     | Administración de categorías, platos, precios y alérgenos.      |
| **03** | 🕐 **Programación Maestra · Shift Engine** | Gestión centralizada de turnos y horarios del establecimiento.  |
| **04** | 💶 **Editor de Tarifas Bilingüe**          | Configuración de tarifas con **1, 2 o 3 columnas** de precios.  |
| **05** | 📷 **Captura y Cropper**                   | Captura mediante cámara nativa y recorte integrado de imágenes. |
| **06** | 👁️ **Vista previa en tiempo real**        | Visualización inmediata de los cambios antes de publicar.       |
| **07** | ⚡ **Generación SPA**                       | Exportación de la carta digital completa mediante **1 clic**.   |

</details>

<details open>
<summary><b>2.2 · 📱 Carta Digital Web SPA · Comensal</b></summary>
<br>

|     Nº | Funcionalidad                     | Descripción                                                     |
| -----: | ------------------------------------ | ------------------------------------------------------------------------ |
| **01** | 📱 **Visor público**              | Carta digital accesible para los comensales mediante código QR. |
| **02** | ⏱️ **Disponibilidad Inteligente** | Badges reactivos según el horario real del establecimiento.     |
| **03** | 🔄 **Filtrado Dinámico**          | Cambio automático de turnos y activación del modo Noche.        |
| **04** | 📋 **Menú Completo**              | Modo alternativo para consultar toda la oferta gastronómica.    |
| **05** | 🌐 **Multi-idioma**               | Soporte nativo para **Español / Inglés / Francés**.             |
| **06** | 🌱 **Dietas y Alérgenos**         | Filtrado por alérgenos y dietas como Vegano, Gluten-Free, etc.  |

</details>

<br>

### 🔄 Flujo de publicación

El proceso completo transforma la configuración local del establecimiento en una **SPA HTML5 autónoma**, lista para alojarse en cualquier infraestructura web compatible.

|   Paso | Proceso                               | Resultado                                                                     |
| -----: | ---------------------------------------- | -------------------------------------------------------------------------------- |
| **01** | 🖥️ **EDITOR PORTABLE**               | El administrador trabaja localmente sobre la carta.                           |
| **02** | ✏️ **Edición local**                  | Se modifican platos, precios, categorías, horarios, imágenes y configuración. |
| **03** | 🗄️ **Base de datos / Configuración** | Toda la información queda estructurada y preparada para su publicación.       |
| **04** | ⚙️ **Optimización + Procesamiento**   | Se procesan datos e imágenes para reducir peso y optimizar la carga.          |
| **05** | 🚀 **GENERADOR SPA**                  | El sistema construye automáticamente la carta web.                            |
| **06** | 📄 **Exportación · 1 clic**           | Se genera el archivo autónomo `index.html`.                                   |
| **07** | 🌍 **Publicación**                    | El archivo puede alojarse en Hosting, VPS, GitHub Pages o servidor propio.    |
| **08** | 🔗 **Código QR**                      | El QR apunta directamente a la carta digital publicada.                       |
| **09** | 📱 **COMENSAL**                       | El cliente escanea el QR y accede a la carta desde su dispositivo.            |

<br>

<div align="center">

**`EDITOR PORTABLE`** → **`GENERADOR SPA`** → **`index.html`** → **`SERVIDOR`** → **`CÓDIGO QR`** → **`COMENSAL`**

</div>

<br>

<details>
<summary>🌐 <b>Destinos de publicación</b></summary>
<br>

| Infraestructura     | Uso                                                                        |
| --------------------- | ----------------------------------------------------------------------------- |
| **Hosting**         | Alojamiento web convencional.                                             |
| **VPS**             | Servidor privado con control total de la infraestructura.                 |
| **GitHub Pages**    | Publicación estática directamente desde un repositorio.                   |
| **Servidor propio** | Alojamiento completamente independiente bajo control del establecimiento. |

</details>

<details>
<summary>🔁 <b>Resumen del ecosistema</b></summary>
<br>

| 🖥️ Administración  | ⚙️ Procesamiento          | 🌐 Publicación                                     | 📱 Cliente                    |
| --------------------- | ---------------------------- | ------------------------------------------------------ | -------------------------------- |
| **Editor Portable** | **Generador SPA**         | **Hosting / VPS / GitHub Pages / Servidor propio** | **Carta Digital Web**         |
| Edición local       | Optimización              | `index.html`                                       | Acceso mediante QR            |
| Platos y categorías | Procesamiento de imágenes | Publicación 1 clic                                 | Consulta de la carta          |
| Precios y tarifas   | Compilación de datos      | Infraestructura propia                             | Disponibilidad en tiempo real |
| Turnos y horarios   | Generación HTML5          | Sin intermediarios                                 | Multi-idioma y filtros        |
| Alérgenos           | SPA autónoma              | Control del establecimiento                        | Experiencia del comensal      |

</details>

<div align="right"><a href="#-editor-de-carta-digital-portable-y-autónomo">⬆ Volver arriba</a></div>

---

<br>

## 3. Arquitectura Técnica y Generación de la SPA HTML5

### 3.1 · 🕐 Programación Inteligente de Disponibilidad

El sistema utiliza un **motor de cálculo en tiempo real** que garantiza la coherencia entre el reloj del local y la vista del cliente.

| Funcionalidad                     | Descripción                                                                                                        |
| ------------------------------------ | ----------------------------------------------------------------------------------------------------------------------- |
| **Turnos Maestros**               | El administrador define la estructura horaria principal: Desayunos, Aperitivo, Comidas, Tardeo, Cenas y Nightlife. |
| **Sincronización de Categorías**  | Las categorías pueden heredar automáticamente los horarios globales.                                               |
| **Soporte Nightlife**             | Gestión de turnos que cruzan la medianoche, por ejemplo de **21:00 a 03:00**.                                      |
| **Validación Semanal**            | Control de días cerrados para apagar automáticamente la oferta gastronómica.                                       |
| **Disponibilidad en Tiempo Real** | La interfaz adapta la información mostrada según el horario actual.                                                |

**🌙 Ejemplo de turno nocturno**

|    Inicio |       Fin | Turno        |
| --------: | --------: | -------------- |
| **21:00** | **03:00** | 🌙 Nightlife |

El sistema está preparado para establecimientos con servicio nocturno extendido.

<br>

### 3.2 · 📦 Publicación y Exportación de la Carta HTML SPA

Cuando el usuario pulsa el botón **Exportar Carta**, se ejecuta el siguiente proceso:

|   Paso | Proceso                           | Descripción                                                                                 |
| -----: | ------------------------------------ | ------------------------------------------------------------------------------------------------ |
| **01** | 📦 **Empaquetado de Datos**       | La configuración de la carta se compila en un **payload JSON optimizado**.                  |
| **02** | 🖼️ **Procesamiento de Imágenes** | Las fotografías se optimizan, reescalan y recortan para reducir el peso de carga.           |
| **03** | ⚡ **Generador SPA Autónomo**      | El editor produce un único archivo `index.html`.                                            |
| **04** | 🧩 **Integración**                | El archivo contiene la lógica, estilos y datos necesarios para funcionar de forma autónoma. |
| **05** | 🔐 **Sello de Marca y Licencia**  | Se incorpora una capa de seguridad con firma de autoría e identificación de producto.       |

<div align="center">

**Resultado de la exportación**

```text
index.html
```

</div>

El archivo generado está preparado para su publicación en cualquier infraestructura compatible con contenido web estático.

<div align="right"><a href="#-editor-de-carta-digital-portable-y-autónomo">⬆ Volver arriba</a></div>

---

<br>

## 4. Ventajas Competitivas frente a las Cartas Digitales SaaS

| Característica                   | Carta Digital Portable           | Competencia Tradicional · SaaS          |
| ----------------------------------- | ----------------------------------- | ------------------------------------------ |
| **Cuotas mensuales / Licencias** | **0 €/mes · Pago único**         | 29 € – 99 €/mes                         |
| **Propiedad del sistema**        | **Sí**                           | Dependencia de la plataforma            |
| **Turnos y disponibilidad real** | **Sí · Badges reactivos**        | Inexistente o etiquetas estáticas       |
| **Cruce de medianoche**          | **Sí · Soporte nativo**          | Errores habituales después de las 00:00 |
| **Idiomas**                      | **ES / EN / FR**                 | Generalmente traducción manual          |
| **Velocidad móvil**              | **Ultra-ligera · < 0,5 s\***     | Dependiente de peticiones externas      |
| **Dependencia del servidor**     | **Sin plataforma intermediaria** | Dependencia total del proveedor         |
| **Independencia del QR**         | **Total**                        | El QR depende de la plataforma          |
| **Control de los datos**         | **Local / propietario**          | Gestionado por el proveedor             |

> \* El rendimiento real dependerá del dispositivo, red, servidor y contenido publicado.

<div align="right"><a href="#-editor-de-carta-digital-portable-y-autónomo">⬆ Volver arriba</a></div>

---

<br>

## 5. Ficha Técnica y Especificaciones

<details open>
<summary><b>💻 Editor Portable — Administración</b></summary>
<br>

| Módulo                            | Descripción y funcionalidades                                                                                         |
| ------------------------------------ | ------------------------------------------------------------------------------------------------------------------------ |
| **Entorno de ejecución**          | Ejecutable portable autónomo para Windows / macOS / Linux.                                                            |
| **Configuración Horaria Maestra** | Control centralizado de turnos: Desayunos, Aperitivo, Comidas, Tardeo, Cenas y Nightlife, además del horario semanal. |
| **Editor de Tarifas**             | Personalización de columnas de precios con etiquetas bilingües y restauración de fábrica.                             |
| **Armonía Cromática OKLAB**       | Generación de temas visuales basados en percepción humana para mejorar el contraste.                                  |
| **Recortador Interactivo**        | Herramienta Cropper integrada para banners y fotografías de platos.                                                   |
| **Vista Previa**                  | Visualización en tiempo real antes de publicar.                                                                       |
| **Exportación SPA**               | Generación de la carta web mediante un clic.                                                                          |

</details>

<details open>
<summary><b>📱 Carta Digital Pública — Visor Comensal</b></summary>
<br>

| Componente                  | Características Técnicas                                                                      |
| ------------------------------ | -------------------------------------------------------------------------------------------------- |
| **Disponibilidad Reactiva** | Etiquetas dinámicas con cuenta atrás para cierres de turno y próximas aperturas.              |
| **Gestión de Menú del Día** | Lógica inteligente que evita pedidos individuales en platos pertenecientes a un menú cerrado. |
| **Soporte Multi-idioma**    | Español, Inglés y Francés.                                                                    |
| **Filtrado por Turnos**     | Muestra automáticamente las categorías correspondientes al turno activo.                      |
| **Modo Menú Completo**      | Permite consultar la totalidad de la oferta gastronómica.                                     |
| **Accesibilidad**           | Soporte para los 14 alérgenos de la UE, indicadores dietéticos, picante y `aria-labels`.      |
| **SEO & Performance**       | SPA optimizada para carga rápida incluso con baja cobertura.                                  |
| **Sello de Calidad**        | Footer personalizado con información del establecimiento y licencia de software.              |

</details>

<div align="right"><a href="#-editor-de-carta-digital-portable-y-autónomo">⬆ Volver arriba</a></div>

---

<br>

## 6. Novedades y Actualizaciones Recientes

<div align="center">

![Última actualización](https://img.shields.io/badge/ÚLTIMA%20ACTUALIZACIÓN-Septiembre%202026-000000?style=for-the-badge&labelColor=000000)

</div>

<br>

|      # | Actualización / Mejora                | Descripción                                                                                                                                    |
| -----: | ---------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| **01** | **Gestión de Menú del Día**           | Los comensales no pueden pedir platos sueltos cuando pertenecen a un menú. El sistema les guía hacia la configuración del combo.            |
| **02** | **Disponibilidad Reactiva**           | Etiquetas dinámicas como `⏳ Abre hoy a las 13:00` o `🚨 Cierra en 15 min`, actualizadas en tiempo real.                                     |
| **03** | **Accesibilidad Universal**           | Implementación exhaustiva de etiquetas `aria-labels` en la interfaz.                                                                          |
| **04** | **Exportación HTML Robusta**          | Sustitución de motores de reemplazo de texto por métodos de segmentación de strings para mejorar la compatibilidad con navegadores móviles. |
| **05** | **Motor de Sincronización Global**    | Las categorías pueden sincronizarse con los turnos maestros con un clic.                                                                    |
| **06** | **Nightlife & Cruce de Medianoche**   | Soporte nativo para horarios nocturnos extendidos.                                                                                           |
| **07** | **Visibilidad Inteligente de Extras** | Suplementos y guarniciones se muestran u ocultan según el turno activo.                                                                     |
| **08** | **Idioma alternativo**                | Incorporación de otros idiomas (Español/Inglés con traducción automática).                                                                                          |
| **09** | **Sello de Seguridad y Marca**        | Implementación de firmas digitales y mecanismos de protección de marca en el HTML exportado.                                                |
| **10** | **Sincronización de Backup**          | Persistencia forzada en disco y memoria antes de descargar copias de seguridad con imágenes Base64 optimizadas.                             |
| **11** | **Guías Visuales Interactivas**       | Microinteracciones `Pulse CTA` para destacar acciones como tema, alérgenos y lectura por voz.                                               |

<div align="right"><a href="#-editor-de-carta-digital-portable-y-autónomo">⬆ Volver arriba</a></div>

---

<br>

## 7. Caso de Uso Comercial

### 💰 Ahorro de Costes Inmediato

El establecimiento elimina el gasto recurrente en software de carta digital y sustituye el modelo de suscripción por una solución de **pago único**.

### 📈 Upselling & Cross-Selling por Franja Horaria

Permite mostrar ofertas dinámicas únicamente durante los horarios establecidos:

| Franja / Función  | Aplicación                                                   |
| -------------------- | ----------------------------------------------------------------- |
| ☀️ **Desayunos**  | Promociones y productos disponibles durante la mañana.      |
| 🍸 **Happy Hour** | Ofertas específicas durante una franja horaria determinada. |
| 🍽️ **Comidas**   | Menús y platos disponibles durante el servicio de mediodía. |
| 🌆 **Tardeo**     | Productos y promociones específicas de la tarde.            |
| 🌙 **Cenas**      | Carta adaptada al servicio nocturno.                        |
| 🌃 **Nightlife**  | Oferta específica para horarios nocturnos y de madrugada.   |

De esta forma se evita saturar la carta con productos que no están disponibles en ese momento.

<br>

### ⚙️ Independencia Operativa

El hostelero puede modificar directamente:

`Precios` · `Platos` · `Categorías` · `Fotografías` · `Horarios` · `Productos agotados` · `Sugerencias del día` · `Promociones` · `Disponibilidad`

Todo ello **sin depender de diseñadores, agencias web o plataformas externas**.

<br>

### 📲 Experiencia de Cliente Ininterrumpida

La carta está diseñada para ofrecer una experiencia rápida incluso en situaciones de conectividad limitada, como:

`Comedores interiores` · `Terrazas` · `Sótanos` · `Zonas con baja cobertura`

<br>

### ♿ Accesibilidad y Alérgenos

El sistema incorpora funcionalidades orientadas a la accesibilidad y la información alimentaria, incluyendo el filtrado de los **14 alérgenos de la Unión Europea** y etiquetas accesibles mediante `aria-labels`.

> **Nota:** Las funcionalidades de cumplimiento normativo no sustituyen la responsabilidad del establecimiento de mantener la información de alérgenos actualizada y correctamente verificada.

<div align="right"><a href="#-editor-de-carta-digital-portable-y-autónomo">⬆ Volver arriba</a></div>

---

<br>

## 🧩 Tecnologías y Conceptos

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-000000?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-000000?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-000000?style=for-the-badge&logo=javascript&logoColor=white)
![React](https://img.shields.io/badge/React-000000?style=for-the-badge&logo=react&logoColor=white)
![JSON](https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-000000?style=for-the-badge&logo=github&logoColor=white)

</div>

<br>

| Tecnología / Concepto     | Aplicación                                                  |
| ---------------------------- | ------------------------------------------------------------- |
| **HTML5**                 | Estructura de la carta web exportada.                      |
| **CSS3**                  | Diseño visual y responsive.                                |
| **JavaScript**            | Lógica de interacción y disponibilidad.                    |
| **React**                 | Arquitectura de la aplicación web del visor.               |
| **SPA**                   | Aplicación web de página única.                            |
| **JSON**                  | Estructuración y transporte de los datos de la carta.      |
| **Base64**                | Integración de recursos e imágenes optimizadas.            |
| **GitHub Pages**          | Posible infraestructura de publicación.                    |
| **Responsive Design**     | Adaptación a smartphones, tablets y escritorio.            |
| **Web Accessibility**     | `aria-labels` y funcionalidades de accesibilidad.          |
| **Image Optimization**    | Reducción y optimización de fotografías.                   |
| **Shift Engine**          | Gestión inteligente de turnos y horarios.                  |
| **Arquitectura Portable** | Ejecución autónoma sin dependencia de una plataforma SaaS. |

<div align="right"><a href="#-editor-de-carta-digital-portable-y-autónomo">⬆ Volver arriba</a></div>

---

<br>

<div align="center">

## 🚀 Filosofía del Proyecto

Nace con una premisa sencilla:

> **El restaurante debe ser propietario de su carta digital, no un rehén de la plataforma que la aloja.**

</div>

El modelo pretende eliminar la dependencia tecnológica innecesaria y proporcionar al establecimiento:

| Propiedad     | Control            | Independencia          | Libertad                   |
| --------------- | --------------------- | ------------------------- | ----------------------------- |
| **Tus datos** | **Tus contenidos** | **Tu infraestructura** | **Sin cuotas recurrentes** |

---

<br>

## 📜 Licencia, Dirección de Arte y Autoría

**© 2026 Manolo Recio · Todos los derechos reservados.**

Concepto, diseño de interfaz de usuario y experiencia (**UI/UX**), desarrollo de ingeniería web de alto rendimiento y arquitectura de marca creados íntegramente por:

<div align="center">

### **Manolo Recio**

*Senior Graphic & Visual Designer · Scenography Developer · AI Creative Developer*

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-manolorecio.github.io-000000?style=for-the-badge&logo=googlechrome&logoColor=white)](https://manolorecio.github.io/Manolo-Recio-Portfolio/)
[![Email](https://img.shields.io/badge/EMAIL-manoloreciodesign@gmail.com-000000?style=for-the-badge&logo=gmail&logoColor=white)](mailto:manoloreciodesign@gmail.com)
[![Teléfono](https://img.shields.io/badge/TEL-633%20555%20950-000000?style=for-the-badge&logo=whatsapp&logoColor=white)](tel:+34633555950)

</div>

---

<br>

<div align="center">

## 🚫 No más cartas digitales secuestradas

**No entregues a tus comensales un PDF frío, incómodo e inaccesible.**

Ofrece una experiencia interactiva de autoría que respete su privacidad, cuide su salud alimentaria y libere para siempre a tu establecimiento de las cuotas abusivas de suscripción.

<br>

### *Tu carta · Tus datos · Tu servidor · Tu libertad*

<br>

---

<br>

<a href="https://manolorecio.github.io/Manolo-Recio-Portfolio/" target="_blank" rel="noopener noreferrer">
  <img src="./manolo-recio-logo.png" width="480" alt="Manolo Recio — Senior Graphic & Visual Designer, Scenography Developer & AI Creative Developer">
</a>

</div>
