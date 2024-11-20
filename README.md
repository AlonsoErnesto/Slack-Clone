# Slack Clone - Frontend

Este proyecto es una implementación de un clon de Slack que utiliza herramientas modernas para ofrecer una interfaz de usuario sofisticada y funcionalidades avanzadas. A continuación, se detallan las tecnologías clave utilizadas.

## 🖥️ Frontend e Interfaz de Usuario

### **Radix UI (`@radix-ui/*`)**
- Colección de componentes accesibles como `Avatar`, `Dialog`, `DropdownMenu`, `Popover`, `Separator`, `Slot`, y `Tooltip`.
- Simplifica la construcción de interfaces de usuario modernas, accesibles y consistentes.

### **Lucide React (`lucide-react`)**
- Biblioteca de iconos optimizada para React con un diseño limpio y personalizable.

### **TailwindCSS**
- Framework CSS basado en clases utilitarias para construir interfaces modernas y responsivas rápidamente.
- **Complementos:**
  - `tailwind-merge`: Permite combinar y sobrescribir clases de Tailwind eficientemente.
  - `tailwindcss-animate`: Añade animaciones predefinidas con clases CSS.

### **Sonner**
- Biblioteca para mostrar notificaciones altamente personalizables con estilo moderno.

### **React Verification Input (`react-verification-input`)**
- Componente diseñado para campos de ingreso de códigos de verificación, ideal para flujos de autenticación (2FA u OTP).

### **CMDK (`cmdk`)**
- Herramienta para implementar menús estilo *Command Palette*, ofreciendo accesos rápidos y mejorando la experiencia del usuario.

### **React Resizable Panels (`react-resizable-panels`)**
- Facilita la creación de paneles ajustables, especialmente útiles en interfaces con diseños flexibles.

## 📊 Gestión de Estados y Datos

### **Jotai**
- Librería de gestión de estados reactivos. Es ligera y escalable, adecuada para proyectos complejos.

### **React Use (`react-use`)**
- Conjunto de *hooks* útiles que simplifican funcionalidades comunes en React, como efectos y controles avanzados.

### **Convex (`convex`) y Auth (`@convex-dev/auth`)**
- Plataforma y herramientas para manejar datos en tiempo real y autenticación segura.

## 🛠️ Manipulación y Formateo de Datos

### **Date-fns**
- Biblioteca de utilidades para formatear, manipular y operar con fechas en JavaScript.

### **Emoji Mart (`@emoji-mart/*`)**
- Biblioteca para integrar emojis, con componentes optimizados para React y datos predefinidos.

### **Quill**
- Editor de texto enriquecido, ideal para entradas avanzadas como comentarios, publicaciones o formularios.

## 🎨 Temas y Estilos

### **Next Themes (`next-themes`)**
- Biblioteca para gestionar temas claros, oscuros u otros esquemas en aplicaciones basadas en Next.js.

### **Class Variance Authority (`class-variance-authority`)**
- Facilita la definición y gestión de variantes condicionales de clases CSS.

### **Clsx**
- Herramienta para combinar clases CSS condicionalmente, manteniendo un código más limpio y legible.

## 🔒 Autenticación y Verificación

### **@auth/core**
- Solución moderna para gestionar flujos de autenticación robustos en aplicaciones web.

---

### 🚀 Funcionalidades Clave
- **Interfaz accesible y moderna**: Utilizando Radix UI y TailwindCSS.
- **Autenticación segura**: Integración con `@auth/core` y `@convex-dev/auth`.
- **Manejo avanzado de estados y datos**: Gracias a Jotai y Convex.
- **Soporte de temas**: Implementación de temas dinámicos con `next-themes`.
- **Notificaciones personalizables**: Proporcionadas por Sonner.
- **Flexibilidad en diseño**: Paneles ajustables y menús interactivos para una experiencia de usuario mejorada.

Este clon de Slack no solo replica funcionalidades principales, sino que aprovecha tecnologías modernas para ofrecer una solución robusta y escalable.
