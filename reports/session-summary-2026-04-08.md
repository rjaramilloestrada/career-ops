# Career-Ops Session — 2026-04-08

## Tema Principal

Configuración inicial del sistema career-ops para Rafael Jaramillo Estrada, incluyendo onboarding completo, escaneo de portales de empleo, evaluación de ofertas, y generación de materiales de aplicación (CVs personalizados + cover letters) para roles de Technical Project Manager 100% remotos desde Ecuador.

---

## Decisiones Tomadas

### Perfil y Configuración
1. **CV guardado** como `cv.md` en la raíz del proyecto
2. **Perfil creado** en `config/profile.yml` con datos completos
3. **Archivo de personalización** `modes/_profile.md` creado con archetypes, framing adaptativo, narrativa, scripts de negociación y política de ubicación
4. **Arquetipos actualizados** en `modes/_shared.md` — reemplazados los defaults de AI/ML por roles alineados a Rafael: Technical Project Manager, Technical Lead, AI Product Manager, AI Automation Consultant, Head of Product (early-stage), Program Manager

### Filtro de Ubicación (decisión crítica)
5. **Filtro duro de remote implementado** — después del primer scan, muchas ofertas eran on-site en Alemania/US/EU. Se actualizó `profile.yml` y `_profile.md` con regla: **solo roles 100% remote ejecutables desde Ecuador**
   - Aceptable: Remote worldwide, Remote LATAM, Remote Americas, Contractor/consulting
   - Rechazar automáticamente: Remote US only, Remote EU only, Hybrid, On-site fuera de Ecuador
   - Score 1.0 → SKIP automático para cualquier rol geo-restringido

### Evaluaciones
6. **No generar PDFs hasta revisar scores** — el usuario pidió evaluaciones primero, PDFs después
7. **Solo evaluar Tier 1 + Tier 2** del primer scan (20 ofertas), no las 103 completas
8. **Segundo scan enfocado** en remote-worldwide/LATAM después de la corrección del filtro
9. **PDFs generados** para los 3 top picks del segundo scan: Tekton Labs, Tether, Paymentology

---

## Información Clave

### Datos del Candidato
- **Nombre:** Rafael Jaramillo Estrada
- **Email:** rajaramilloestrada@alumni.fullsail.edu
- **Teléfono:** +593994215250
- **Ubicación:** Guayaquil, Ecuador (UTC-5)
- **Visa:** No US/EU visa
- **Idiomas:** English (Fluent), Spanish (Native)
- **Educación:** B.S. Game Design (Full Sail University, Winter Park FL), A.A. Business Administration (Valencia Community College, Orlando FL)

### Roles Objetivo
- **Primary:** Technical Project Manager, Technical Lead
- **Secondary:** AI Product Manager, AI Automation Consultant
- **Adjacent:** Head of Product (early-stage), Program Manager

### Compensación
- **Rango objetivo:** $3,000–5,000/month USD
- **Mínimo:** $3,000/month
- **Moneda:** USD
- **Abierto a:** FTE, contract, consulting

### Experiencia Clave (proof points)
| Empresa | Rol | Período | Métricas |
|---------|-----|---------|----------|
| Karpowership | Senior PM | Ene 2024 – Ago 2025 | 4 Powerships, 25+ contractors, govt stakeholders, 90% commute reduction |
| Eagle Eye Productions | Founder & PM | Abr 2022 – Feb 2024 | 50+ clients, 15+ remote contractors, 2-4 day turnaround |
| PULSE: Beat & Burn | Technical Lead | Ago 2025 – Present | React/TS/Node/PostgreSQL PWA, $2,500+ first-week revenue, 100+ users, 125+ transactions |
| Glipy | Founder & Technical Lead | Ene 2026 – Present | Flutter/Supabase GLP-1 health app, Hispanic market, production-ready |
| Infernozilla | Business Developer | Ago 2024 – Nov 2024 | 500+ studios contacted, 75% response rate |
| FireApp | Front-End Developer | Oct 2020 – Feb 2022 | Webflow/Angular 9, 5-person team, 5 web projects |
| Radioi99 | Marketing PM | Sep 2016 – Dic 2020 | 1→8+ programs, 25% audience growth |
| Offshore Gas & Oil | Project Coordinator | Abr 2015 – Ago 2016 | 5+ remote sites, 20% productivity improvement |

### Preferencias
- **Remote:** Mandatory (100% desde Ecuador)
- **Evitar:** Roles puramente de coding sin componente PM/leadership, On-site/hybrid fuera de Ecuador, Roles que requieran work authorization US/EU/UK, Security clearance

---

## Scans Realizados

### Scan 1 — Greenhouse APIs + WebSearch (pre-filtro remote)
- **Fecha:** 2026-04-07
- **APIs queried:** 27 Greenhouse APIs
- **WebSearch queries:** 7
- **Ofertas encontradas:** ~1,200+ total
- **Filtradas por título:** 107 relevantes
- **Añadidas a pipeline:** 103
- **Problema:** No se filtró por remote/ubicación — muchas resultaron ser on-site o US/EU-only

### Scan 2 — Remote-Only desde Ecuador
- **Fecha:** 2026-04-07
- **Queries ejecutados:** 30 (WebSearch enfocado en remote/LATAM/worldwide)
- **Resultados encontrados:** 85+ total
- **Skipped (no remote desde Ecuador):** 28
- **Skipped (título):** 5
- **Duplicados:** 1
- **Nuevas añadidas a pipeline:** 24

---

## Evaluaciones Completadas

### Batch A — Tier 1 (Reports 001-005)
| # | Empresa | Rol | Score | Veredicto |
|---|---------|-----|-------|-----------|
| 001 | Helsing | Technical Project Manager | 2.8/5 | SKIP — Munich on-site, security clearance |
| 002 | Helsing | (Senior) Project Manager | 2.6/5 | SKIP — Munich/Berlin on-site, PMP required |
| 003 | Helsing | Programme Manager | 2.3/5 | SKIP — Vendor mgmt, consulting background req |
| 004 | GetYourGuide | Sr Technical PM, Merchandising | 3.4/5 | SKIP — Berlin hybrid |
| 005 | HelloFresh | Freelance Sr Technical PM | 2.0/5 | SKIP — Posición cerrada, German required |

### Batch B — Tier 1 (Reports 006-011)
- **Estado:** Agente lanzado pero resultados no confirmados en conversación. Reports 006-011 no aparecen en `reports/`. Posiblemente no completó o los archivos no se escribieron.

### Batch C — Tier 2 (Reports 012-020)
| # | Empresa | Rol | Score | Veredicto |
|---|---------|-----|-------|-----------|
| 012 | Intercom | Senior AI Product Manager | 2.8/5 | SKIP — Berlin hybrid |
| 013 | Arize AI | AI Product Manager | 3.2/5 | Condicional — Remote US, verificar intl |
| 014 | Vercel | PM - Agent Platform | 2.9/5 | SKIP — SF/NYC hybrid |
| 015 | Airtable | Program Manager, AI Programs | 3.5/5 | Condicional — Remote US, verificar intl |
| 016 | Airtable | Product Manager, AI | 3.0/5 | SKIP — San Francisco only |
| 017 | Aledade | Technical PM - AI Platform | 3.6/5 | Condicional — Remote US, verificar intl |
| 018 | Writer | AI Product Manager | 3.1/5 | Low confidence — JD parcial |
| 019 | Glean | Sr Solutions Engineer, LATAM | 2.5/5 | SKIP — Rol equivocado (SE no PM), Brasil/México |
| 020 | Jobgether | AI Delivery Manager | 3.7/5 | Mejor match Tier 2 — remote, comp baja, aggregator |

### Batch Remote 1 (Reports 021-026)
| # | Empresa | Rol | Score | Veredicto |
|---|---------|-----|-------|-----------|
| 021 | **Tether** | Technical Project Manager (100% Remote) | **3.9/5** | Aplicar — Web3 domain gap manejable |
| 022 | Pareto.AI | Technical Project Manager | 3.6/5 | Skip — Data ops, no es TPM real |
| 023 | Pareto.AI | Project Manager | 3.5/5 | Skip — SQL/Python heavy |
| 024 | **Tekton Labs** | Delivery Manager [ALL LATAM] | **4.3/5** | **Aplicar ya** — Mejor match overall |
| 025 | Kraken | Technical PM - Growth | 3.7/5 | Stretch — $96K-192K pero engineering-heavy |
| 026 | Devsu | Technical Project Manager | 4.1/5 | Posting cerrado — contactar directo |

### Batch Remote 2 (Reports 027-031)
| # | Empresa | Rol | Score | Veredicto |
|---|---------|-----|-------|-----------|
| 027 | Azumo | PM - Latin America | 3.6/5 | Skip — Chile/Brazil/Argentina only |
| 028 | Deel | Global Payroll Programs & Product Manager | 2.4/5 | SKIP — Cerrado + US/UK/EU only |
| 029 | Deel | Staff Product Operations Manager | 2.6/5 | SKIP — Cerrado + Europe only |
| 030 | **Paymentology** | Implementation Project Manager | **3.9/5** | Aplicar — Worldwide remote, verificar si activo |
| 031 | vCluster Labs | Technical Project Manager | 3.2/5 | SKIP — Europe only |

---

## Materiales de Aplicación Generados

### Tekton Labs — Delivery Manager (4.3/5) ⭐ TOP PICK
- **CV PDF:** `output/024-tekton-labs-cv.pdf` (2pp, 58.3 KB)
- **CV HTML:** `output/024-tekton-labs-cv.html`
- **Cover Letter:** `output/024-tekton-labs-cover-letter.md`
- **Report:** `reports/024-tekton-labs-2026-04-07.md`
- **Link aplicar:** https://tekton-labs.breezy.hr/p/84eb21d97c3a-delivery-manager-all-latam/apply
- **Framing CV:** Eagle Eye como operación de service delivery, Karpowership como delivery multi-stakeholder, background técnico como ventaja para entender engineering teams
- **Comp estimada:** $3,000-5,000/month (dentro de rango)

### Tether — Technical Project Manager (3.9/5)
- **CV PDF:** `output/021-tether-cv.pdf` (2pp, 57.6 KB)
- **CV HTML:** `output/021-tether-cv.html`
- **Cover Letter:** `output/021-tether-cover-letter.md`
- **Report:** `reports/021-tether-2026-04-07.md`
- **Link aplicar:** https://careers.tether.io/o/technical-project-manager-100-remote-worldwide
- **Framing CV:** Technical PM bridging engineering y negocio, PULSE con payment API para relevancia fintech
- **Comp estimada:** $54K-117K/yr ($4,500-9,750/month)

### Paymentology — Implementation PM (3.9/5)
- **CV PDF:** `output/030-paymentology-cv.pdf` (2pp, 56.5 KB)
- **CV HTML:** `output/030-paymentology-cv.html`
- **Cover Letter:** `output/030-paymentology-cover-letter.md`
- **Report:** `reports/030-paymentology-2026-04-07.md`
- **Link aplicar:** Verificar si posting sigue activo (originalmente 2022)
- **Framing CV:** Implementation PM con experiencia en pagos, PULSE + PayPhone API, Karpowership como "contract to go-live"
- **Comp estimada:** ~$3K-5K/month (estimación)

---

## Estado Actual / Pendientes

### Archivos del Sistema
| Archivo | Estado |
|---------|--------|
| `cv.md` | ✅ Creado |
| `config/profile.yml` | ✅ Creado (con filtro remote hard) |
| `modes/_profile.md` | ✅ Creado (archetypes, framing, negotiation) |
| `modes/_shared.md` | ✅ Actualizado (nuevos archetypes) |
| `portals.yml` | ✅ Creado (title filter customizado) |
| `data/applications.md` | ✅ Creado (tiene ~25 entries evaluadas) |
| `data/pipeline.md` | ✅ Creado (103 + 24 = ~127 URLs, mayoría sin evaluar) |
| `data/scan-history.tsv` | ✅ Creado (~170+ URLs registradas) |

### Git
- **Branch:** `claude/review-docs-config-lDh47`
- **Remote:** Pushed y up-to-date
- **Playwright:** Instalado (package.json actualizado, committed)

### Batch B (Reports 006-011)
- Agente fue lanzado (Contentful, RunPod, Rula, Lavendo, Scale Army, Mango Languages) pero los reports no aparecen en el directorio `reports/`. **Pendiente verificar si completó o re-ejecutar.**

---

## Action Items Abiertos

### Inmediatos (hacer ahora)
1. [ ] **Aplicar a Tekton Labs** — Abrir link, subir `024-tekton-labs-cv.pdf`, copiar cover letter, submit
2. [ ] **Aplicar a Tether** — Abrir link, subir `021-tether-cv.pdf`, copiar cover letter, submit
3. [ ] **Verificar Paymentology** — Confirmar si el posting sigue activo antes de aplicar

### Corto plazo
4. [ ] **Contactar Devsu directo** — Score 4.1/5 pero posting cerrado. Empresa ecuatoriana, excelente fit. Buscar su página de careers o contactar recruiting
5. [ ] **Re-ejecutar Batch B** (reports 006-011) — Rula (Remote), Lavendo (Remote), Scale Army, RunPod, Contentful, Mango Languages. Algunos tenían señal de remote real
6. [ ] **Kraken (3.7/5)** — Aplicación aspiracional. Comp $96K-192K/yr pero requiere automation engineering skills. Decidir si vale la pena el stretch
7. [ ] **Revisar cover letters** — El usuario no los revisó aún. Leer y ajustar antes de enviar

### Sistema / Mejoras
8. [ ] **Pipeline restante** — ~100+ ofertas del scan 1 sin evaluar. Mayoría probablemente no son remote. Considerar limpiar el pipeline eliminando ofertas obviamente on-site
9. [ ] **Configurar scan recurrente** — El sistema soporta scans automáticos. Considerar "scan every 3 days" para remote TPM/PM roles
10. [ ] **LinkedIn optimization** — Los reportes sugieren cambios al headline y skills de LinkedIn para cada archetype
11. [ ] **Verificar ofertas condicionales** — Arize AI (3.2), Airtable (3.5), Aledade (3.6) dicen "remote" pero podrían ser US-only. Verificar elegibilidad internacional

---

## Lecciones Aprendidas

1. **Filtrar por remote ANTES de evaluar** — El primer scan perdió tiempo evaluando 14 ofertas, 9 de las cuales eran on-site. El filtro de ubicación debe ser el primer gate.
2. **"Remote" no siempre significa worldwide** — Muchas ofertas US/EU dicen "remote" pero significan "remote dentro de nuestro país". Verificar siempre.
3. **LATAM consulting firms son el sweet spot** — Tekton Labs (4.3) y Devsu (4.1) resultaron los mejores matches. Empresas que operan nearshore consulting en LATAM valoran exactamente lo que Rafael ofrece.
4. **Greenhouse API es el método más eficiente** — Devuelve JSON estructurado con todos los listings. Ashby y Lever requieren Playwright o WebSearch.
