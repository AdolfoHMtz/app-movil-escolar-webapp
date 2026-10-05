# 🎓 App Escolar — Gestión Académica

Sistema web de **gestión académica** para la materia *Desarrollo de Aplicaciones Móviles*. Permite administrar **administradores, maestros y alumnos**, registrar **eventos académicos** y consultar **gráficas** con estadísticas.

<p align="center">
  <a href="https://app-movil-escolar-webapp-ahm.netlify.app" target="_blank" rel="noopener">
    <img src="https://img.shields.io/badge/%F0%9F%9A%80%20Abrir%20app%20en%20vivo-00C7B7?style=for-the-badge&logo=netlify&logoColor=white" alt="Abrir en Netlify" />
  </a>
</p>

![Angular](https://img.shields.io/badge/Angular-16-DD0031?style=flat-square&logo=angular&logoColor=white)
![Angular Material](https://img.shields.io/badge/Angular_Material-757575?style=flat-square&logo=angular&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white)
![Django](https://img.shields.io/badge/Django_REST-5-092E20?style=flat-square&logo=django&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)

## Funciones

- Inicio de sesión y panel con menú lateral.
- Registro, edición y baja de **administradores, maestros y alumnos**.
- Registro y edición de **eventos académicos**.
- **Gráficas** con estadísticas (ng2-charts).
- Tablas con paginación en español.

## Estructura

```
├── app-movil-escolar-webapp/   Frontend en Angular (desplegado en Netlify)
│   └── src/app/
│       ├── screens/            Pantallas: login, home, admin, maestros, alumnos, eventos, gráficas
│       ├── partials/           Formularios de registro, navbar y sidebar
│       ├── modals/             Diálogos de edición y eliminación
│       └── services/           Conexión con la API
└── app_movil_escolar_api/      API REST en Django (desplegada en Render)
```

## Cómo ejecutarlo

**Frontend**

```bash
cd app-movil-escolar-webapp
npm install
npm start
```

**Backend**

```bash
cd app_movil_escolar_api
python -m venv venv
source venv/bin/activate   # En Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

## Autor

**Adolfo Huerta** · [@AdolfoHMtz](https://github.com/AdolfoHMtz) · 2025
