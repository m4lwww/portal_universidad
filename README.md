# Portal Universidad

### Los trámites escolares, sin filas y en minutos.

![Estado](https://img.shields.io/badge/estado-MVP%20funcionando-brightgreen)
![Python](https://img.shields.io/badge/Python-3.10-blue)
![Flask](https://img.shields.io/badge/Flask-3.0-black)
![Docker](https://img.shields.io/badge/Docker-listo-2496ED)

---

## El problema

Pedir una constancia hoy significa hacer fila, llenar formatos en papel, pagar en el banco y **esperar varios días**.
Los alumnos pierden tiempo y el personal de la escuela está saturado de trabajo manual.

## La solución

**Portal Universidad** reúne todos los trámites escolares en una sola plataforma web.

| Hoy | Con Portal Universidad |
|---|---|
| Filas en ventanilla | Todo desde el celular |
| Formatos en papel | Formularios en línea |
| Esperar días | Respuesta en minutos |
| Preguntar "¿ya quedó?" | Seguimiento en tiempo real |

## Ya funciona

No es solo una idea: el MVP ya está construido y corre en cualquier computadora con Docker.

- Página principal del portal
- API de estado del servicio (`/api/status`)
- Desplegable en segundos gracias a contenedores

## Por qué invertir

- Cualquier universidad o escuela es un cliente potencial.
- Los alumnos ya hacen todo desde el celular, menos sus trámites escolares.
- **Ingresos recurrentes:** cada escuela paga una suscripción anual.

## ¿Qué haremos con los 10 millones?

| Área | Inversión | Para qué |
|---|---|---|
| Desarrollo | $4,000,000 | Equipo de programadores y app móvil |
| Ventas | $3,000,000 | Llegar a las primeras universidades |
| Infraestructura | $2,000,000 | Servidores seguros y escalables |
| Marketing | $1,000,000 | Dar a conocer la plataforma |
| **Total** | **$10,000,000** | |

## Plan

- [x] **Fase 1:** MVP funcionando con Flask y Docker
- [ ] **Fase 2:** Constancias digitales y pagos en línea
- [ ] **Fase 3:** App móvil
- [ ] **Fase 4:** Prueba piloto con universidades

## Pruébalo tú mismo

```bash
git clone https://github.com/m4lwww/portal_universidad.git
cd portal_universidad
docker build -t portal .
docker run -p 5000:5000 portal
```

Abre `http://localhost:5000` en tu navegador.

---

### La escuela del futuro no tiene filas.

**Miguel Angel Jimenez Vilchis**