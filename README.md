# Sistema de Registro de Comida

Una aplicación web completa para el registro y gestión de consumo de alimentos en comedores empresariales.

## Características

### 🍽️ **Registro Principal**
- Búsqueda rápida de empleados por nombre o número
- Escáner de códigos QR para identificación
- Interfaz intuitiva y fácil de usar

### 👥 **Gestión de Empleados**
- Añadir, editar y eliminar empleados
- Gestión de múltiples comedores
- Importación masiva via CSV
- Generación automática de gafetes con códigos QR
- Control de empleados inactivos (21+ días)

### 📊 **Seguimiento y Reportes**
- Registro de consumos por semana
- Historial completo de semanas guardadas
- Exportación a Excel de datos
- Estadísticas detalladas de consumo

### 🔧 **Panel de Administración**
- Gestión de dispositivos y tablets
- Configuración de comedores
- Control de acceso con contraseñas
- Monitoreo de actividad

### 🔐 **Características de Seguridad**
- Autenticación de administradores
- Sistema de PIN opcional para empleados
- Identificación única de dispositivos
- Respaldo en tiempo real con Firebase

## Tecnologías Utilizadas

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Estilos**: Tailwind CSS
- **Base de Datos**: Firebase Firestore
- **Autenticación**: Firebase Auth
- **Generación QR**: QRCode.js
- **Audio**: Tone.js
- **Exportación**: html2canvas, JSZip, FileSaver.js

## Estructura del Proyecto

```
├── index.html          # Aplicación principal (SPA)
└── README.md          # Este archivo
```

## Despliegue

Este proyecto está configurado para GitHub Pages y se despliega automáticamente desde la rama principal.

**URL de acceso**: `https://abrahamal1994-gif.github.io`

## Uso

### Para Empleados
1. Abrir la aplicación en el navegador
2. Buscar el nombre o número de empleado
3. Confirmar identidad y registrar consumo

### Para Administradores
1. Hacer clic en el botón "Admin" en la esquina superior derecha
2. Ingresar la contraseña de administrador
3. Acceder a todas las funcionalidades de gestión

## Configuración

La aplicación utiliza Firebase para el almacenamiento de datos. Las credenciales están configuradas en el archivo principal.

### Contraseñas por Defecto
- **Administrador**: `1560`
- **Comedores**: `comedoresadmin`

## Soporte para Dispositivos

- ✅ Navegadores web modernos
- ✅ Dispositivos móviles y tablets
- ✅ Modo offline básico
- ✅ Responsive design

## Licencia

Proyecto privado para uso interno de la empresa.