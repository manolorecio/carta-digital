***

# DIMEDI: Editor de Carta Digital Portable y Autónomo

> **El fin del "Secuestro Digital" en la hostelería.** Una herramienta standalone de pago único que devuelve el control absoluto, la soberanía de datos y la libertad financiera al hostelero. **Sin cuotas mensuales, sin intermediarios y sin comisiones.**

---

## 🌐 Demo en Vivo y Acceso QR
Prueba la experiencia real que tendrá el comensal accediendo directamente desde tu smartphone o escaneando el código QR oficial del proyecto:
### 👉 **[Demo de Carta Digital · Vista de Comensal](https://manolorecio.github.io/carta-digital/)**


<p align="center">
  <a href="https://manolorecio.github.io/carta-digital/" target="_blank">
    <img src="https://raw.githubusercontent.com/manolorecio/carta-digital/main/qr-code.svg" width="280" alt="Código QR de la Carta Digital DIMEDI" style="border-radius: 15px; box-shadow: 0 4px 10px rgba(0,0,0,0.15);">
  </a>
</p>

---

## ❖ ¿Qué es DIMEDI (Editor Carta Digital Portable)?

**DIMEDI** es el primer **Editor de Carta Digital Standalone y Portable** diseñado para el sector de la restauración (restaurantes, tabernas, bares, cafeterías, hoteles, chiringuitos, tascas, mesones, gastrobares, pizzerías, hamburgueserías, heladerías, pastelerías, panaderías, food trucks, cáterings, bodegas, beach clubs y salones de celebraciones). 

A diferencia de las soluciones SaaS (Software de Alquiler) que cobran suscripciones perpetuas y exigen conexión constante a servidores de terceros, **DIMEDI se ejecuta localmente** (incluso desde un pendrive). El software edita de manera 100% offline y exporta una **Single Page Application (SPA) HTML5** ultra-ligera, autónoma y auto-ejecutable para el comensal.

---

## 🌟 Características y Diferenciales Únicos

### 1. 🛡️ Soberanía de Datos y Funcionamiento Offline-First
* **Datos Propios:** Toda la base de datos de tu menú (platos, precios, alérgenos) se almacena localmente en archivos estructurados **`.json`** universales dentro de tu equipo. Eres el dueño absoluto de tu activo digital.
* **Entorno Seguro Standalone:** El editor portable se ejecuta localmente en Windows (como un ejecutable portátil `.exe` de un solo clic) o en macOS/Linux mediante Node.js, sin necesidad de instalación compleja ni bases de datos en la nube.
* **Resiliencia Operativa:** Si la conexión a internet de la calle cae un sábado por la noche, tú puedes seguir gestionando, modificando y actualizando el stock de tu carta en el editor local sin ningún problema.

### 2. ⚡ Compilador "Zero Bloatware" (Rendimiento Extremo)
* **Carga Instantánea (<0.2 segundos):** Al pulsar "Exportar HTML", el editor compila todo el menú, estilos, interactividad y motores de accesibilidad en un **único archivo `.html` autocontenido**.
* **Optimización Multimedia:** Las imágenes y logotipos vectoriales SVG se optimizan y se incrustan directamente en formato **Base64**. Esto elimina la posibilidad de "enlaces rotos" a imágenes y garantiza máxima nitidez al hacer zoom.
* **Sin Cookies ni Rastreadores:** Protege la privacidad de tus comensales. El HTML resultante tiene cero cookies de seguimiento de terceros, lo que ahorra drásticamente batería y datos móviles en la mesa.

### 3. 🚫 Seguridad Alimentaria y Filtro de Salud (R.D. 126/2015)
* **Motor Predictivo de Alérgenos:** Como un auténtico "Copiloto Tecnológico", mientras redactas el título o descripción de un plato, un algoritmo predictivo analiza el texto y preselecciona de forma automática los alérgenos oficiales (ej. si escribes *"Sardina curada con vinagre"*, preselecciona *Pescado* y *Sulfitos*).
* **Filtros Activos para el Cliente:** El comensal abre un panel interactivo lateral, selecciona sus intolerancias y **la carta oculta dinámicamente en tiempo real** los platos incompatibles, eliminando por completo la ansiedad y asegurando su salud.

### 4. 👁️ Hospitalidad Universal y Accesibilidad Real (WCAG 2.1)
No es un simple contraste de fondo. Es una suite de accesibilidad activa integrada directamente en el navegador del comensal:
* **Control de tamaño de texto** dinámico mediante slider táctil.
* **Modo Blanco y Negro (Escala de Grises)** para daltonismo o acromatopsia.
* **Alto Contraste** para facilitar la lectura bajo la luz del sol en terrazas o salones íntimos.
* **Guía de Lectura Horizontal** interactiva para no perder la línea de precios.
* **Tipografía Accesible para Dislexia** seleccionable de forma inmediata.

### 5. 🔊 La Carta que "Habla" (Web Speech API)
* **Lectura de Voz Fonética Bilingüe:** Un motor que realiza la lectura del menú de forma natural. Lee el plato en español y seguidamente en inglés de manera secuencial.
* **Normalización Fonética Inteligente:** Traduce números de precio a lenguaje hablado (ej. *"19,00 €") *"diecinueve euros"* / *"nineteen euros"*) y normaliza la pronunciación de fracciones (*"1/2") (*"media ración de"*) y anglicismos.

### 6. 🗣️ Asesor Gastronómico y Enfoque de Entrada Unificado
* **Entrada unificada mediante barra `" / "`:** Olvídate de duplicar formularios o mantener menús paralelos. Escribe *"Patatas / French Fries"* en un solo campo; el sistema procesará la barra diagonal y maquetará ambos idiomas con una jerarquía cromática elegante de forma automática.
* **Cultura Gastronómica:** El motor de traducción integrado explica el contexto del recetario tradicional y local (ej. traduciendo y explicando la textura del *"Salmorejo"* o del *"Ajoblanco"* de forma profesional para el comensal internacional).

### 7. 📊 Comparativa de Rendimiento Técnico: DIMEDI vs. SaaS Convencionales

En el comedor de un restaurante, la cobertura de datos móviles suele ser deficiente debido a muros gruesos, sótanos o zonas de sombra. Una carta pesada frustra al cliente y sobrecarga su dispositivo. Aquí se detalla la diferencia real en la mesa:

| Métrica de Rendimiento | Ecosistema DIMEDI (SPA Autónoma) 🟢 | Competencia SaaS Tradicional (En la Nube) 🔴 |
| :--- | :--- | :--- |
| **Peso Total de Transferencia** | **150 KB - 400 KB** <br>*(Todo inyectado, optimizado y comprimido)* | **3.500 KB - 8.000 KB+ (3.5MB - 8MB+)** <br>*(Imágenes pesadas, scripts y trackers innecesarios)* |
| **Número de Peticiones HTTP** | **1 sola petición** <br>*(Fichero único autocontenido de carga global)* | **45 a 120+ peticiones** <br>*(Llamadas constantes a bases de datos remotas y CDNs)* |
| **Velocidad de Carga (Buena red)** | **< 0.2 segundos** (Latencia Cero) | **2.5 a 5.0 segundos** (Dependiente de colas de servidor) |
| **Velocidad de Carga (Mala red / Sótano)** | **< 0.5 segundos** (Carga instantánea offline en caché) | **12+ segundos o Error (Timeout)** (Bloqueo del servicio) |
| **Cookies y Rastreadores** | **0 (Cumplimiento de privacidad nativo y limpio)** | **5 a 15+ trackers** (Google Analytics, Pixel de Meta, etc.) |
| **Banners de consentimiento (RGPD)** | **No requeridos** (No recopila datos personales) | **Obligatorios y molestos** (Interrumpen el acceso en mesa) |
| **Dependencia de Servidor Externo** | **Ninguna (Soberanía absoluta)** | **Total** (Si falla el hosting del proveedor, se cae tu QR) |
| **Impacto en Hardware Móvil** | **Consumo ínfimo / Sin recalentamiento del móvil** | **Drenaje activo de batería y sobreesfuerzo de CPU** |

---

## 📂 Estructura del Ecosistema Local

Al descomprimir tu software **DIMEDI** en tu equipo o en un pendrive, obtendrás la siguiente estructura limpia de archivos y carpetas:

```bash
DIMEDI-Tu-Establecimiento-Editor-Portable/
├── Training-Tasca-Editor.exe     # Ejecutable principal local para Windows (sin instalación)
├── launcher.cjs                  # Lanzador multiplataforma para macOS o Linux (requiere Node.js)
├── INSTRUCCIONES.md              # Manual técnico paso a paso de uso rápido integrado
├── qr-code.svg                   # Archivo vectorial QR de las mesas
├── VENTAJAS_Y_SOLUCIONES.md      # Dossier comercial y de ventajas operativas del sistema
├── LEEME.txt                     # Resumen de inicio rápido
├── dist/                         # Interfaz visual y estilos nativos del editor
└── client-data/                  # ¡La carpeta más importante! Resguardo de soberanía
    ├── data/                     # Archivos de base de datos estructural del restaurante (.json)
    ├── images/                   # Logotipos, imágenes de categorías y favicons corporativos
    ├── backups/                  # Copias de seguridad automáticas con marca de fecha/hora
    └── exports/                  # Histórico de cartas compiladas listas para su publicación
```
*(Nota: No borres ni muevas ningún elemento fuera de esta carpeta para asegurar la integridad de la base de datos local).*

---

## ⚙️ Pipeline de Publicación Instantánea (Paso a Paso)

El flujo para actualizar la carta a tus comensales se resume en un proceso ágil de 3 pasos:





1. **Edita:** Abre tu programa local `.exe`. Actualiza precios, añade suplementos o marca un plato que se ha agotado en cocina con el botón **"AGOTADO"**.
2. **Exporta:** Haz clic en **"Exportar HTML"** en la barra central. El sistema compilará y guardará tu archivo unificado y optimizado en la subcarpeta `client-data/exports/`.
3. **Publica:** Copia el archivo resultante, renombrándolo a **`index.html`**, y súbelo a la raíz de tu servidor web tradicional, o arrástralo directamente a un repositorio gratuito de **GitHub Pages**, Netlify o Vercel. 

> **¡Tu Código QR nunca cambia!** El código QR físico impreso desde **`qr-code.pdf`** en tus soportes es permanente. Siempre apuntará a la misma dirección web donde tienes alojada la carta, permitiéndote actualizar el menú miles de veces de forma invisible.

---

## 📜 Licencia, Dirección de Arte y Autoría

**© 2026 Manolo Recio | Todos los derechos reservados.**

Concepto, diseño de interfaz de usuario y de experiencia (UI/UX), desarrollo de ingeniería web de alto rendimiento y arquitectura de marca creados íntegramente por:

**Manolo Recio** | *Senior Graphic & Visual Designer, Scenography Developer & AI Creative Developer*

* **Sitio Web & Portfolio:** [manolorecio.github.io/Manolo-Recio-Portfolio/](https://manolorecio.github.io/Manolo-Recio-Portfolio/)
* **Email de Contacto:** [manoloreciodesign@gmail.com](mailto:manoloreciodesign@gmail.com)
* **Teléfono:** <a href="tel:+34633555950">633 555 950</a>

***

*No entregues a tus comensales un PDF frío, incómodo e inaccesible. Ofrece una experiencia interactiva de autoría que respete su privacidad, cuide su salud alimentaria y libere para siempre a tu establecimiento de las cuotas abusivas de suscripción.*

***

