# Plan de arranque — Empresa de volteos y movimiento de tierras (República Dominicana)

Punto de partida: **2 camiones volteo de 19 m³**, posible sociedad con amigos.

> Los datos legales y de trámites son orientativos. Confírmalos con un abogado y un contador dominicanos antes de firmar o registrar nada.

---

## 1. Nombres comerciales

Criterios: fácil de decir por teléfono, que suene a obra y a cumplimiento, que se lea bien rotulado en la puerta de un camión y que pueda crecer (de 2 camiones a flota, y de transporte a movimiento de tierras).

| # | Nombre | Por qué funciona |
|---|--------|------------------|
| 1 | **Tierra Firme** Transporte SRL | Transmite solidez y cumplimiento. Sirve para volteos y para movimiento de tierras. *(Usado como ejemplo en la web.)* |
| 2 | **Volteo Seguro** RD | Dice exactamente lo que vendes. Muy buscable en Google y Facebook ("volteo" es la palabra que usa el cliente). |
| 3 | **Grupo Cimiento** | Suena a empresa grande; deja espacio para crecer a constructora. |
| 4 | **MueveTierra** Dominicana | Directo, moderno, buen dominio web. |
| 5 | **Caliche & Arena** Transporte | Usa los materiales que más vas a mover; muy local. |
| 6 | **Quisqueya Volteos** | Identidad nacional, fácil de recordar. |
| 7 | **Ruta Firme** Logística de Obra | Pone el foco en la puntualidad. |
| 8 | **Bloque Duro** Transporte | Coloquial y con fuerza; bueno para redes sociales. |
| 9 | **Terranova** Movimiento de Tierras | Elegante, sirve para proyectos inmobiliarios y turísticos. |
| 10 | **Doble Eje** Volteos | Término del oficio; recuerda que son camiones pesados. |
| 11 | **Agregados Express** RD | Si te enfocas en entregar arena/grava rápido a ferreterías y obras. |
| 12 | **TransObra** Caribe | Corto, sirve si luego trabajas fuera de la zona metropolitana. |

**Mis 3 favoritos:** Tierra Firme, Volteo Seguro y Grupo Cimiento.

Antes de enamorarse de uno:
1. Búsqueda de disponibilidad en **ONAPI** (Oficina Nacional de la Propiedad Industrial) y registro del nombre comercial.
2. Revisar que el dominio `.com.do` (NIC.DO) o `.com` y los usuarios de Instagram/Facebook estén libres.
3. Probarlo por teléfono: "Buenas, Tierra Firme" — si hay que deletrearlo, descártalo.

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
- Nombre, correo, zonas y textos de ejemplo del formulario.
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
| **1–2** | Elegir nombre y verificar en ONAPI. Firmar acuerdo de socios. Constituir la empresa. Abrir cuenta bancaria empresarial. Contratar o confirmar choferes. Revisar seguro, marbete, licencias, mantenimiento. |
| **3–4** | Rotular camiones. WhatsApp Business, Google Business Profile, Instagram/Facebook. Publicar la web. Imprimir tarjetas y conduces numerados. Lista de 50 prospectos (obras, ferreterías, retro, minas). |
| **5–8** | Ruta de obras 2 veces por semana. Visitar 20 ferreterías/depósitos. Cerrar 2 alianzas con operadores de retro. Lanzar programa de referidos. Primeras reseñas en Google. |
| **9–12** | Medir indicadores. Ajustar precios por zona. Buscar 1 contrato por obra (camión asignado). Evaluar anuncios pagados. Preparar documentación para Registro de Proveedores del Estado. |

Meta al día 90: los dos camiones con **al menos 20 días trabajados al mes** y **un cliente de contrato** que garantice la base de ingresos.

---

## 5. La sociedad con amigos

### 5.1 Forma jurídica
- **SRL (Sociedad de Responsabilidad Limitada)**, Ley 479-08 de Sociedades Comerciales: la más usada para pymes. Mínimo 2 socios; cada socio responde solo hasta su aporte. Verificar con el abogado el capital social mínimo vigente.
- Si al final vas solo: **EIRL** (Empresa Individual de Responsabilidad Limitada), para separar tu patrimonio personal del negocio.

**Trámites típicos:** nombre comercial en ONAPI → estatutos y constitución → registro mercantil en la Cámara de Comercio y Producción de tu provincia → RNC en la DGII → registro de empleadores en la TSS (choferes en nómina) → cuenta bancaria → licencias de vehículo pesado de los choferes, seguro de ley y marbete al día en el INTRANT/DGII.

### 5.2 Acuerdo de socios (por escrito, antes de mover un solo viaje)
1. **Aportes**: quién pone qué. Si un socio aporta un camión, hay que tasarlo y decidir si pasa a nombre de la empresa (recomendado) o si la empresa se lo alquila.
2. **Porcentajes** de participación según el valor de los aportes.
3. **Roles y sueldos**: quien trabaje a diario (ventas, despacho, cobros) cobra un sueldo aparte de las utilidades. Separar "socio inversionista" de "socio operador".
4. **Reparto de utilidades**: primero un **fondo de mantenimiento y reposición** (por ejemplo un % fijo de lo facturado), después reparto.
5. **Decisiones**: qué se decide por mayoría y qué requiere unanimidad (comprar o vender camiones, endeudarse, entrar socios nuevos).
6. **Salida de un socio**: derecho de preferencia de los demás para comprar sus cuotas, fórmula de valoración y plazo de pago.
7. **Desempate** cuando hay 50/50: mediador o un tercer voto acordado.
8. **Prohibiciones**: no usar los camiones para trabajos personales, no competir con la empresa.
9. **Fallecimiento o incapacidad** de un socio.
10. **Reportes**: estado de cuenta mensual a todos los socios, cuenta bancaria con doble firma para montos grandes.

### 5.3 Reglas de convivencia
- Todo el dinero pasa por la cuenta de la empresa; nada en efectivo "por fuera".
- Reunión mensual con números: viajes, ingresos, gastos, cuentas por cobrar.
- Un solo responsable de despacho y uno de cobros, para que los clientes no reciban precios distintos.

---

## 6. Próximos pasos inmediatos
1. Elegir 3 nombres y verificar disponibilidad en ONAPI.
2. Reunión con los socios para definir aportes y roles, con este documento como guía.
3. Cita con abogado (constitución + acuerdo de socios) y contador (RNC, NCF, nómina).
4. Llamar a 5–8 competidores para conocer precios.
5. Reemplazar datos de ejemplo en la web y publicarla.
