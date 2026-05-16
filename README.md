# Nochu Toast & Coffee — Kiosco Digital Interactivo 
Kiosco digital interactivo de autoservicio para Nochu Toast; Coffee. Desarrollado bajo un enfoque (Lógico, Funcional y Asíncrono) integrando Tau Prolog en entornos web para la inferencia automatizada de comandas, combos y cashback.

Este proyecto consiste en un **Kiosco Digital de Autoservicio Interactivo** diseñado como caso de estudio para la cafetería **Nochu** en Mérida, Yucatán. La aplicación combina la fluidez visual de un sistema táctil gamificado con un robusto motor de reglas de negocio ejecutado mediante programación multiparadigma.

Inspirado en el juego de Papa's Pizzeria pero con la función de ordenar como si llegaras a un Mcdonald's (Proyección en el futuro para Nochu), mis amigos y dueños de Nochu Toast me dieron permiso para poder llevar acabo este proyecto. 

El sistema permite a los clientes seleccionar productos del menú real, personalizar ingredientes (agregar extras o remover elementos base) y calcular subtotales, descuentos por combos y obsequios de fidelidad en tiempo real mediante inferencia lógica declarativa.

---

## Paradigmas de Programación Implementados

1. **Paradigma Lógico (Declarativo):** Implementado mediante **Tau Prolog** para estructurar la Base de Conocimiento (`KB`). Controla los precios base, la compatibilidad de ingredientes, la inferencia automática del *Nochu Combo* (10% de descuento) y cortesías de lealtad al superar ciertos umbrales de compra.
2. **Paradigma Funcional:** Uso de funciones puras de orden superior en JavaScript (`.map()`, `.filter()`, `.reduce()`) para la manipulación e inmutabilidad de la comanda antes de ser parseada al motor lógico, evitando efectos secundarios en el estado de la UI.
3. **Paradigma Asíncrono:** Gestión de consultas al motor lógico y generación dinámica de elementos (como códigos QR de Cashback) mediante promesas de JavaScript, manteniendo la interfaz de usuario responsiva y fluida a 60 FPS.

---

## Estructura del Repositorio

* `nochu-kiosk.html` : Interfaz táctil interactiva completa, lógica de control y Base de Conocimiento de Prolog integrada.
* `Reporte_Proyecto_Nochu.pdf` : Documentque detalla la arquitectura y los fundamentos de los paradigmas aplicados.
* `README.md` : Instrucciones de instalación, configuración y ejecución del entorno.
* `NOCHU INSPO.pdf` : Documento donde expreso el proceso creativo del proyecto con la inspo.

---

## Instalación Local y Ejecución

Debido a la arquitectura desacoplada y al uso de **Tau Prolog** integrado nativamente en el entorno del cliente web, el proyecto no requiere de complejas instalaciones de servidores backend ni dependencias pesadas de Node.js. Se ejecuta directamente sobre cualquier navegador moderno.

* Página web (UBICACIÓN, INSTAGRAM Y EL PROYECTO "nochu-kiosk.html": https://nochukiosko.framer.website/  
* Proyecto:  https://jsrangel666.github.io/Motor-de-Inferencia-L-gica-como-Servicio/

### Pasos para ejecución local:

1. **Clonar el repositorio** en tu máquina local:
   ```bash
   git clone [ https://jsrangel666.github.io/Motor-de-Inferencia-L-gica-como-Servicio/)

   
