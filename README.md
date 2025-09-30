# House Admin - Django Project

Una aplicación web desarrollada con Django para la administración de casas y habitaciones.

## 🚀 Características

- Sistema de gestión de habitaciones
- Autenticación de usuarios
- Panel de administración
- CRUD completo para entidades
- Interfaz web responsiva

## 🛠️ Instalación

1. **Clona el repositorio**
   ```bash
   git clone https://github.com/tu-usuario/houseadmin.git
   cd houseadmin
   ```

2. **Crea un entorno virtual**
   ```bash
   python3 -m venv env
   source env/bin/activate  # En Linux/Mac
   # env\Scripts\activate   # En Windows
   ```

3. **Instala las dependencias**
   ```bash
   pip install -r requirements.txt
   ```

4. **Ejecuta las migraciones**
   ```bash
   python3 manage.py makemigrations
   python3 manage.py migrate
   ```

5. **Crea un superusuario (opcional)**
   ```bash
   python3 manage.py createsuperuser
   ```

## 🏃‍♂️ Uso

Para iniciar el servidor de desarrollo:

```bash
python3 manage.py runserver
```

Visita `http://127.0.0.1:8000/` en tu navegador.

## 📁 Estructura del Proyecto

```
houseadmin/
├── base/                 # App principal
│   ├── models.py        # Modelos de datos
│   ├── views.py         # Vistas
│   ├── urls.py          # URLs de la app
│   ├── forms.py         # Formularios
│   └── templates/       # Templates HTML
├── houseadmin/          # Configuración del proyecto
│   ├── settings.py      # Configuraciones
│   └── urls.py          # URLs principales
├── templates/           # Templates globales
└── manage.py           # Script de gestión de Django
```

## 🔧 Comandos Útiles

- `python3 manage.py runserver` - Iniciar el servidor de desarrollo
- `python3 manage.py startapp <app_name>` - Crear una nueva app
- `python3 manage.py makemigrations` - Crear migraciones
- `python3 manage.py migrate` - Aplicar migraciones
- `python3 manage.py createsuperuser` - Crear superusuario
- `python3 manage.py collectstatic` - Recopilar archivos estáticos

## 🤝 Contribuir

1. Haz un fork del proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Confirma tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📝 Notas de Desarrollo

- La app creada debe agregarse en `INSTALLED_APPS` en `settings.py`
- Los templates deben configurarse en `TEMPLATES` en `settings.py`
- Para implementar CRUD se necesita modificar `views.py`, `urls.py` y los templates
- Revisar la implementación de autenticación en las vistas

## 📚 Recursos

Tutorial seguido: [Django Tutorial](https://www.youtube.com/watch?v=PtQiiknWUcI&t=6854s)