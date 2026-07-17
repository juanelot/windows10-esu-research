# Windows 10 ESU (Extended Security Updates) — Investigación Completa

**Fecha**: Julio 2026
**Contexto**: Usuario salvadoreño, Lenovo desktop vieja (i5-3570, 4GB RAM, Windows 7 actualmente)
**Fin de soporte Windows 10**: 14 de octubre de 2025

---

## 1) ¿Hay un programa de $30/año para consumidores?

**SÍ** — Microsoft anunció un programa ESU para consumidores:

- **Precio**: **$31 USD** (un solo pago) por **1 año** de actualizaciones de seguridad
- **Opción gratuita**: Es **GRATIS** si inicias sesión con una cuenta Microsoft y activas la sincronización de configuración en la nube
- **Microsoft Rewards**: También se puede canjear por 1,000 puntos
- **Válido para**: Windows 10 Home, Pro, Pro Education y Workstation
- **Solo 1 año**: El programa de consumidores es estrictamente por **1 año** (octubre 2025 - octubre 2026)

**Fuentes**:
- Microsoft Support: Windows 10 Consumer ESU Program
- Ars Technica (Oct 2024): "Home users can only buy one year of extra Windows 10 updates for $30 per PC"

---

## 2) ¿Cuántos años de extensión hay disponibles?

| Edición | Duración | Costo |
|---------|----------|-------|
| Home / Pro (Consumidor) | 1 año (Oct 2025 - Oct 2026) | Gratis (con cuenta MS) o $31 |
| Pro / Enterprise (Comercial) | 3 años (Oct 2025 - Oct 2028) | Año 1: $61, Año 2: $122, Año 3: $244/disp. |
| Education | 3 años | Precios académicos |
| IoT Enterprise LTSC 2021 | Hasta 2032 | Sin costo (licencia diferente) |

**Importante**: El programa de consumidores es SOLO por 1 año. No hay opción de renovar.

---

## 3) ¿Cómo se activa?

### Método gratuito:
1. **Settings → Accounts → Your Info** → Iniciar sesión con cuenta Microsoft
2. **Settings → Accounts → Sync your settings** → Activar "Sync settings"
3. Después del 14 de octubre 2025, abrir **Windows Update**
4. Buscar "Extended Security Updates" y aceptar términos
5. Las actualizaciones ESU aparecerán automáticamente

### Método de pago ($31):
1. Después del 14 de octubre 2025, Windows Update mostrará opción de compra ESU
2. Completar pago mediante cuenta Microsoft

---

## 4) Formas gratuitas / extensiones no oficiales

### ✅ Oficial: Windows 10 IoT Enterprise LTSC 2021
- **Actualizaciones hasta**: Enero 2032 (¡7 años extra!)
- Se puede convertir desde Windows 10 Home/Pro existente sin formatear
- Usar clave `QPM6N-7J2WJ-P88HH-P3YRH-YY74H`
- Las ediciones IoT son "binary identical" a Enterprise — solo cambia el licenciamiento

### ✅ MAS (Microsoft Activation Scripts) — TSforge
- Activa 3 años completos de ESU comercial en cualquier edición
- Web: massgrave.dev

### ✅ 0patch (Terceros)
- Micro-parches de seguridad, ~$30/año
- Independiente de Microsoft, cubre hasta Windows 7

---

## 5) ¿Funciona en equipos viejos sin TPM?

**Windows 10 ESU**: ✅ **SÍ** — Windows 10 no requiere TPM 2.0. ESU es solo una suscripción de actualizaciones, no añade requisitos.

**Windows 10 IoT LTSC 2021**: ✅ Mismos requisitos que Windows 10 normal.

**Windows 11**: El i5-3570 NO es oficialmente compatible (requiere 8th gen+), pero:
- Windows 11 IoT Enterprise 24H2 **tiene requisitos relajados** oficialmente (TPM 2.0 es "opcional")
- El i5-3570 soporta SSE4.2/POPCNT que son los requisitos reales de Win11 24H2
- **Problema**: 4GB RAM es muy poco para Windows 11

---

## Recomendación para el usuario

**Opción recomendada — La más simple**:
1. Actualizar de Windows 7 a Windows 10 (usa la licencia de Win7, aún funciona)
2. Iniciar sesión con cuenta Microsoft → Activar sync → ESU gratuito por 1 año
3. Usar ese año para planificar migración o actualizar hardware

**Opción máxima duración (Gratis)**:
1. Actualizar a Windows 10
2. Convertir a **Windows 10 IoT Enterprise LTSC 2021** → actualizaciones hasta 2032
3. Sin TPM requerido, funciona en cualquier PC compatible con Windows 10

**Consideraciones**:
- 4GB RAM es muy justo para Windows 10. Considera actualizar a 8GB (DDR3 es barato)
- Sin ESU o LTSC, Windows 10 sin soporte después de octubre 2026 es riesgoso
- Alternativa a considerar: Linux (Mint o Zorin) si el rendimiento es prioridad
