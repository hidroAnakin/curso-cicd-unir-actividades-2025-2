# 🚀 Entornos de Integración y Entrega Continua - UNIR

> Repositorio oficial del curso de CI/CD de la Maestría en Desarrollo y Operaciones de Software

## 📋 Información del Curso

- **Universidad**: Universidad Internacional de La Rioja (UNIR)
- **Programa**: Maestría en Desarrollo y Operaciones de Software
- **Asignatura**: Entornos de Integración y Entrega Continua
- **Modalidad**: Online con sesiones prácticas
- **Duración**: 17 semanas

## 🎯 Objetivos de Aprendizaje

Al completar este curso serás capaz de:

1. ✅ Dominar Git y GitHub para trabajo colaborativo
2. ✅ Diseñar e implementar pipelines CI/CD
3. ✅ Automatizar pruebas y despliegues
4. ✅ Aplicar principios DevOps en proyectos reales
5. ✅ Configurar infraestructura como código
6. ✅ Implementar monitoreo y observabilidad

## 📚 Contenido del Curso

### Módulo 1: Fundamentos
- Introducción a DevOps
- Control de versiones con Git
- Colaboración con GitHub
- Branching strategies

### Módulo 2: Integración Continua
- Conceptos de CI
- GitHub Actions
- Jenkins fundamentals
- Automatización de pruebas

### Módulo 3: Entrega Continua
- Pipelines CD
- Estrategias de deployment
- Ambientes y configuración
- Rollback strategies

### Módulo 4: Infraestructura como Código
- Introducción a IaC
- Terraform basics
- Ansible para configuración
- Versionado de infraestructura

### Módulo 5: Contenedores y Orquestación
- Docker fundamentals
- Docker Compose
- Introducción a Kubernetes
- CI/CD con contenedores

### Módulo 6: Monitoreo y Observabilidad
- Logs, métricas y traces
- Prometheus y Grafana
- Alerting strategies
- SRE principles

## 🛠️ Requisitos Técnicos

### Software Necesario
- **Git** (2.40+): [Descargar](https://git-scm.com/)
- **Visual Studio Code**: [Descargar](https://code.visualstudio.com/)
- **Docker Desktop**: [Descargar](https://www.docker.com/products/docker-desktop/)
- **Python** (3.9+): [Descargar](https://www.python.org/)
- **Node.js** (16+): [Descargar](https://nodejs.org/)

### Cuentas Requeridas
- [ ] GitHub (con email verificado)
- [ ] Docker Hub
- [ ] AWS Free Tier (opcional)

### Configuración Inicial
```bash
# Configurar Git
git config --global user.name "Tu Nombre"
git config --global user.email "tu.email@unir.net"

# Clonar este repositorio
git clone https://github.com/unir-cicd/curso-2025.git
cd curso-2025

# Verificar instalación
./scripts/verificar-entorno.sh
```

## 📁 Estructura del Repositorio

```
curso-2025/
├── README.md                 # Este archivo
├── .github/                  # Configuración GitHub
│   └── workflows/           # Pipelines CI/CD
├── actividades/             # Actividades del curso
│   ├── actividad1/         # Introducción Git/GitHub
│   ├── actividad2/         # Primer Pipeline CI
│   ├── actividad3/         # Automatización Tests
│   └── proyecto-final/     # Proyecto integrador
├── ejemplos/               # Código de ejemplo
│   ├── docker/            # Ejemplos Docker
│   ├── terraform/         # Ejemplos IaC
│   └── pipelines/         # Ejemplos CI/CD
├── recursos/              # Material adicional
│   ├── slides/           # Presentaciones
│   ├── guias/            # Guías prácticas
│   └── cheatsheets/      # Referencias rápidas
└── scripts/              # Scripts de utilidad
```

## 📝 Actividades y Evaluación

### Actividades Prácticas (60%)
- **Actividad 1**: Control de versiones y colaboración (10%)
- **Actividad 2**: Pipeline CI básico (15%)
- **Actividad 3**: Testing automatizado (15%)
- **Actividad 4**: Deployment automatizado (20%)

### Proyecto Final (30%)
Implementación completa de un pipeline CI/CD para una aplicación real

### Participación (10%)
- Contribuciones en clase
- Code reviews
- Discusiones en issues

## 🚦 Flujo de Trabajo

### Para Estudiantes

1. **Fork** este repositorio
2. **Clone** tu fork localmente
3. **Crea una rama** para cada actividad:
   ```bash
   git checkout -b actividad1/tu-nombre-apellido
   ```
4. **Desarrolla** la solución
5. **Commit** con mensajes descriptivos:
   ```bash
   git commit -m "feat: implementa validación de entrada en formulario"
   ```
6. **Push** tu rama:
   ```bash
   git push origin actividad1/tu-nombre-apellido
   ```
7. **Crea un Pull Request** hacia el repo principal

### Convenciones de Commits
Usamos [Conventional Commits](https://www.conventionalcommits.org/):
- `feat:` Nueva funcionalidad
- `fix:` Corrección de bugs
- `docs:` Cambios en documentación
- `test:` Añadir o modificar tests
- `refactor:` Refactorización de código
- `chore:` Tareas de mantenimiento

## 🤝 Código de Conducta

Este curso sigue el [Código de Conducta de UNIR](CODE_OF_CONDUCT.md). 

Puntos clave:
- Respeto mutuo en todas las interacciones
- Colaboración constructiva
- Aprendizaje inclusivo
- Cero tolerancia al plagio

## 📞 Soporte y Contacto

### Canales de Comunicación
- **Issues**: FORO "Pregúntale a tu profesor"

### FAQ
<details>
<summary>¿Puedo usar otro editor en lugar de VSCode?</summary>

Sí, pero las demostraciones se harán con VSCode. Asegúrate de que tu editor tenga buena integración con Git.
</details>

<details>
<summary>¿Necesito experiencia previa con Git?</summary>

No es necesaria, pero es recomendable. Las primeras sesiones cubren los fundamentos.
</details>

<details>
<summary>¿Puedo entregar actividades tarde?</summary>

Se acepta con penalización del 10% por día de retraso, máximo 3 días.
</details>

## 📚 Recursos Adicionales

### Libros Recomendados
- 📖 "The DevOps Handbook" - Kim, Humble, Debois, Willis
- 📖 "Continuous Delivery" - Humble, Farley
- 📖 "Pro Git" - Chacon, Straub (gratis online)

### Cursos Complementarios
- 🎓 [GitHub Skills](https://skills.github.com/)
- 🎓 [Docker 101 Tutorial](https://www.docker.com/101-tutorial)
- 🎓 [Kubernetes Basics](https://kubernetes.io/docs/tutorials/kubernetes-basics/)

### Herramientas Online
- 🔧 [Git Branching Playground](https://learngitbranching.js.org/)
- 🔧 [RegEx101](https://regex101.com/)
- 🔧 [Terraform Playground](https://www.katacoda.com/courses/terraform/playground)

## 📊 Estado del Curso

![Build Status](https://img.shields.io/github/workflow/status/unir-cicd/curso-2025/CI)
![Issues](https://img.shields.io/github/issues/unir-cicd/curso-2025)
![PRs](https://img.shields.io/github/issues-pr/unir-cicd/curso-2025)
![License](https://img.shields.io/badge/license-MIT-blue)

## ⭐ Contribuciones Destacadas

¡Gracias a todos los estudiantes que han contribuido a mejorar este curso!

<!-- ALL-CONTRIBUTORS-LIST:START -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

## 📄 Licencia

Este material está bajo licencia [MIT](LICENSE). Eres libre de usar, modificar y distribuir el contenido con atribución.

---

<p align="center">
  <strong>¡Bienvenidos al mundo de DevOps! 🚀</strong><br>
  Preparados para automatizar todo 🤖
</p>
