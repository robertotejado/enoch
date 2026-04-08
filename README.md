-----

# ⬡ ENOCH ◈

### **The Watchers Awakening — AI-Powered Pentest Assistant**

*(Nota: Sustituye esta URL por la de tu imagen una vez subida)*

**Enoch** es una suite de auditoría de seguridad avanzada impulsada por Inteligencia Artificial local. Basada originalmente en el proyecto METATRON, esta versión evoluciona hacia una interfaz mística e inmersiva diseñada para profesionales que buscan centralizar su flujo de reconocimiento y análisis heurístico en una sola herramienta.

-----

## ✨ Características Principales

  * **⚡ Motor en Tiempo Real**: Ejecución de herramientas industriales (`nmap`, `nikto`, etc.) con salida línea por línea directa en la consola de la interfaz.
  * **🤖 Inteligencia Artificial Local**: Integración nativa con **Ollama** para analizar vectores de ataque y vulnerabilidades sin que tus datos salgan de tu red.
  * **🛡️ Arquitectura "The Watchers"**: Una estética inspirada en el misticismo enoquiano con una Splash Screen inmersiva y un diseño oscuro moderno optimizado para largas sesiones de trabajo.
  * **📂 Gestión de Datos Segura**: Persistencia automática de sesiones en una base de datos **SQLite** local y configuración protegida en el directorio del usuario (`~/.enoch/`).
  * **🔍 Inteligencia de Amenazas**: Buscador integrado de **CVE (NVD)** y resultados web de DuckDuckGo directamente en el dashboard.
  * **💾 Exportación Rápida**: Guarda tus escaneos y hallazgos en formato `.txt` con un solo clic.

-----

## 📋 Requisitos del Sistema

Para garantizar el funcionamiento óptimo de los "Vigilantes", tu sistema debe cumplir con lo siguiente:

### **1. Entorno Linux**

Enoch está optimizado para distribuciones de ciberseguridad:

  * **Sistemas**: Kali Linux o Ubuntu (22.04 LTS o superior).

### **2. Dependencias de Red y Pentesting**

Asegúrate de tener instaladas las siguientes herramientas en tu sistema (el paquete `.deb` intentará resolverlas automáticamente):

  * `nmap`, `whois`, `whatweb`, `curl`, `dnsutils` (para `dig`), `nikto`.

### **3. Cerebro IA (Ollama)**

Enoch requiere un servidor de IA local activo:

  * **Servidor**: Ollama ejecutándose en `http://127.0.0.1:11434`.
  * **Modelo recomendado**: `qwen2.5:7b` (o cualquier modelo compatible configurado desde el menú de Ajustes).

-----

## 🚀 Instalación y Lanzamiento

Actualmente, Enoch se distribuye exclusivamente como un paquete **Debian (.deb)** para facilitar una instalación limpia con accesos directos al sistema.

1.  **Descarga** el archivo `enoch.deb` desde la sección de [Releases].
2.  **Instala** el paquete usando la terminal:
    ```bash
    sudo dpkg -i enoch.deb
    ```
3.  **Resuelve dependencias** si es necesario:
    ```bash
    sudo apt install -f
    ```

### **Ejecución**

Puedes iniciar la herramienta de dos maneras:

  * **Menú de Aplicaciones**: Busca **"Enoch PenTest"** (icono de la efigie de Enoch).
  * **Terminal**: Simplemente escribe `enoch`.

-----

## ⚙️ Configuración Inicial

Al abrir Enoch por primera vez, ve al panel de **Configuración** ⚙️:

1.  Verifica la **URL de Ollama** (por defecto `http://127.0.0.1:11434`).
2.  Introduce el **nombre del modelo** que has descargado (ej: `qwen2.5:7b`, `qwen2.5:3b`).
3.  Usa el botón **"Verificar conexiones"** para confirmar que los Vigilantes están listos.

-----

## ⚠️ Aviso Legal (Disclaimer)

Esta herramienta ha sido creada con fines estrictamente educativos y para profesionales de la seguridad informática autorizados. El uso de Enoch para atacar infraestructuras sin permiso explícito por escrito es ilegal y responsabilidad exclusiva del usuario final.

-----

*Developed by Enoch Team — Based on the METATRON engine.*

-----

Como Enoch es un ecosistema interactivo, he preparado una visualización del flujo de trabajo para que tus usuarios entiendan cómo la herramienta coordina las fases de escaneo y el análisis de la IA:
<img width="1280" height="815" alt="pantalla-enoch" src="https://github.com/user-attachments/assets/05192273-ec2f-4ab1-9de4-8aa50cb13cb5" />

