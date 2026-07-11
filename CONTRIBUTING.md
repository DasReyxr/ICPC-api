# Guía para contribuir

¡Gracias por querer colaborar con Jaleaki!

El objetivo del proyecto es mantener un directorio confiable, actualizado y fácil de consultar. Cualquier ayuda es bienvenida.

## ¿Qué puedes aportar?

Puedes contribuir agregando o mejorando:

- Empleos.
- Programas de internships.
- Certificaciones.
- Correcciones de información.
- Enlaces rotos.
- Mejoras a la documentación.

## Antes de agregar un registro

Verifica que:

- Sea una fuente oficial.
- El enlace funcione correctamente.
- No exista un registro duplicado.
- La descripción sea clara y breve.

## Jobs

Se aceptan, por ejemplo:

- Páginas oficiales de empleo de empresas.
- Portales universitarios.
- Programas de contratación.
- Job boards confiables.

Evita agregar:

- Enlaces de referidos.
- Sitios fraudulentos.
- Vacantes expiradas.
- Información sin fuente.

## Internships

Se recomienda agregar únicamente programas oficiales, tales como:

- Empresas.
- Universidades.
- Instituciones gubernamentales.
- Organizaciones reconocidas.

## Credentials

Se aceptan:

- Certificaciones.
- Certificados.
- Badges.
- Programas oficiales de formación.

Siempre que provengan del proveedor oficial.

## Formato del JSON

Mantén el mismo formato utilizado por el proyecto.

Ejemplo:

```json
{
    "company": "Example",
    "type": "Company",
    "description": "...",
    "location": "Remoto",
    "degree": ["ISC"],
    "tags": ["Software"],
    "url": "https://..."
}
```

## Proceso para contribuir

1. Haz un Fork del repositorio.
2. Crea una rama para tus cambios.

```bash
git checkout -b feature/nuevo-recurso
```

3. Realiza las modificaciones.
4. Verifica que el JSON sea válido.
5. Haz un commit descriptivo.

```bash
git commit -m "Agregar NVIDIA Careers"
```

6. Sube tu rama.

```bash
git push origin feature/nuevo-recurso
```

7. Abre un Pull Request explicando los cambios realizados.

## Recomendaciones

- Usa enlaces oficiales.
- Escribe descripciones claras y concisas.
- Evita lenguaje publicitario.
- Mantén el formato del proyecto.
- No agregues información duplicada.

## Reportar problemas

Si encuentras:

- Enlaces rotos.
- Información incorrecta.
- Programas desactualizados.
- Registros duplicados.

Puedes abrir un **Issue** describiendo el problema.

## Código de conducta

Mantén un ambiente de colaboración y respeto.

Todas las contribuciones son revisadas con el objetivo de conservar un directorio útil y de calidad para toda la comunidad.