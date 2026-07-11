# Jaleaki

Jaleaki es un directorio colaborativo de oportunidades laborales, programas de prácticas profesionales (internships) y certificaciones, orientado principalmente a estudiantes y recién egresados de áreas de ingeniería y tecnología.

El proyecto utiliza archivos JSON como fuente de datos y una interfaz web estática para consultar, filtrar, editar y exportar información sin necesidad de un servidor.

## Características

- Buscar empleos, internships y certificaciones.
- Filtrar por carrera, ubicación, proveedor, dominio y categoría.
- Editar registros directamente desde el navegador.
- Guardar cambios temporalmente mediante LocalStorage.
- Exportar los cambios como archivos JSON.
- Compatible con GitHub Pages.
- No requiere backend.

## Estructura del proyecto

```
.
├── credentials/
│   └── data.json
├── internship/
│   └── data.json
├── jobs/
│   └── data.json
├── index.html
├── README.md
└── CONTRIBUTING.md
```

## Formato de los datos

### Jobs

```json
{
    "company": "Google",
    "program": "Careers",
    "description": "...",
    "location": "Remoto",
    "degree": ["ISC", "IE"],
    "tags": ["Software"],
    "url": "https://..."
}
```

### Internships

```json
{
    "company": "Microsoft",
    "program": "Explore",
    "description": "...",
    "location": "México",
    "degree": ["ISC"],
    "tags": ["Internship"],
    "url": "https://..."
}
```

### Credentials

```json
{
    "name": "AWS Certified Cloud Practitioner",
    "provider": "AWS",
    "providerGroup": "Cloud",
    "domain": "Cloud Computing",
    "category": "Foundations",
    "type": "Certification",
    "description": "...",
    "tags": ["Cloud"],
    "url": "https://..."
}
```

## Ejecutar el proyecto

Clona el repositorio:

```bash
git clone https://github.com/DasReyxr/CPC-api.git
cd CPC-api
```

Inicia cualquier servidor estático.

Con Python:

```bash
python -m http.server
```

Con Node.js:

```bash
npx serve
```

Después abre:

```
http://localhost:8000
```

## Edición de datos

La interfaz permite editar la información desde el navegador.

Los cambios:

- Se almacenan únicamente en LocalStorage.
- No modifican automáticamente los archivos del repositorio.
- Pueden exportarse como archivos JSON para posteriormente subirlos mediante un Pull Request.

## Objetivo

Jaleaki busca mantener un directorio abierto y actualizado de:

- Bolsas de trabajo.
- Páginas oficiales de empresas.
- Programas de internships.
- Certificaciones profesionales.

Cualquier persona puede contribuir agregando nuevas oportunidades o corrigiendo información existente.

## Licencia

Este proyecto se distribuye bajo la licencia MIT.