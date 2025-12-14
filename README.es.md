<div align="center">
  <sub>
    <a href="README.md">English</a> | Español | <a href="README.zh.md">简体中文</a>
  </sub>
</div>

<h1 align="center">
  Blu - Potencia tus herramientas con la que les ha estado faltando.
</h1>

<p align="center">
  <a href="https://github.com/GarvAgnihotri/blu">
    <img src="https://img.shields.io/github/stars/GarvAgnihotri/blu?style=flat-square" alt="Estrellas en GitHub" />
  </a>
  <a href="https://github.com/GarvAgnihotri/blu/issues">
    <img src="https://img.shields.io/github/issues/GarvAgnihotri/blu?style=flat-square" alt="Problemas en GitHub" />
  </a>
  <a href="https://github.com/GarvAgnihotri/blu/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/GarvAgnihotri/blu?style=flat-square" alt="Licencia" />
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=Garv.blu">
    <img src="https://img.shields.io/visual-studio-marketplace/v/Garv.blu?style=flat-square" alt="Versión en VS Code Marketplace" />
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=Garv.blu">
    <img src="https://img.shields.io/visual-studio-marketplace/i/Garv.blu?style=flat-square" alt="Instalaciones en VS Code" />
  </a>
  <img src="https://img.shields.io/visual-studio-marketplace/r/Garv.blu?style=flat-square" />
</p>

<div align="center">
  <table>
    <tbody>
      <td align="center">
        <a href="https://marketplace.visualstudio.com/items?itemName=Garv.blu" target="_blank"><strong>Descargar en VS Marketplace</strong></a>
      </td>
      <td align="center">
        <a href="https://github.com/GarvAgnihotri/blu/discussions" target="_blank"><strong>Solicitudes de Funciones</strong></a>
      </td>
    </tbody>
  </table>
</div>

---

<p align="center">
  <img src="https://github.com/user-attachments/assets/demo-placeholder-1" width="100%" alt="Demo de Blu mostrando flujo de trabajo orientado a objetivos" />
  <em>Demo: Blu planificando y ejecutando una tarea compleja de refactorización</em>
</p>

## ¿Qué es Blu?

**Blu** es una extensión de VS Code con IA que te ayuda a trabajar con **objetivos en lugar de prompts**. Describe lo que quieres lograr, y Blu analizará tu código, planificará los cambios necesarios y los ejecutará paso a paso—siempre con tu aprobación.

Construido sobre la poderosa base de Cline, Blu extiende el concepto con flujos de trabajo mejorados orientados a objetivos y un enfoque en la colaboración del desarrollador.

---

## Características Principales

### Desarrollo Orientado a Objetivos
<img align="right" width="350" src="https://github.com/user-attachments/assets/sidebar-demo-placeholder">

**Trabaja desde la intención, no la implementación.** Simplemente describe tu objetivo—"agregar autenticación de usuario," "refactorizar este componente," o "arreglar el diseño móvil"—y Blu creará un plan detallado antes de realizar cualquier cambio.

- **Desglose inteligente de tareas**: Blu analiza tu solicitud y la divide en pasos lógicos
- **Planificación consciente del contexto**: Comprende la estructura y dependencias de tu proyecto
- **Flujo de trabajo de aprobación**: Revisa y aprueba cada paso antes de la ejecución

> [!TIP]
> Abre Blu en la barra lateral (Ver → Paleta de Comandos → "Blu: Open Sidebar") para trabajar junto a tu código. Esto te da visibilidad completa del proceso de planificación y ejecución de Blu.

<!-- Clear float -->
<div style="clear: both;"></div>

### Comprensión Profunda del Código
<img align="left" width="360" src="https://github.com/user-attachments/assets/code-analysis-placeholder">

Blu no solo lee archivos—entiende tu proyecto. A través del análisis AST, mapeo de dependencias y búsqueda semántica, Blu se pone al día rápidamente, incluso en bases de código grandes y complejas.

- **Análisis AST**: Comprende la estructura y relaciones del código
- **Gestión inteligente del contexto**: Solo agrega archivos relevantes al contexto
- **Reconocimiento de patrones**: Identifica patrones comunes y mejores prácticas
- **Conciencia entre archivos**: Comprende cómo los cambios afectan toda la base de código

<!-- Clear float -->
<div style="clear: both;"></div>

### Ejecución con Intervención Humana
<img align="right" width="340" src="https://github.com/user-attachments/assets/approval-workflow-placeholder">

**Siempre tienes el control.** Blu presenta un plan claro y muestra diferencias antes de realizar cualquier cambio. Aprueba, modifica o rechaza cada paso mientras Blu trabaja en tu tarea.

- **Vistas de diferencias interactivas**: Ve exactamente qué cambiará
- **Aprobación paso a paso**: Controla el ritmo de ejecución
- **Retroalimentación en tiempo real**: Proporciona entrada mientras Blu trabaja
- **Deshacer/Rehacer**: Control total sobre cada modificación

<!-- Clear float -->
<div style="clear: both;"></div>

### Integración de Herramientas Potentes

#### Creación y Edición de Archivos
Blu puede crear nuevos archivos, modificar los existentes e incluso refactorizar entre múltiples archivos manteniendo la calidad y consistencia del código.

#### Integración de Terminal
Ejecuta comandos directamente en tu terminal con monitoreo completo de salida. Blu puede:
- Instalar dependencias y ejecutar scripts de compilación
- Iniciar servidores de desarrollo
- Ejecutar pruebas y migraciones
- Desplegar aplicaciones

#### Automatización del Navegador
Para tareas de desarrollo web, Blu puede:
- Lanzar tu aplicación en un navegador
- Interactuar con elementos de UI
- Capturar capturas de pantalla y registros de consola
- Depurar problemas visuales y de tiempo de ejecución

### Soporte Multi-Modelo
<img align="left" width="370" src="https://github.com/user-attachments/assets/model-support-placeholder">

Usa tu proveedor de IA preferido:
- **OpenAI**
- **Anthropic**
- **Google Gemini**
- **OpenRouter**
- **Y Muchos Más**

El seguimiento de costos y monitoreo del uso de tokens te ayuda a mantenerte dentro del presupuesto.

<!-- Clear float -->
<div style="clear: both;"></div>

### Extensible a través de MCP
<img align="right" width="350" src="https://github.com/user-attachments/assets/mcp-tools-placeholder">

Extiende las capacidades de Blu con el **Model Context Protocol**. Crea herramientas personalizadas para tu flujo de trabajo específico:

- **"Agrega una herramienta que obtenga tickets de Jira"** – Trabaja directamente desde requisitos
- **"Agrega una herramienta que verifique el estado de AWS"** – Monitorea infraestructura
- **"Agrega una herramienta que consulte tu base de datos"** – Obtén información de datos reales
- **"Agrega una herramienta que se integre con tu API"** – Conéctate a servicios internos

Blu incluso puede ayudarte a crear e instalar estas herramientas automáticamente.

<!-- Clear float -->
<div style="clear: both;"></div>

### Asistencia Consciente del Contexto
<img align="left" width="360" src="https://github.com/user-attachments/assets/context-menu-placeholder">

Agrega contexto relevante con comandos simples:

- **`@ Agregar Contexto`** – Incluye el contenido de un archivo específico

Escribe para buscar y agregar rápidamente lo que Blu necesita para entender tu tarea.

<!-- Clear float -->
<div style="clear: both;"></div>

### Puntos de Control y Control de Versiones
<img align="right" width="340" src="https://github.com/user-attachments/assets/checkpoints-placeholder">

**Experimenta de forma segura.** Blu crea puntos de control mientras trabaja, permitiéndote:
- **Comparar** cualquier punto de control con el estado actual
- **Restaurar** a puntos anteriores en el tiempo
- **Ramificar** diferentes enfoques
- **Fusionar** experimentos exitosos

Todos los cambios se rastrean en la Línea de Tiempo de VS Code para una fácil reversión.

<!-- Clear float -->
<div style="clear: both;"></div>

---

## Comenzando

### Instalación Rápida
1. **Instala desde VS Code Marketplace**: Busca "Blu" o usa [este enlace directo](https://marketplace.visualstudio.com/items?itemName=Garv.blu)
2. **Abre Blu**: Haz clic en el icono de Blu en la Barra de Actividad o ejecuta `Blu: Open Sidebar` desde la Paleta de Comandos
3. **Configura tu proveedor de IA**: Agrega tu clave API en configuraciones (Ctrl+, → Extensiones → Blu)
4. **Comienza tu primera tarea**: Escribe un objetivo y deja que Blu planifique la ejecución

---

## Arquitectura y Filosofía

Blu se construye sobre tres principios fundamentales:

1. **Claridad Primero** – Sin cambios ocultos, sin magia. Todo es transparente y explicable.
2. **Control del Desarrollador** – Apruebas cada cambio. Blu sugiere, tú decides.
3. **Inteligencia Colaborativa** – Blu amplifica tus habilidades, no reemplaza tu juicio.

### Cómo Funciona Blu
1. **Análisis de Objetivo** – Comprende tu intención y requisitos
2. **Recolección de Contexto** – Analiza partes relevantes de tu código
3. **Generación de Plan** – Crea un plan de ejecución paso a paso
4. **Ejecución Interactiva** – Ejecuta cada paso con tu aprobación
5. **Validación** – Prueba y verifica los resultados

---

## Contribuyendo

¡Aceptamos contribuciones! Así es como puedes comenzar:

1. **Bifurca el repositorio** y clónalo localmente
2. **Configura el entorno de desarrollo**:
   ```bash
   npm install
   npm run compile
