# Plan de arranque — PLG Volteos y Movimiento de Tierras

Empresa: **Palacios Logistic Group SRL** (consultoría y transporte). Nueva división: **2 camiones volteo de 19 m³**, con posible sociedad futura para construcción.

> Los datos legales y de trámites son orientativos. Confírmalos con un abogado y un contador dominicanos antes de firmar o registrar nada.

---

## 1. Identidad: Palacios Logistic Group SRL (PLG)

La empresa ya existe y está registrada como **Palacios Logistic Group SRL** (consultoría y transporte). Los volteos y el movimiento de tierras arrancan como una **división** de PLG, no como empresa nueva (ver sección 5).

| Dónde | Cómo se presenta |
|---|---|
| Facturas, contratos, licitaciones | Palacios Logistic Group SRL |
| Camiones, redes sociales, tarjetas | **PLG Volteos** + "19 m³ · WhatsApp 809-XXX-XXXX" |
| Google Business / WhatsApp Business | Palacios Logistic Group – Volteos y Movimiento de Tierras |
| Dominio web | `palacioslogistic.com.do` o `plg.com.do` (verificar en NIC.DO) |

**Lema fijo junto al nombre:** *Volteos y Movimiento de Tierras*. "Logistic" por sí solo hace pensar en almacenes o mensajería; el lema le dice al cliente de construcción qué haces.

Pendiente: revisar con el abogado que el **objeto social** de PLG incluya movimiento de tierras, alquiler de equipos y construcción; si no, ampliarlo por asamblea y registrarlo en la Cámara de Comercio.

---

## 2. Página web

Archivo listo: [`web/index.html`](../web/index.html) — una sola página, sin dependencias, funciona en celular.

**Estructura**
1. **Encabezado fijo** con logo y botón "Cotizar" (WhatsApp).
2. **Portada** con mensaje principal y una **calculadora de viajes**: el cliente pone largo × ancho × espesor (o los m³), elige el material y ve cuántos viajes de 19 m³ necesita, incluido el esponjamiento (relleno ×1.30, escombros ×1.45, tierra de excavación ×1.25, arena/grava ×1.00). El botón envía ese cálculo por WhatsApp. Esto es lo que diferencia la web de la competencia.
3. **Franja de datos**: 19 m³ por viaje, 38 m³ por ronda, horario, factura con NCF.
4. **Servicios**: arena y grava, caliche y relleno, bote de escombros, bote de tierra, volteo + equipo (con aliados), contratos por día/obra.
5. **Cómo trabajamos**: Cotiza → Confirma → Despacho → Entrega con conduce firmado y factura.
6. **Flota**: ficha de cada camión (agregar fotos reales cuando estén rotulados).
7. **Para quién** y **zonas de servicio**.
8. **Contacto**: formulario que arma el mensaje de WhatsApp + botón flotante de WhatsApp.

**Antes de publicarla, cambiar:**
- El número `18090000000` en el script y los enlaces `wa.me` por el WhatsApp real.
- RNC real en el pie de página, correo, zonas y textos de ejemplo del formulario.
- Agregar fotos reales de los camiones cargando y descargando (son lo que más vende).

**Publicación (costo casi cero)**
- Hosting gratis: GitHub Pages o Netlify (subir la carpeta `web/`).
- Dominio: `.com.do` en NIC.DO o `.com` en cualquier registrador.
- Conectar **Google Business Profile** y poner el enlace de la web en el perfil de WhatsApp Business e Instagram.

---

## 3. Estrategia para conseguir clientes

### 3.1 A quién venderle (en orden de prioridad)

| Segmento | Por qué | Cómo llegar |
|---|---|---|
| **Ingenieros residentes y maestros de obra** | Deciden a quién llaman el día del vaciado. Volumen constante. | Visita en obra, tarjeta + WhatsApp, comisión por referido. |
| **Ferreterías y depósitos de materiales** | Venden arena/grava pero muchos no tienen camión propio o les falta capacidad. | Acuerdo de "transportista preferido" con precio por zona. |
| **Constructoras pequeñas y medianas** | Contratos por obra = ingreso estable para 1 camión. | Propuesta formal, registro como suplidor, crédito controlado. |
| **Contratistas de retroexcavadora/pala** | Siempre necesitan volteos para el bote de tierra. | Alianza: ellos te traen el trabajo, tú los recomiendas a ellos. |
| **Minas y graveras** | Buscan transportistas para despachar a sus clientes. | Visitar al encargado de despacho; quedar en su lista. |
| **Particulares (relleno de solares)** | Pagan de contado y bien. Llegan por Facebook/Marketplace y Google. | Anuncios locales y Marketplace. |
| **Estado y ayuntamientos** (fase 2) | Contratos grandes pero con pagos lentos. | Registro de Proveedores del Estado (DGCP) cuando la empresa tenga RNC y estados financieros. |

### 3.2 Canales

**Gratis o casi gratis (primer mes)**
- **Rotular los dos camiones**: nombre, "Volteos 19 m³", WhatsApp en grande. Es la publicidad más barata y la que más funciona en este negocio.
- **WhatsApp Business**: catálogo con cada material/servicio, respuestas rápidas, etiquetas (nuevo, cotizado, cliente, moroso), estados diarios con fotos de entregas.
- **Google Business Profile**: categoría "Servicio de transporte de materiales / Contratista de movimiento de tierras", fotos, horario; pedir reseña a cada cliente satisfecho.
- **Facebook Marketplace y grupos** de construcción de tu zona; publicar 3–4 veces por semana.
- **Corotos** (clasificados dominicanos): anuncio fijo de servicio.
- **Tarjetas y volantes** en ferreterías, depósitos y obras activas.

**Venta directa (lo que más cierra)**
- **Ruta de obras**: 2 mañanas por semana, recorrer zonas en construcción, hablar con el residente, dejar tarjeta y ofrecer el **primer viaje con descuento**.
- **Programa de referidos**: pagar una comisión fija por cada viaje que traiga un maestro de obra, chofer o vendedor de ferretería. Se paga cuando el cliente paga.
- **Alianzas con 2–3 operadores de retro/pala**: paquetes "excavación + bote" con un solo precio.

**Pagado (cuando el flujo de caja lo permita)**
- Anuncios de Facebook/Instagram segmentados por zona (radio 15–20 km), objetivo "mensajes de WhatsApp", presupuesto pequeño y diario.
- Google Ads con búsquedas como "volteo de arena", "bote de escombros", "relleno para solar" + tu zona.

**Contenido que funciona** (reels/estados de 15–30 s): camión descargando, antes/después de un solar rellenado, timelapse de una jornada, "¿cuántos viajes necesita un solar de 200 m²?".

### 3.3 Precios y cobro

- Cotizar **por viaje según distancia** (zonas por anillos desde la base) o **por m³** en contratos grandes. **Por día** cuando el camión queda asignado a una obra.
- Antes de fijar precios: llamar como cliente a 5–8 competidores de tu zona y anotar precio por viaje, material incluido o no, y tiempo de respuesta.
- Fórmula mínima por viaje:
  `precio ≥ (combustible + chofer + peajes + desgaste de gomas + mantenimiento + seguro y marbete prorrateados + depreciación) ÷ viajes del mes + margen`
- **Política de crédito** (el problema número uno de este negocio): clientes nuevos pagan por adelantado o contra entrega; crédito de 15 días máximo solo a clientes con historial; tope de deuda por cliente; no despachar a quien tenga facturas vencidas.
- Factura siempre con **NCF**: las constructoras exigen comprobante con crédito fiscal.

### 3.4 Operación que fideliza
- Llegar a la hora prometida y avisar si hay atraso.
- **Conduce firmado** en cada viaje y foto de la carga por WhatsApp.
- Reporte semanal a clientes de contrato: viajes, m³, saldo.
- Choferes uniformados, camión limpio, carga cubierta con lona.

### 3.5 Indicadores semanales
- Viajes por camión por día (meta inicial: 4–6 en zona metropolitana, según distancia).
- Días trabajados por camión al mes (meta: 22+).
- Kilómetros en vacío (bajarlos combinando entregas con regresos cargados).
- Costo de combustible por viaje.
- Cuentas por cobrar con más de 15 días.
- Clientes nuevos y clientes que repiten.

---

## 4. Plan de 90 días

| Semana | Acciones |
|---|---|
| **1–2** | Ampliar objeto social de PLG si hace falta. Centro de costos de volteos en la contabilidad. Contratar o confirmar choferes. Revisar seguro, marbete, licencias, mantenimiento. |
| **3–4** | Rotular camiones. WhatsApp Business, Google Business Profile, Instagram/Facebook. Publicar la web. Imprimir tarjetas y conduces numerados. Lista de 50 prospectos (obras, ferreterías, retro, minas). |
| **5–8** | Ruta de obras 2 veces por semana. Visitar 20 ferreterías/depósitos. Cerrar 2 alianzas con operadores de retro. Lanzar programa de referidos. Primeras reseñas en Google. |
| **9–12** | Medir indicadores. Ajustar precios por zona. Buscar 1 contrato por obra (camión asignado). Evaluar anuncios pagados. Preparar documentación para Registro de Proveedores del Estado. |

Meta al día 90: los dos camiones con **al menos 20 días trabajados al mes** y **un cliente de contrato** que garantice la base de ingresos.

---

## 5. Estructura de empresas y socios

### 5.1 Fase 1 — ahora: todo dentro de PLG
- Los dos volteos operan bajo Palacios Logistic Group SRL.
- Se aprovecha el historial de PLG (RNC, antigüedad, estados financieros) para constructoras, minas y el Registro de Proveedores del Estado.
- Una sola contabilidad, una sola declaración en la DGII y una sola TSS.
- Llevar los volteos como **centro de costos separado** en la contabilidad, para saber si la división gana dinero por sí sola.

### 5.2 Fase 2 — nueva SRL cuando entren socios o empiecen contratos de construcción
```
Palacios Logistic Group SRL (tuya)
  ├─ Dueña de camiones y equipos
  ├─ Consultoría y transporte
  └─ Alquila camiones y equipos ──►  PLG Construcciones SRL (nueva)
                                       Socios: tú y/o PLG + amigos
                                       Contratos de obra y movimiento de tierras
```
- Los socios entran **solo en la nueva empresa**, nunca en PLG.
- Los equipos quedan en PLG: si la constructora enfrenta un reclamo, los camiones no son de ella.
- El alquiler entre ambas empresas va por contrato escrito y a precio de mercado (la DGII revisa operaciones entre relacionadas).

### 5.3 Acuerdo de socios de la nueva SRL (por escrito, antes de operar)
1. **Aportes** y su valoración (efectivo, equipos, clientes).
2. **Porcentajes** de participación.
3. **Roles y sueldos**: el socio que opera a diario cobra sueldo aparte de las utilidades.
4. **Utilidades**: primero un fondo de mantenimiento y reposición, después reparto.
5. **Decisiones** por mayoría vs. unanimidad (comprar equipos, endeudarse, socios nuevos).
6. **Salida de un socio**: derecho de preferencia, fórmula de valoración y plazo de pago.
7. **Desempate** en sociedades 50/50.
8. **No competencia** y prohibición de uso personal de los equipos.
9. **Uso del nombre y la marca PLG**: pertenece a Palacios Logistic Group; la nueva empresa la usa con licencia y la pierde si tú sales.
10. **Fallecimiento o incapacidad** de un socio; reportes mensuales y doble firma bancaria.

---

## 6. Próximos pasos inmediatos
1. Abogado: confirmar o ampliar el objeto social de PLG (movimiento de tierras, alquiler de equipos, construcción).
2. Contador: abrir centro de costos de la división de volteos; NCF y nómina de choferes.
3. Registrar el dominio y crear los perfiles de PLG Volteos (Google, WhatsApp Business, Instagram, Facebook).
4. Llamar a 5–8 competidores para conocer precios.
5. Reemplazar datos de ejemplo en la web y publicarla.
