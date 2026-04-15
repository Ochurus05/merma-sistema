# merma-sistema
app control de merma mcdonalds

Sistema de Gestión de Merma – McDonald's

Descripción

Este proyecto consiste en el desarrollo de una aplicación de escritorio en Java que permite registrar, gestionar y analizar la merma de productos dentro de una sucursal de McDonald's, facilitando la captura de datos y reduciendo errores humanos en el proceso operativo.

Problema identificado

Actualmente, el registro de merma en la operación diaria presenta las siguientes problemáticas:

Captura manual lenta
Errores humanos en el registro
Falta de datos en tiempo real
Pérdida o inconsistencia de información

Solución

Se desarrolló una aplicación que permite:

Registro rápido de merma (manual)
Generación automática de merma (simulación)
Almacenamiento en archivo CSV
Generación de reportes semanales y mensuales

Arquitectura

           Usuario
              ↓  
     Aplicación Java (Swing)
              ↓
       Lógica de negocio
              ↓
   Archivo CSV (persistencia)

  
Tabla de Contenidos
  °Requerimientos
  °Instalación
  °Configuración
  °Uso
  °Contribución
  °Roadmap
  
Requerimientos
-Software
  °Java JDK 17 o superior
  °NetBeans IDE
  °Git
  °Maven

Dependencias
  °JUnit (pruebas)
  °Librerías estándar de Java

Infraestructura
 °No requiere servidor web
 °No requiere base de datos
 °Funciona localmente

Instalación
1. Clonar repositorio
git clone https://github.com/tu-usuario/sistema-merma-mcd.git
cd sistema-merma-mcd
2. Abrir en NetBeans
File → Open Project
Seleccionar carpeta del proyecto

Ejecutar aplicación
Click derecho → Run Project
O ejecutar clase Main.java

Ejecutar pruebas
mvn test

Despliegue
Local
Ejecutar .jar generado:
java -jar sistema-merma.jar
Nube (opcional)
Puede desplegarse en servicios como Heroku (modo Java app)

Configuración
Archivo principal
mermas.csv
Parámetros configurables
Lista de productos (en código)
Ruta del archivo CSV

Uso
-Usuario final
1. Abrir aplicación
2. Seleccionar producto
3. Ingresar cantidad
4. Presionar:
"Registrar Manual"
"Automático"
5. Consultar reportes

Usuario administrador
°Validar datos registrados
°Revisar archivo CSV
°Ejecutar reportes
°Gestionar productos (en código)

Contribución
Pasos para contribuir

# 1. Clonar repo
git clone https://github.com/tu-usuario/sistema-merma-mcd.git

# 2. Crear branch
git checkout -b feature/nueva-funcionalidad

# 3. Hacer cambios
git add .
git commit -m "Nueva funcionalidad"

# 4. Subir cambios
git push origin feature/nueva-funcionalidad

# 5. Crear Pull Request en GitHub
Flujo de trabajo
°master → producción
°develop → desarrollo
°branches → features

Roadmap
Próximas mejoras
°Interfaz gráfica avanzada (JTable)
°Exportación a Excel
°Sistema de login
°Integración con base de datos
°Dashboard con gráficas
°Versión móvil

Video de demostración


Producto
Ejecutable

Archivo generado:

sistema-merma.jar
Ejecución
java -jar sistema-merma.jar
📌 Notas finales

Este proyecto fue desarrollado con fines académicos para mejorar el proceso de captura de merma en operaciones reales de McDonald's, aplicando buenas prácticas de desarrollo, control de versiones y gestión de proyectos.
