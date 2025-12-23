# The J-Handbook

Plataforma web de documentación interactiva para la estandarización de prácticas modernas en Java, con ejecución de código en tiempo real y análisis estático.

> _Proyecto educativo independiente no afiliado con Oracle. Todo el contenido refleja opiniones y experiencias personales de los autores._

## Descripción

Este proyecto nace de la necesidad de contar con una herramienta que facilite el aprendizaje de Java mediante una documentación opinada que no solo explique conceptos, sino que permita ejecutarlos y validarlos en tiempo real. Implementamos una arquitectura híbrida con renderizado de islas para optimizar el rendimiento y mejorar la experiencia de usuario.

## Características

- 🚀 Ejecución de código Java en tiempo real
- 📊 Análisis estático de código
- 🎯 Documentación opinada basada en mejores prácticas
- ⚡ Arquitectura híbrida con renderizado optimizado
- 🔧 API REST construida con Spring Boot

## Tecnologías

### Backend

- **Java 21** (JDK 24)
- **Spring Boot 3.x**
- **Maven** - Gestión de dependencias
- **Spring Web** - API REST
- **Lombok** - Reducción de código boilerplate
- **Spring Boot DevTools** - Desarrollo ágil

### Frontend

- **Astro** - Framework web moderno
- **React** - Componentes interactivos
- **Tailwind CSS** - Estilos
- **pnpm** - Gestor de paquetes
- **Node.js** - Entorno de ejecución

## Requisitos Previos

- JDK 24 instalado (configurado para Java 21)
- Maven 3.6 o superior
- Node.js 18 o superior
- pnpm 8 o superior
- Git

## Instalación

### Clonar el repositorio

```bash
git clone https://github.com/tu-usuario/java-mastery-interactive.git
cd java-mastery-interactive
```

### Configurar el Backend

1. Asegúrate de tener configurada la variable de entorno `JAVA_HOME` apuntando a tu JDK 24:

```bash
# Windows
set JAVA_HOME=C:\Path\To\JDK24
# Linux/Mac
export JAVA_HOME=/path/to/jdk24
```

2. Verifica la instalación de Maven:

```bash
mvn --version
```

La API estará disponible en `http://localhost:8080`

### Configurar el Frontend

1. Navega a la carpeta web:

```bash
cd web
```

2. Instala las dependencias con pnpm:

```bash
pnpm install
```

3. Ejecutar el servidor de desarrollo:

```bash
pnpm dev
```

La aplicación frontend estará disponible en `http://localhost:4321`

### Ejecutar en Producción

#### Backend

```bash
cd api
mvn clean package
java -jar target/api-0.0.1-SNAPSHOT.jar
```

#### Frontend

```bash
pnpm build
pnpm preview
```

## Desarrollo

### Backend

El proyecto utiliza Spring Boot DevTools, lo que permite reinicio automático durante el desarrollo. Simplemente guarda los cambios en tu IDE y la aplicación se recargará automáticamente.

### Frontend

Astro ofrece hot module replacement (HMR) para desarrollo rápido. Los cambios se reflejarán instantáneamente en el navegador.

## Estructura del Proyecto

```
The J-Handbook/
├── api/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   └── resources/
│   │   └── test/
│   └── pom.xml
├── web/
│   ├── src/
│   │   ├── components/
│   │   ├── layouts/
│   │   ├── pages/
│   │   └── styles/
│   ├── astro.config.mjs
│   ├── tsconfig.json
│   └── package.json
└── README.md
```

## Contribuciones

Este proyecto está siendo desarrollado activamente. Si encuentras algún problema o tienes sugerencias, no dudes en abrir un issue.

## Autores

- **Angel Eduardo Lugo López**
- **Alef David Esparza Díaz**
- **Cesar Axel Alvarez Gómez**

## Avisos Legales

### Sobre Java y Oracle

**Java** es una marca registrada de Oracle y/o sus afiliados. Este proyecto (**The J-Handbook**) es una herramienta educativa independiente y no está afiliada, respaldada, patrocinada ni aprobada por Oracle Corporation.

### Sobre el Contenido

Este proyecto presenta **opiniones y recomendaciones personales** de los autores basadas en su experiencia y estudio. No somos instructores certificados por Oracle ni representantes oficiales. El contenido refleja nuestras perspectivas sobre mejores prácticas en Java y no debe considerarse como documentación oficial o la única forma correcta de programar. Reconocemos que existen múltiples enfoques válidos para resolver problemas de programación.

**Recomendamos siempre consultar la documentación oficial de Oracle y otras fuentes confiables para complementar el aprendizaje.**

### Responsabilidad

Los autores **no se hacen responsables** del uso o mal uso de la información proporcionada. Este material se ofrece "tal cual" sin garantías de ningún tipo. El usuario asume toda la responsabilidad por la implementación de cualquier código o concepto presentado en esta plataforma.

## Licencia

Este proyecto está bajo desarrollo como proyecto personal y educativo.

**Licencia**

- ✅ **Uso personal y educativo:** Permitido y alentado
- ✅ **Modificación y distribución:** Permitido con atribución
- ❌ **Uso comercial:** No permitido
- ⚠️ **Sin garantías:** Los autores no son responsables del mal uso del software

Para más detalles, consulta el archivo [LICENSE](./LICENSE).

---

_Desarrollado con ☕ y mucho código_
