# UniCIEO — Sistema de Virtualizacion Academica y Proyeccion de Costos

**Universidad CIEO | Vicerrectoria Academica**
*Vigilada Mineducacion*

---

## Descripcion

Sistema integral de gestion academica para la **Universidad CIEO**, enfocado en el seguimiento del proceso de virtualizacion de programas academicos, control de costos, gestion de contratos y cumplimiento de condiciones de Registro Calificado ante el MEN (Ministerio de Educacion Nacional de Colombia).

Aplicacion web de pagina unica (SPA) que funciona completamente en el navegador, sin necesidad de servidor backend.

---

## Modulos

### 1. Dashboard Ejecutivo
- Indicadores clave: programas, asignaturas, costos, contratos
- Estado SACES (Con Registro, Renovacion, Radicado, En Proceso, Pendiente)
- Resumen financiero consolidado
- Graficos interactivos (Chart.js)

### 2. Datos Programas (Registro Calificado)
- Seguimiento de las **15 condiciones del Decreto 1330**
- Tarjetas interactivas por programa
- Filtros por estado SACES
- Edicion de etapas con observaciones

### 3. Virtualidad Academica
- 15 programas y 216 asignaturas
- 65 transversales y 151 propias
- Editor de asignaturas multi-programa
- Barra de resumen con KPIs

### 4. Flujo de Caja
- Proyeccion financiera mensual (Dic-2025 a Jul-2026)
- Integracion de datos de contratos
- Grafico comparativo ejecutado vs. proyectado

### 5. Inversion y Contratos
- 6 contratos por **$267.700.000 COP**
- Doble aprobacion: VB Academica + Pago Financiera
- Proyeccion mensual vs. ejecucion real
- Grafico de analisis por contrato

### 6. Bitacora de Cambios
- Registro cronologico de acciones
- Filtros por programa y tipo

---

## Programas Academicos

| Codigo | Programa | Modalidad | Estado SACES | Seccion |
|--------|----------|-----------|-------------|---------|
| GSO | Gest. Serv. Odontologicos | Virtual | Con Registro | Actuales |
| ORT | Ortodoncia | Presencial | Renovacion | Actuales |
| IMP | Implantologia Oral | Presencial | Renovacion | Actuales |
| END | Endodoncia | Presencial | Con Registro | Actuales |
| PER | Periodoncia | Presencial | Con Registro | Actuales |
| GMS | Gcia. Mercadeo en Salud | Virtual | Radicado | Nuevos |
| GCS | Gcia. Calidad en Salud | Virtual | Radicado | Nuevos |
| ADM | Administracion en Salud | Virtual | Radicado | Nuevos |
| RO | Rehabilitacion Oral | Presencial | Radicado | Nuevos |
| ODO | Odontologia | Presencial | Radicado | Nuevos |
| GS | Gerencia de la Salud | Virtual | En Proceso | Proyeccion |
| AUD | Auditoria en Salud | Virtual | En Proceso | Proyeccion |
| SST | Gerencia de la SST | Virtual | En Proceso | Proyeccion |
| PSI | Psicologia | Virtual | En Proceso | Proyeccion |
| IS | Ingenieria de Software | Virtual | Pendiente | Proyeccion |

---

## Contratos Registrados

| ID | Contratista | Valor |
|----|-------------|-------|
| CPS-PJ-001-2025 | Visu S.A.S | $9.000.000 |
| CPS-PN-002-2026 | Daniel Orlando Montes Toro | $20.000.000 |
| CPS-PN-003-2026 | Daniel Orlando Montes Toro | $8.000.000 |
| CPS-PN-004-2026 | Daniel Orlando Montes Toro | $18.000.000 |
| CPS-PN-005-2026 | Politecnico de Colombia | $30.000.000 |
| CPS-PJ-001-2026 | Politecnico de Colombia | $182.700.000 |
| | **Total Inversion** | **$267.700.000** |

---

## Tecnologias

- **HTML5 / CSS3 / JavaScript ES6** — SPA de archivo unico
- **Chart.js** — Graficos interactivos
- **LocalStorage API** — Persistencia y auto-guardado
- **CSS Variables** — Paleta institucional UniCIEO
- **PapaParse** — Importacion/exportacion CSV

---

## Uso

1. Descargar `UniCIEO_Virtualizacion_FINAL.html`
2. Abrir en cualquier navegador moderno (Chrome, Edge, Firefox)
3. No requiere servidor, instalacion ni conexion a internet

### Auto-guardado
- Guardado automatico cada 30 segundos
- Guardado inmediato al hacer cambios
- Boton "Guardar archivo" descarga copia HTML actualizada
- Restauracion automatica al reabrir

---

## Paleta Institucional

| Variable | Color | Uso |
|----------|-------|-----|
| --color-red | #D40E1E | Color principal UniCIEO |
| --color-black | #171717 | Texto y encabezados |
| --color-success | #27ae60 | Completados / aprobados |
| --color-warning | #f39c12 | Pendientes |
| --color-danger | #e74c3c | Alertas y urgencias |

---

## Autor

**Andres Ivan Toledo**
Vicerrector Academico — Universidad CIEO

## Licencia

Uso interno institucional — Universidad CIEO. Todos los derechos reservados.
