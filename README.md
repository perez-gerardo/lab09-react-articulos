# Lab09 - ReactJS con Bootstrap

## 📋 Descripción
Aplicación ReactJS que implementa una tabla de gestión de artículos con diseño Bootstrap. Permite visualizar, agregar y eliminar artículos de forma dinámica.

## 🚀 Características
- **Tabla responsiva** con Bootstrap
- **Eliminación dinámica** de artículos
- **Diseño moderno** con estilos Bootstrap
- **Componente de clase** React
- **Estado reactivo** con `this.state` y `this.setState`

## 🛠️ Tecnologías Utilizadas
- ReactJS
- Bootstrap 5
- JavaScript ES6+
- HTML5/CSS3

## 📦 Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/perez-gerardo/lab09-react-articulos.git
```

2. Instala las dependencias:
```bash
npm install
```

3. Ejecuta la aplicación:
```bash
npm start
```

4. Abre tu navegador en `http://localhost:3000`

## 🎯 Funcionalidades

### Gestión de Artículos
- **Visualización**: Tabla con código, descripción y precio
- **Eliminación**: Botón "Borrar" para cada artículo
- **Diseño**: Tabla responsiva con estilos Bootstrap

### Artículos Incluidos
- Coca-cola - $2.50
- Inka-cola - $2.20  
- Fanta - $1.70

## 📱 Diseño Bootstrap
- **Tabla responsiva**: Se adapta a dispositivos móviles
- **Estilos modernos**: `table-striped`, `table-hover`, `table-bordered`
- **Encabezado oscuro**: `table-dark` para mejor contraste
- **Botones estilizados**: `btn-danger` para eliminar

## 🎥 Video Explicativo
Este proyecto incluye un video explicativo de máximo 4 minutos que demuestra:
- Explicación del código
- Funcionamiento de la aplicación
- Demostración de eliminación de artículos

## 📸 Capturas
- Capturas del código fuente
- Capturas de la ejecución en navegador
- Demostración de funcionalidades

## 👨‍💻 Autor
**Agustín** - Estudiante de Desarrollo de Aplicaciones Empresariales

## 📚 Laboratorio
**Lab09 - ReactJS**  
**Docente**: Renato Usnayo Cáceres  
**Institución**: Tecsup

## 📝 OBSERVACIONES
- **Instalación inicial**: La creación del proyecto ReactJS con `create-react-app` requirió varios intentos debido a problemas de permisos en Windows.
- **Integración Bootstrap**: La instalación de Bootstrap fue exitosa y su integración en el proyecto fue sencilla mediante `import 'bootstrap/dist/css/bootstrap.min.css'`.
- **Conversión de función a clase**: Se tuvo que convertir el componente funcional por defecto a un componente de clase para implementar el estado y los métodos requeridos.
- **Gestión de estado**: La implementación del método `borrar()` funcionó correctamente usando `filter()` para mantener la inmutabilidad del estado.
- **Diseño responsivo**: Bootstrap facilitó la creación de una tabla responsiva que se adapta a diferentes tamaños de pantalla.

## 🎯 CONCLUSIONES
- **Objetivo cumplido**: Se logró implementar exitosamente una aplicación ReactJS con gestión de artículos y diseño Bootstrap profesional.
- **Aprendizaje técnico**: Se dominó el uso de componentes de clase, gestión de estado con `this.state` y `this.setState`, y la integración de Bootstrap en React.
- **Resolución de problemas**: Los errores de instalación se solucionaron creando un nuevo proyecto con nombre diferente y verificando el directorio de trabajo.
- **Resultado final**: La aplicación cumple con todos los requisitos del laboratorio, incluyendo tabla responsiva, eliminación dinámica y diseño moderno con Bootstrap.
- **Valor agregado**: El README documentado y el repositorio en GitHub facilitan la presentación y futuras referencias del proyecto.