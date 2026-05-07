# 🚀 SauceDemo QA Automation Project

Proyecto de automatización QA desarrollado utilizando Python, Selenium y Pytest para validar funcionalidades críticas del sitio demo de e-commerce SauceDemo.

---

# 📌 Objetivo del Proyecto

El objetivo de este proyecto es demostrar conocimientos prácticos en:

* Automatización de pruebas Web
* Selenium WebDriver
* Pytest
* Estructuración de proyectos QA
* Uso de Fixtures
* Validaciones UI
* Manejo de waits explícitos
* Integración con Git y GitHub

Este proyecto fue desarrollado como práctica profesional de automatización QA utilizando buenas prácticas y estructura escalable.

---

# 🛠️ Tecnologías Utilizadas

| Tecnología         | Descripción                   |
| ------------------ | ----------------------------- |
| Python             | Lenguaje principal            |
| Pytest             | Framework de testing          |
| Selenium WebDriver | Automatización de navegador   |
| WebDriverManager   | Gestión automática de drivers |
| ChromeDriver       | Driver para Google Chrome     |
| Git                | Control de versiones          |
| GitHub             | Repositorio remoto            |

---

# 📂 Estructura del Proyecto

```bash
PRELABAUTOMATION/
│
├── tests/
│   └── test_saucedemo.py
│
├── utils/
│   └── helpers.py
│
├── conftest.py
├── pytest.ini
├── requirements.txt
├── .gitignore
└── README.md
```

---

# ✅ Casos de Prueba Automatizados

## 🔐 Login de Usuario

Validaciones:

* Inicio de sesión exitoso
* Redirección correcta al catálogo
* Verificación de título principal

---

## 🛍️ Validación de Catálogo de Productos

Validaciones:

* Visualización correcta de productos
* Existencia de productos en inventario
* Verificación del nombre del primer producto

---

## 🛒 Agregar Producto al Carrito

Validaciones:

* Agregar producto correctamente
* Validación del badge del carrito
* Verificación del producto agregado

---

# ⚙️ Instalación del Proyecto

## 1. Clonar repositorio

```bash
git clone https://github.com/TU_USUARIO/saucedemo-automation.git
```

---

## 2. Ingresar al proyecto

```bash
cd saucedemo-automation
```

---

## 3. Crear entorno virtual (Opcional recomendado)

```bash
python -m venv venv
```

### Activar entorno virtual

Windows:

```bash
venv\Scripts\activate
```

---

## 4. Instalar dependencias

```bash
pip install -r requirements.txt
```

---

# ▶️ Ejecución de Tests

## Ejecutar todos los tests

```bash
py -m pytest -v
```

---

## Ejecutar un test específico

```bash
py -m pytest tests/test_saucedemo.py -v
```

---

# 📸 Evidencia de Ejecución

Ejemplo esperado:

```bash
============================= test session starts =============================
collected 3 items

tests/test_saucedemo.py ...                                           [100%]

============================== 3 passed ==============================
```

---

# 🧠 Conceptos Aplicados

Durante el desarrollo del proyecto se aplicaron conceptos como:

* Fixtures de Pytest
* Reutilización de código
* Selectores CSS/XPATH
* Explicit Waits
* Assertions
* Organización modular
* Automatización E2E
* Manejo de WebDriver
* Flujo básico de Page Interaction

---

# 🔥 Mejoras Futuras

Próximas mejoras planeadas:

* Implementar Page Object Model (POM)
* Integrar reportes HTML
* Screenshots automáticos en fallos
* Data Driven Testing
* Integración CI/CD con GitHub Actions
* Cross Browser Testing
* Integración con Playwright

---

# 👨‍💻 Autor

Carlos Aparicio

QA Manual / QA Automation Engineer


# ⭐ Notas

Este proyecto fue desarrollado con fines educativos y de práctica profesional para fortalecer habilidades en QA Automation y testing automatizado.