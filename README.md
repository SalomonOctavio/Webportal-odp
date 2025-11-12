# Portal de Ofertas de Datos (WebPortal/ODP) — TELCO

Autoservicio para **consultar consumo/saldo** y **suscribir ofertas de datos** (prepago/pospago), con **notificaciones** y redirecciones contextuales (cuota=0, saldo insuficiente, roaming). Integración con CRM/BSCS/ALU y políticas en PCRF vía bus.

## Objetivo
Disponibilizar en línea las ofertas comerciales y asegurar la correcta activación/desactivación por segmento y método de pago, con mínima fricción en la experiencia.

## Enfoque
- Clientes: **WebPortal** (web/wap) y **ODP** (app).
- Funciones: saldo, consumo diario, paquetes activos, (de)suscripción, notificaciones.
- Integraciones: **UCM/UOM** ↔ **OSB/Middleware** ↔ **BSCS/ALU/PCRF**.

## Artefactos
📁 `/diagrams`  
- `arquitectura-webportal-odp.mmd` — contexto e integraciones.  
- `flujo-suscripcion.mmd` — suscripción por segmento/pago.

📁 `/docs`  
- `kpis.md` — TTGL/TTV y métricas de adopción (placeholders).  
- `catalogo-ofertas.md` — estructura y parámetros de oferta (máscara).  
- `uat-casos.md` — matriz de pruebas por categoría (login, saldo, suscripción, notificaciones).

📁 `/uat`  
- `plan-uat.md` — alcance, precondiciones y participantes.  
- `checklist-go-no-go.md` — criterios mínimos de liberación.

## Nota
Repo **anonimizado**: sin adjuntar documentos de proveedor ni credenciales. Se preserva el enfoque funcional.
