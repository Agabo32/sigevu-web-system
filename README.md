<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=30&duration=3000&pause=1000&color=2E86C1&center=true&vCenter=true&width=600&lines=🏠+SIGEVU;Sistema+Integral+de+Gestión;de+Viviendas" alt="Typing SVG" />

<br/>

![Version](https://img.shields.io/badge/versión-1.0.0-2E86C1?style=for-the-badge)
![Status](https://img.shields.io/badge/estado-completado-27AE60?style=for-the-badge)
![Type](https://img.shields.io/badge/tipo-pasantía_profesional-8E44AD?style=for-the-badge)
![License](https://img.shields.io/badge/licencia-académica-F39C12?style=for-the-badge)

<br/>

> **Sistema web desarrollado durante pasantías profesionales en CORPOLARA para optimizar la gestión, consulta y administración de beneficiarios, viviendas y proyectos habitacionales.**

<br/>

[✨ Características](#-características) &nbsp;•&nbsp; [🛠️ Tecnologías](#️-tecnologías-utilizadas) &nbsp;•&nbsp; [📸 Capturas](#-capturas-de-pantalla) &nbsp;•&nbsp; [⚙️ Instalación](#️-instalación) &nbsp;•&nbsp; [👨‍💻 Autor](#-autor)

</div>

---

## 📖 Descripción

**SIGEVU** *(Sistema Integral para la Gestión de Viviendas)* es una plataforma web diseñada para **centralizar y digitalizar** la administración de programas habitacionales, brindando acceso rápido a la información de beneficiarios, viviendas y proyectos.

Desarrollado durante mis pasantías profesionales en **CORPOLARA**, el proyecto aplicó buenas prácticas de ingeniería de software, diseño relacional de bases de datos y principios de arquitectura MVC, resultando en una herramienta funcional utilizada en entorno institucional real.

```
🏢 Empresa:      CORPOLARA
📅 Período:      Pasantías Profesionales
🎯 Objetivo:     Digitalizar la gestión de programas habitacionales
🧩 Arquitectura: MVC (Modelo - Vista - Controlador)
```

---

## ✨ Características

<table>
  <tr>
    <td>

**👥 Beneficiarios**
- Registro y actualización de datos personales
- Consulta avanzada con filtros múltiples
- Historial completo por beneficiario

**🏘️ Viviendas**
- Registro detallado de unidades habitacionales
- Vinculación con beneficiario y proyecto
- Control de estado y disponibilidad

**📁 Proyectos**
- Administración de proyectos habitacionales
- Seguimiento de avance y asignaciones
- Estadísticas por proyecto

    </td>
    <td>

**🗺️ Ubicaciones**
- Gestión de ubicaciones geográficas
- Organización por estado, municipio y parroquia

**📊 Reportes**
- Generación de reportes detallados
- Exportación de datos para toma de decisiones

**⚡ Herramientas**
- 📥 Importación masiva de datos
- 🔐 Sistema de autenticación seguro
- 🖥️ Panel administrativo completo
- 📱 Diseño totalmente responsive

    </td>
  </tr>
</table>

---

## 🛠️ Tecnologías Utilizadas

<div align="center">

### Frontend
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

### Backend
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)

### Base de Datos
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### Herramientas
![XAMPP](https://img.shields.io/badge/XAMPP-FB7A24?style=for-the-badge&logo=xampp&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

</div>

---

## 📸 Capturas de Pantalla

<details>
<summary><b>🔐 Login — Pantalla de acceso al sistema</b></summary>
<br/>

![Login](docs/images/SIGEVU-Login.png)

</details>

<details>
<summary><b>👥 Gestión de Beneficiarios — Listado y administración</b></summary>
<br/>

![Beneficiarios](docs/images/SIGEVU-BENEFICIARIOS.png)

</details>

<details>
<summary><b>📋 Datos del Beneficiario — Ficha completa</b></summary>
<br/>

![Datos Beneficiarios](docs/images/SIGEVU-4.png)

</details>

<details>
<summary><b>📊 Reportes — Generación y visualización</b></summary>
<br/>

![Reportes](docs/images/SIGEVU-3.png)

</details>

---

## 📸 Capturas de Pantalla
### Login
![Login](docs/images/SIGEVU-Login.png)
### Gestión de Beneficiarios
![Beneficiarios](docs/images/SIGEVU-BENEFICIARIOS.png)
### Datos del Beneficiario
![Datos_Beneficiarios](docs/images/SIGEVU-4.png)
### Reportes
![Reportes](docs/images/SIGEVU-3.png)

## 🗄️ Estructura del Proyecto

```
📦 SIGEVU/
├── 🎨 assets/              # Recursos estáticos (CSS, JS, imágenes)
├── ⚙️  config/              # Configuración de base de datos y app
├── 🎮 controllers/         # Controladores MVC
├── 🗃️  models/              # Modelos y lógica de negocio
├── 👁️  views/               # Vistas y plantillas HTML
├── 🗄️  database/            # Scripts SQL y migraciones
└── 🚀 index.php            # Punto de entrada principal
```

---

## ⚙️ Instalación

Sigue estos pasos para ejecutar el proyecto localmente:

**1.** 📥 **Clonar el repositorio**
```bash
git clone https://github.com/Agabo32/Sistema_Central_de_Vivienda.git
cd Sistema_Central_de_Vivienda
```

**2.** 🗄️ **Crear la base de datos MySQL**
```sql
CREATE DATABASE sigevu CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;
```

**3.** 📂 **Importar el archivo SQL**
```bash
mysql -u root -p sigevu < database/sigevu.sql
```

**4.** 🔧 **Configurar credenciales** en `config/database.php`
```php
define('DB_HOST', 'localhost');
define('DB_NAME', 'sigevu');
define('DB_USER', 'tu_usuario');
define('DB_PASS', 'tu_contraseña');
```

**5.** 🚀 **Iniciar con XAMPP o Apache** y abrir en el navegador:
```
http://localhost/SIGEVU
```

---

## 👨‍💻 Autor

<div align="center">

<img src="https://avatars.githubusercontent.com/Agabo32" width="100" style="border-radius:50%;" alt="Gabriel Torrealba"/>

### Gabriel Torrealba

**Estudiante de Ingeniería en Sistemas**
*Especializado en desarrollo web y bases de datos*

[![GitHub](https://img.shields.io/badge/GitHub-Agabo32-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Agabo32)

</div>

---

## 📄 Licencia

```
Proyecto desarrollado con fines académicos y profesionales.
Todos los derechos reservados © Gabriel Torrealba
```

---

<div align="center">

⭐ **Si este proyecto te fue útil, considera dejar una estrella en el repositorio** ⭐

<img src="https://komarev.com/ghpvc/?username=Agabo32&label=Visitas+al+perfil&color=2E86C1&style=flat" alt="Profile views"/>

</div>
