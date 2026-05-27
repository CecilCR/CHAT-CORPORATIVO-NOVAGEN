# 🚨 Comité de Crisis – Simulador Estratégico NovaGen

Herramienta interactiva para simular una **sesión de crisis corporativa** dentro de un canal restringido de mensajería.  
Permite a los participantes leer el contexto, elegir una postura estratégica y enviar una intervención que se integra dinámicamente al chat.

🔗 **Demo en vivo**: [Insertar enlace después del despliegue]

---

## 📌 Descripción

Este simulador recrea un escenario realista de filtración de datos en una empresa tecnológica.  
Los usuarios deben:

1. **Leer** la conversación cifrada entre la Dirección Ejecutiva, Jefe de Comunicaciones y Legal.
2. **Pasar** al panel de decisión y elegir una postura:  
   - **Posición A**: Contener daño reputacional, blindar la operación.  
   - **Posición B**: Transparencia radical y asunción pública de responsabilidad.  
   - **Posición C**: Ganar tiempo, escalar a auditoría externa.
3. **Redactar** una intervención breve que incluya: posición elegida, riesgos priorizados e información necesaria.
4. **Enviar** la postura, que aparece automáticamente en el chat como un mensaje del usuario con estilo diferenciado.

El diseño imita aplicaciones de mensajería moderna (estilo WhatsApp/Teams) y separa claramente la lectura del chat de la toma de decisión, evitando confusiones.

---

## ✨ Características

- ✅ **Chat corporativo realista** con mensajes exactos del enunciado (Dirección Ejecutiva, Jefe de Comunicaciones, Legal, alertas internas).
- ✅ **Fecha dinámica**: muestra el día actual automáticamente (ej: `MARTES, 14 DE ABRIL 2025`).
- ✅ **Dos pantallas independientes**:  
  - Pantalla 1: solo lectura del chat.  
  - Pantalla 2: panel de decisión con opciones A/B/C y envío de intervención.
- ✅ **Intervención visible** en el chat con burbujas a la derecha (usuario) y avatares circulares.
- ✅ **Corrección visual** de viñetas (un solo punto por ítem, sin dobles puntos).
- ✅ **Validación** de selección de postura y texto antes de enviar.
- ✅ **Persistencia** de la última intervención al volver al chat.
- ✅ **Diseño responsivo** adaptable a móvil, tablet y escritorio.
- ✅ **Notificación toast** al enviar una intervención.
- ✅ **Código 100% autónomo** (HTML/CSS/JS puro, sin dependencias externas).

---

## 🖼️ Capturas de pantalla

*Pantalla 1: Chat corporativo (estilo mensajería)*  

![Captura del chat](./docs/chat-screen.png)

*Pantalla 2: Panel de decisión con opciones y editor*  

![Pantalla de decisión](./docs/strategy-screen.png)

> *Las imágenes son ilustrativas. Puedes generar las tuyas con herramientas de captura.*  
> *(Sugerencia: ejecutar localmente y tomar capturas)*

---

## 🛠️ Tecnologías utilizadas

- **HTML5** semántico
- **CSS3** (Flexbox, Grid, variables, animaciones, diseño responsivo)
- **JavaScript ES6+** (manejo del DOM, mensajes dinámicos, actualización de fecha)
- Sin frameworks externos ni librerías → fácil de alojar y modificar.

---

## 🚀 Cómo usar la herramienta

### Requisitos
- Navegador web moderno (Chrome, Edge, Firefox, Safari).
- No se necesita servidor, funciona completamente en cliente.

### Instalación local

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tuusuario/crisis-comite-simulador.git
