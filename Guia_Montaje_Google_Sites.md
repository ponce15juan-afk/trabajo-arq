# Guía de Montaje para Google Sites: Arquitectura de Computadoras

> **Nota:** Este documento reúne todos los textos, tablas, estructura de bloques y elementos visuales listos para copiar y pegar directamente en **Google Sites**, respetando estrictamente los datos del documento original `Trabajo arq.docx` y las fuentes oficiales actualizadas, sin inventar especificaciones ni precios.

---

## Índice de Páginas en Google Sites

En el panel lateral derecho de Google Sites (`Páginas > + Añadir página`), crea exactamente estas 5 páginas:
1. **Inicio**
2. **Punto 1: CPU, GPU y NPU**
3. **Punto 2: Almacenamiento**
4. **Punto 3: Workstation de IA**
5. **Bibliografía y Recursos**

---

## 1. Página: Inicio

### Bloque 1: Banner Principal (Encabezado tipo Portada o Encabezado grande)
- **Título principal:**
  > Arquitectura de Computadoras: el corazón inteligente de la máquina
- **Subtítulo:**
  > Proyecto Educativo · Carrera de Inteligencia Artificial y Ciencia de Datos · Materia IACO 2026

### Bloque 2: Texto de Presentación (Cuadro de texto)
> Este sitio web educativo reúne el desarrollo completo del proyecto grupal de la materia IACO 2026, a cargo del profesor Emmanuel Galiotti. Su objetivo es explicar de manera clara, rigurosa y accesible cómo la arquitectura de hardware moderna —desde el paralelismo masivo de GPUs y la eficiencia de NPUs hasta las velocidades de bus PCIe 5.0— fundamenta y condiciona las soluciones de Inteligencia Artificial y Ciencia de Datos.

### Bloque 3: Tarjetas de Navegación a las 3 Secciones (Diseño de 3 columnas de Google Sites)

| Columna 1 | Columna 2 | Columna 3 |
| :--- | :--- | :--- |
| **Punto 1: CPU, GPU y NPU** | **Punto 2: Almacenamiento** | **Punto 3: Workstation de IA** |
| Especialización de cada unidad, comparación Panther Lake vs Ryzen AI, esquema funcional y caso de la RTX 5090 Blackwell. | SATA vs NVMe, analogía de la carretera, gráfico logarítmico de velocidades y tecnologías emergentes (PCIe 5.0, DirectStorage, fotónica y ADN). | Perfil profesional (Artista de IA), configuración extrema "Money is No Object" y armado "El Punto Dulce" por menos de USD 800 (USD 797,40). |
| *[Botón: Explorar Punto 1]* | *[Botón: Explorar Punto 2]* | *[Botón: Explorar Punto 3]* |

### Bloque 4: Aviso Académico y Portada
> **Nota para la entrega final:** Para la portada del PDF que acompaña el enlace público de este sitio, recuerden incorporar los nombres completos de todos los integrantes del grupo de trabajo.

---

## 2. Página: Punto 1: CPU, GPU y NPU

### Bloque 1: Encabezado
- **Título:** Punto 1 — El corazón inteligente de la máquina: CPU, GPU y NPU
- **Texto breve:**
  > El rendimiento de una computadora para inteligencia artificial depende del tipo de tarea. La CPU coordina el sistema y resuelve tareas generales. La GPU está preparada para ejecutar muchas operaciones en paralelo y es clave para entrenar o generar contenido con modelos grandes. La NPU acelera ciertas tareas de IA compatibles con un consumo menor, por ejemplo, funciones que se ejecutan de manera continua en una laptop.

### Bloque 2: Tres tarjetas de funciones clave (Diseño de 3 columnas)
- **CPU:** Coordina el sistema, organiza el flujo de ejecución, prepara datos y resuelve tareas generales monohilo o secuenciales.
- **GPU:** Alto paralelismo con miles de núcleos para entrenamiento, ajuste e inferencia matricial de modelos pesados de IA.
- **NPU:** Aceleración dedicada para inferencias compatibles con consumo eléctrico sostenido reducido.

### Bloque 3: Tabla comparativa de procesadores
*(Insertar como tabla o bloque de texto formateado)*

| Característica | Intel Core Ultra X9 388H | AMD Ryzen AI 9 HX 470 |
| :--- | :--- | :--- |
| **Arquitectura** | Panther Lake; diseño híbrido con 16 núcleos: 4 P-cores, 8 E-cores y 4 LP E-cores. | Ryzen AI 400 Series; 12 núcleos Zen: 4 Zen 5 y 8 Zen 5c. |
| **Núcleos e hilos** | 16 núcleos / 16 hilos. | 12 núcleos / 24 hilos. |
| **Frecuencia máxima**| Hasta 5,1 GHz. | Hasta 5,2 GHz. |
| **Caché** | 18 MB de Intel Smart Cache. | 12 MB de caché L2 y 24 MB de caché L3. |
| **NPU** | Intel AI Boost; hasta 50 TOPS de rendimiento de IA según especificaciones del fabricante [1]. | AMD XDNA 2; hasta 55 TOPS de rendimiento de IA según especificaciones del fabricante [2, 3]. |
| **Gráficos integrados** | Intel Arc B390. | AMD Radeon 890M. |

### Bloque 4: Explicación de conceptos y glosario
> - **P-cores (Performance cores):** Se enfocan en tareas que requieren más rendimiento por núcleo.
> - **E-cores (Efficient cores):** Realizan tareas de fondo con mayor eficiencia.
> - **LP E-cores (Low Power Efficient cores):** Apuntan a tareas livianas de muy bajo consumo.
> - **Zen 5 y Zen 5c:** Tipos de núcleo de la misma familia arquitectónica; Zen 5c prioriza la densidad y eficiencia.
> - **Núcleos e hilos:** Los núcleos procesan tareas en paralelo físico; los hilos ayudan a organizar y alternar varias tareas dentro de esos núcleos.
> - **Memoria Caché:** Memoria pequeña y ultrarrápida donde se guardan temporalmente datos frecuentes para evitar accesos lentos a la memoria RAM.
> - **Aclaración sobre TOPS:** Los TOPS anunciados por los fabricantes (50 vs 55 TOPS) no corresponden a una misma prueba estandarizada; cambian la precisión matemática, el tipo de operación matricial y las condiciones de medición [1–3].

### Bloque 5: Esquema de arquitectura y reparto de trabajo
- **Imagen 1 (Esquema funcional de procesadores):** Subir el gráfico generado con los bloques de Intel y AMD.
  - *Pie de foto:* Esquema simplificado de los bloques principales según fichas oficiales de fabricante [1–3]. No representa un plano físico del chip.
- **Imagen 2 (Cómo se reparten el trabajo):** Subir el diagrama de bloques CPU ↔ GPU ↔ NPU.
  - *Pie de foto:* Esquema conceptual del flujo de trabajo: la CPU organiza; la GPU entrena e infiere modelos paralelos; la NPU atiende inferencias continuas y eficientes. La NPU no sustituye a la GPU en entrenamiento masivo.

### Bloque 6: NPU y Caso Real Windows Studio Effects
> **¿Qué hace especial a la NPU y cuáles son sus límites?**
> Una NPU (Neural Processing Unit) acelera operaciones frecuentes en redes neuronales, sobre todo **inferencia**: cuando el modelo previamente entrenado procesa entradas y produce una respuesta. Permite ejecutar tareas locales de forma sostenida dejando CPU y GPU libres. La ventaja real de consumo depende del chip, del modelo y del software; no se deduce sólo del número de TOPS.
>
> **Caso de uso real: Windows Studio Effects**
> Ofrece encuadre automático de cámara, contacto visual simulado, desenfoque de fondo y aislamiento de ruido en videollamadas. Microsoft indica que estas funciones requieren un **Copilot+ PC** con NPU de más de 40 TOPS [21]. Esto demuestra cómo la NPU sostiene inferencias interactivas constantes sin recalentar el equipo ni agotar la batería.

### Bloque 7: GPU de alto rendimiento: NVIDIA GeForce RTX 5090
> La RTX 5090 se basa en la arquitectura **Blackwell**, equipada con 21.760 núcleos CUDA y 32 GB de memoria GDDR7 [4]. Los núcleos CUDA ejecutan operaciones paralelas masivas; los Tensor Cores de 5ª generación aceleran el cómputo matricial con cuantización en menor precisión como **FP4**. La memoria de video (VRAM) es determinante porque delimita el tamaño máximo del modelo que puede cargarse localmente.

**Resultados informados por fabricantes:**

| Prueba publicada | Resultado informado | Qué permite concluir |
| :--- | :--- | :--- |
| **RTX 5090 · FLUX.1-dev, 30 pasos** | 3.853 ms; FP4, precisión mixta | Ejemplo concreto de inferencia de imagen; depende del flujo TensorRT/Model Optimizer. Dato de fabricante [6]. |
| **RTX 5090 · FLUX.1-schnell, 4 pasos** | 591 ms; FP4, precisión mixta | Modelo y cantidad de pasos distintos: no comparar directamente con FLUX.1-dev. Dato de fabricante [6]. |
| **Core Ultra X9 388H vs 9 386H · Llama 2 7B** | Hasta 2,2× en tiempo hasta primer token | Resultado MLPerf GPU/Windows ML publicado por Intel; equipos y modos de energía distintos [5]. |

> *Aclaración metodológica:* No se encontró una medición pública comparable que enfrente estas dos NPU con la RTX 5090 bajo las mismas condiciones. Por ello, la diferencia de eficiencia se presenta como una función intrínseca esperada de cada tipo de unidad, no como un porcentaje medido para estos modelos específicos.

### Bloque 8: Conclusión: ¿Qué unidad conviene según la tarea?

| Componente | Dónde aporta más | Ejemplo de uso |
| :--- | :--- | :--- |
| **CPU** | Coordina el sistema, prepara datos y ejecuta tareas generales. | Cargar el conjunto de datos y controlar el programa. |
| **GPU** | Operaciones paralelas exigentes; entrenamiento, ajuste fino e inferencia pesada. | Generar imágenes con Stable Diffusion o FLUX en una RTX. |
| **NPU** | Inferencia compatible que conviene ejecutar de forma local, continua y eficiente. | Efectos de videollamada, reducción de ruido o funciones de IA integradas en laptops. |

### Bloque 9: Galería de Aplicaciones Reales (3 aplicaciones documentadas)

1. **Generación de imágenes por difusión (FLUX / Stable Diffusion · GPU):**
   - *Epígrafe:* La GPU ejecuta el modelo de difusión en paralelo y genera imágenes localmente. En tarjetas con arquitectura Blackwell y TensorRT FP4 se alcanzan inferencias por debajo del segundo [6].
   - *Fuente:* [NVIDIA Developer Blog [6]](https://developer.nvidia.com/blog/nvidia-tensorrt-unlocks-fp4-image-generation-for-nvidia-blackwell-geforce-rtx-50-series-gpus/).
2. **Videollamadas asistidas por IA (Windows Studio Effects · NPU):**
   - *Epígrafe:* El panel de Windows Studio Effects permite encuadre automático, contacto visual y desenfoque ejecutado directamente en la NPU en equipos Copilot+ PC sin degradar el rendimiento del procesador ni la GPU [21].
   - *Fuente:* [Microsoft Support [21]](https://support.microsoft.com/en-us/windows/ai/ai-features/windows-studio-effects) y [Microsoft Learn](https://learn.microsoft.com/es-es/windows/apps/develop/windows-integration/windows-studio-effects).
3. **Edición y postproducción neural de video (DaVinci Resolve · GPU):**
   - *Epígrafe:* La GPU acelera el motor DaVinci Neural Engine para tareas intensivas como Magic Mask (aislamiento automático de personajes), reencuadre inteligente y reducción de ruido en tiempo real.
   - *Fuente:* [Blackmagic Design DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve).

---

## 3. Página: Punto 2: Almacenamiento

### Bloque 1: Encabezado
- **Título:** Punto 2 — La superautopista de los datos: Almacenamiento y velocidades
- **Texto:**
  > El almacenamiento conserva el sistema operativo, los programas, los modelos y los conjuntos de datos. Un acceso rápido reduce el tiempo de carga y transferencia. Sin embargo, el SSD no reemplaza la RAM ni la memoria de video: una vez que un modelo se usa, sus partes necesarias deben pasar a la memoria del sistema o de la GPU.

### Bloque 2: SATA vs NVMe y la Analogía de la Carretera
> - **SATA:** Es una interfaz de conexión heredada. SATA III alcanza alrededor de 6 Gb/s (~600 MB/s teóricos brutos), rindiendo unos 550 MB/s reales en lectura.
> - **NVMe:** Protocolo diseñado específicamente para unidades de estado sólido que operan a través del bus PCI Express (PCIe).
>
> **La analogía pedagógica de la carretera:**
> Se suele comparar a *SATA como una carretera de 2 carriles* y a *NVMe como una autopista de 8 carriles*. Esta comparación ayuda a conceptualizar el gran salto en ancho de banda, pero es fundamental aclarar que **no describe literalmente la cantidad de carriles físicos** de las unidades: los SSD M.2 NVMe de consumo habituales utilizan hasta 4 carriles PCIe (x4).

### Bloque 3: Tabla comparativa de velocidades declaradas

| Unidad comparada | Lectura secuencial | Escritura secuencial | Tipo de cifra |
| :--- | :--- | :--- | :--- |
| **HDD Seagate BarraCuda 3 TB** | 156 MB/s | 156 MB/s | Promedio indicado en la ficha consultada [9] |
| **SSD SATA Samsung 870 EVO 1 TB** | Hasta 560 MB/s | Hasta 530 MB/s | Máximos secuenciales del fabricante [10] |
| **SSD NVMe Samsung 9100 PRO PCIe 5.0 4 TB** | Hasta 14.800 MB/s | Hasta 13.400 MB/s | Máximos secuenciales del fabricante [11] |

### Bloque 4: Ejemplo práctico: Cargar un dataset de 100 GB (100.000 MB)
> Cálculo ideal dividiendo tamaño (100.000 MB) por velocidad de lectura secuencial:
> - **HDD Seagate BarraCuda (156 MB/s):** 10 minutos y 41 segundos (≈ 641 s).
> - **SSD SATA Samsung 870 EVO (560 MB/s):** 2 minutos y 59 segundos (≈ 179 s).
> - **SSD NVMe Samsung 9100 PRO (14.800 MB/s):** 7 segundos (≈ 6,76 s).
>
> *Nota:* Estimación puramente teórica en lectura continua. En la práctica, intervienen la fragmentación, cantidad de archivos pequeños, sistema de archivos, temperaturas y procesador.

### Bloque 5: Gráfico Comparativo en Escala Logarítmica
- **Imagen del Gráfico:** Insertar la imagen del gráfico de barras generado.
- **Pie y explicación del gráfico:**
  > **Figura:** Velocidades secuenciales declaradas en fichas de producto [9–11].
  > *Aclaración sobre la escala:* Se utiliza **escala logarítmica** en el eje vertical (10², 10³, 10⁴) para permitir la lectura proporcional de magnitudes tan dispares (desde 156 MB/s hasta 14.800 MB/s) sin que las barras de HDD queden invisibles.
  > *Rigor de datos:* Se distingue explícitamente que el valor del HDD (156 MB/s) es el promedio informado en ficha, mientras que los valores de los SSD Samsung son máximos secuenciales teóricos comunicados por el fabricante; no constituyen resultados de una misma prueba empírica.

### Bloque 6: Mirando al horizonte (Tecnologías emergentes)
- **PCIe 5.0:** Duplica la tasa de transferencia por carril frente a PCIe 4.0 (32 GT/s vs 16 GT/s), alcanzando tasas superiores a 14.000 MB/s [7, 11].
- **Microsoft DirectStorage:** API que agiliza la carga de datos desde el disco a la GPU sin sobrecargar la CPU. En IA podría beneficiar la carga de pesos en modelos diseñados para este flujo, aunque hoy no acelera automáticamente cualquier software [8].
- **Circuitos Fotónicos:** Empleo de fotones para resolver operaciones matriciales neuronales a velocidades altísimas con muy baja latencia. Existen prototipos de laboratorio (Nature Photonics), pero con retos en integración masiva [18, 19].
- **Cómputo y Almacenamiento en ADN:** Investigación sobre densidad molecular extrema para resguardo masivo. Es un campo incipiente que por sus tiempos de síntesis y lectura no reemplaza a un SSD doméstico [20].

### Bloque 7: Veredicto del almacenamiento

| Uso recomendado | Solución simple |
| :--- | :--- |
| **Archivado masivo y backups económicos** | HDD tradicional. |
| **Actualizar una PC antigua a bajo costo** | SSD SATA. |
| **Carga ágil de modelos de IA y grandes datasets** | SSD NVMe PCIe (si la PC cuenta con puerto compatible). |

---

## 4. Página: Punto 3: Workstation de IA

### Bloque 1: Perfil profesional elegido
> **Perfil:** Artista de IA generativa que crea imágenes y prueba modelos localmente. Requiere una GPU con suficiente memoria de video (VRAM), abundante memoria RAM para multitarea y almacenamiento veloz para modelos y proyectos.

### Bloque 2: Configuración 1 — "Money is No Object" (Sin límite de presupuesto)
> Propuesta profesional extrema para centros de cómputo y creadores de alto nivel:

| Componente | Elección | Justificación técnica |
| :--- | :--- | :--- |
| **CPU** | AMD Ryzen Threadripper PRO 9995WX | 96 núcleos y 192 hilos para tareas paralelas masivas; consumo nominal de 350 W [13]. |
| **GPU** | NVIDIA RTX PRO 6000 Blackwell Workstation (96 GB) | 96 GB GDDR7 con ECC y Tensor Cores de 5ª gen; ideal para ciencia de datos y LLMs pesados [15]. |
| **Placa madre** | ASUS Pro WS WRX90E-SAGE SE | Formato SSI-EEB, soporte para Threadripper PRO, 8 canales DDR5 ECC RDIMM y ranuras PCIe 5.0 [14]. |
| **Memoria RAM** | 512 GB DDR5 ECC RDIMM (8 × 64 GB) | Aprovecha los 8 canales de memoria para procesar volúmenes masivos de datos simultáneos [14]. |
| **Almacenamiento** | 2 × Samsung 9100 PRO NVMe PCIe 5.0 de 4 TB | Separa sistema y librerías de modelos y datasets; hasta 14.800/13.400 MB/s cada uno [11]. |
| **Fuente** | be quiet! Dark Power Pro 13 (1600 W) | Conectores nativos 12V-2x6 y amplio margen de estabilidad eléctrica [29]. |
| **Refrigeración** | Noctua NH-U14S TR5-SP6 | Cooler de aire optimizado para socket sTR5 y validado para 9995WX [30]. |
| **Gabinete** | Fractal Design Define 7 XL | Torre espaciosa con soporte nativo para placas SSI-EEB y refrigeración eficiente [31]. |

---

### Bloque 3: Landing Page — Configuración 2: "El Punto Dulce" (Presupuesto hasta USD 800)

#### Encabezado de la Landing Page
> ### Workstation de IA por menos de USD 800
> **Una computadora para aprender, programar, probar modelos locales moderados y crear con IA.**
> Combina un procesador AMD Ryzen 5 5600, 32 GB de memoria RAM, 1 TB en SSD NVMe y una tarjeta gráfica NVIDIA GeForce RTX 3060 de 12 GB.
> Diseñada bajo una cuidada selección de piezas nuevas y usadas para maximizar la VRAM dentro del presupuesto de la consigna.

#### Infografía visual de capacidades (Insertar imagen)
- **Tarjeta 1:** USD 797 · Costo estimado
- **Tarjeta 2:** 12 GB · VRAM RTX 3060
- **Tarjeta 3:** 6 / 12 · Núcleos / Hilos CPU
- **Tarjeta 4:** 32 GB · RAM DDR4-3200
- **Tarjeta 5:** 1 TB · SSD NVMe M.2

#### Diagrama de bloques funcional (Insertar imagen)
- *Imagen del esquema funcional:* Interconexión SSD NVMe ↔ RAM 32 GB ↔ CPU Ryzen 5 5600 ↔ GPU RTX 3060 12GB con placa madre B550 y fuente de 650 W.

#### Tabla de componentes del armado económico (Total exacto: USD 797,40)

| Componente | Elección exacta | Estado | Función en lenguaje sencillo | Precio estimado |
| :--- | :--- | :---: | :--- | :---: |
| **GPU** | NVIDIA GeForce RTX 3060 12 GB *(probar antes de comprar)* | **Usada** | Acelera los modelos de IA; sus 12 GB de VRAM son vitales para cargar los modelos en memoria. | USD 285 [22] |
| **CPU** | AMD Ryzen 5 5600 *(con cooler Wraith Stealth incluido)* | **Nuevo** | Cerebro general del equipo: 6 núcleos y 12 hilos para el sistema y preparación de datos. | USD 110,93 [23] |
| **Placa madre** | MSI PRO B550M-P, socket AM4 | **Nueva** | Placa base que interconecta todos los componentes de manera confiable. | USD 69,99 [24] |
| **Memoria RAM** | 2 × SK hynix HMA82GU6DJR8N-XN, 16 GB c/u (32 GB DDR4-3200, 2Rx8 UDIMM no ECC) | **Usada** | Permite ejecutar programas de datos y multitarea sin colapsar el sistema. | USD 90 [25] |
| **Almacenamiento**| Timetec MS10 35TTFP6PCIE-1TB (SSD NVMe M.2 2280 PCIe 3.0 x4, 1 TB) | **Nuevo** | Unidad de lectura rápida para el sistema operativo, librerías y modelos. | USD 139,99 [26] |
| **Fuente** | Thermaltake Smart BM3, 650 W, 80 Plus Bronze | **Nueva** | Energía limpia y certificada; supera los 550 W mínimos recomendados por NVIDIA [16]. | USD 69,99 [27] |
| **Gabinete** | Cooler Master MasterBox Q300L, MCB-Q300L-KANN-S00 (Micro-ATX) | **Usado** | Chasis con filtros magnéticos y flujo de aire para mantener refrigeradas las piezas. | USD 31,50 [28] |
| **TOTAL COMPONENTES** | | | **Suma total de la torre (sin periféricos ni envío)** | **USD 797,40** |

> *Nota de precios:* Precios consultados en el mercado de Estados Unidos entre el 29 y el 30 de octubre de 2026 [22–28]. Se suman únicamente los componentes: no se agrega reserva para envío. El total tampoco incluye monitor, teclado, mouse ni sistema operativo. Margen hasta el límite de USD 800: **USD 2,60**.

#### Justificación y Cuidados Críticos al Comprar
- **Priorizar la VRAM:** Se busca la RTX 3060 específicamente en su versión de **12 GB** (verificar antes de comprar, ya que existe una variante de 8 GB no adecuada para este propósito).
- **Ahorro seguro:** Se opta por piezas usadas en GPU, RAM y gabinete para no recortar en la gráfica.
- **Confiabilidad en piezas críticas:** La fuente (650 W) y el SSD son nuevos.
- **Límites reales:** Permite aprender, programar y generar imágenes locales moderadas. No está concebida para entrenamiento de modelos masivos desde cero.
- **Verificaciones previas al armado:** Probar la RTX usada bajo estrés técnico antes de cerrar la compra y comprobar que la BIOS de la motherboard B550 sea compatible con la serie Ryzen 5000.

#### Galería de Fotografías de los 7 Modelos Exactos Incorporados

1. **GPU: NVIDIA GeForce RTX 3060 12 GB**
   - *Imagen:* `https://assets.nvidia.partners/images/png/gv-n3060gaming%20oc-12gd.png`
   - *Epígrafe:* Tarjeta gráfica NVIDIA GeForce RTX 3060 de 12 GB GDDR6.
   - *Fuentes:* [Ficha oficial NVIDIA [16]](https://www.nvidia.com/en-us/geforce/graphics-cards/30-series/rtx-3060-3060ti/) · [Referencia de venta usada [22]](https://pcpartvalue.com/gpu/nvidia-geforce-rtx-3060-12-gb-ga106-12-gb-2021).
2. **CPU: AMD Ryzen 5 5600 con disipador Wraith Stealth**
   - *Imagen:* `https://www.amd.com/content/dam/amd/en/images/products/processors/ryzen/2505503-ryzen-5-5600x.jpg`
   - *Epígrafe:* Procesador AMD Ryzen 5 5600 (6 núcleos / 12 hilos) y disipador de fábrica incluido.
   - *Fuentes:* [Ficha oficial AMD [12]](https://www.amd.com/en/support/downloads/drivers.html/processors/ryzen/ryzen-5000-series/amd-ryzen-5-5600.html) · [Oferta Newegg [23]](https://www.newegg.com/amd-ryzen-5-5000-series-ryzen-5-5600-vermeer-socket-am4-desktop-cpu-processor/p/N82E16819113736).
3. **Placa madre: MSI PRO B550M-P**
   - *Imagen:* `https://storage-asset.msi.com/global/picture/image/feature/mb/B550/Pro/pro-b550m-p/kv/msi-pro-b550m-p-kv-mb.png`
   - *Epígrafe:* Placa madre MSI PRO B550M-P, formato Micro-ATX, socket AM4.
   - *Fuentes:* [Ficha oficial MSI [17]](https://www.msi.com/Motherboard/PRO-B550M-P) · [Newegg [24]](https://www.newegg.com/msi-pro-micro-atx-13-144-765-amd-b550-am4/p/N82E16813144765).
4. **Memoria RAM: 2 × SK hynix HMA82GU6DJR8N-XN (32 GB DDR4-3200)**
   - *Imagen:* `https://c1.neweggimages.com/productimage/nb640/AV80S210322CiVrm.jpg`
   - *Epígrafe:* Kit de 2 módulos SK hynix de 16 GB (32 GB DDR4-3200, 2Rx8 UDIMM no ECC).
   - *Fuentes:* [Ficha del producto Newegg [33]](https://www.newegg.com/sk-hynix-desktop-memory-16gb-ddr4-3200-cas-latency-cl22/p/0RN-00BX-000D3) · [Anuncio de referencia OfferUp [25]](https://offerup.com/item/detail/ce28c0c4-2c61-32ce-96bf-3c6f3f6c39eb).
5. **SSD: Timetec MS10 35TTFP6PCIE-1TB**
   - *Imagen:* `https://timetecinc.com/cdn/shop/files/products_M2_3ssd_new.jpg`
   - *Epígrafe:* SSD NVMe Timetec MS10 M.2 2280 PCIe 3.0 x4 de 1 TB.
   - *Fuentes:* [Ficha oficial Timetec [32]](https://timetecinc.com/products/timetec-premium-m-2-nvme-pcie-3-0-ssd) · [Newegg [26]](https://www.newegg.com/timetec-1tb/p/0D9-00ES-00015?Item=9SIA56XBED8694).
6. **Fuente de poder: Thermaltake Smart BM3 650 W**
   - *Imagen:* `https://thermaltakeusa.com/cdn/shop/files/01_1.jpg?v=1691572534`
   - *Epígrafe:* Fuente semimodular Thermaltake Smart BM3 de 650 W, certificación 80 Plus Bronze.
   - *Fuentes:* [Ficha técnica y cotización Thermaltake [27]](https://www.maxmybuild.com/power-supplies/thermaltake-smart-bm3-650w).
7. **Gabinete: Cooler Master MasterBox Q300L (MCB-Q300L-KANN-S00)**
   - *Imagen:* `https://a.storyblok.com/f/281110/8981b52446/gallery-1-min.png/m/960x0/smart`
   - *Epígrafe:* Gabinete Micro-ATX Cooler Master MasterBox Q300L con filtros magnéticos de ventilación.
   - *Fuentes:* [Ficha oficial Cooler Master [34]](https://www.coolermaster.com/es-global/products/masterbox-q300l.html) · [Referencia de venta eBay [28]](https://www.ebay.com/p/17032785790).

---

## 5. Página: Bibliografía y Recursos

Organizada por eje temático con enlaces directos para facilitar la verificación académica:

### Eje 1: CPU, GPU y NPU
- **[1] Intel.** *Core Ultra X9 388H, especificaciones.* [Enlace](https://www.intel.com/content/www/us/en/products/sku/245526/intel-core-ultra-x9-processor-388h-18m-cache-up-to-5-10-ghz/specifications.html)
- **[2] AMD.** *Ryzen AI 9 HX 470, especificaciones oficiales.* [Enlace](https://www.amd.com/en/products/processors/laptop/ryzen/ai-400-series/amd-ryzen-ai-9-hx-470.html)
- **[3] AMD.** *Ryzen AI 400 Series, presentación y datos del producto.* [Enlace](https://www.amd.com/content/dam/amd/en/documents/partner-hub/ryzen/ryzen-ai-400-series-product-deck.pdf)
- **[4] NVIDIA.** *GeForce RTX 5090.* [Enlace](https://www.nvidia.com/en-us/geforce/graphics-cards/50-series/rtx-5090/)
- **[5] Intel.** *Core Ultra X9 388H performance benchmarks.* [Enlace](https://edc.intel.com/content/www/us/en/products/performance/benchmarks/mobile/)
- **[6] NVIDIA Developer Blog.** *TensorRT Unlocks FP4 Image Generation for NVIDIA Blackwell GeForce RTX 50 Series GPUs.* [Enlace](https://developer.nvidia.com/blog/nvidia-tensorrt-unlocks-fp4-image-generation-for-nvidia-blackwell-geforce-rtx-50-series-gpus/)
- **[21] Microsoft Support.** *Windows Studio Effects.* [Enlace](https://support.microsoft.com/en-us/windows/ai/ai-features/windows-studio-effects)

### Eje 2: Almacenamiento y Velocidades
- **[7] PCI-SIG.** *PCIe 5.0 data rates.* [Enlace](https://pcisig.com/what-bit-rates-does-pcie-50-specification-support-and-how-does-it-compare-prior-pcie-generations)
- **[8] Microsoft.** *DirectStorage API and developer resources.* [Enlace](https://devblogs.microsoft.com/directx/directstorage-api-downloads/)
- **[9] Seagate.** *Barracuda Desktop 3TB, product specifications.* [Enlace](https://www.seagate.com/ca/en/support/internal-hard-drives/desktop-hard-drives/desktop-hdd/)
- **[10] Samsung.** *870 EVO 1 TB, product specifications.* [Enlace](https://www.samsung.com/us/memory-storage/sata-ssd/870-evo-sata-2-5-ssd-1tb-sku-mz-77e1t0b-am/)
- **[11] Samsung.** *9100 PRO 4 TB, product specifications.* [Enlace](https://www.samsung.com/us/memory-storage/nvme-ssd/9100-pro-nvme-ssd-sku-mz-vap4t0b-am/)
- **[18] Bandyopadhyay, S. et al. (2024).** *Single-chip photonic deep neural network with forward-only training. Nature Photonics, 18, 1335–1343.* [Enlace](https://www.nature.com/articles/s41566-024-01567-z)
- **[19] Nature. (2024).** *Fully forward mode training for optical neural networks. Nature, 632, 280–286.* [Enlace](https://www.nature.com/articles/s41586-024-07687-4)
- **[20] Yang, S. et al. (2024).** *DNA as a universal chemical substrate for computing and data storage. Nature Reviews Chemistry, 8, 179–194.* [Enlace](https://doi.org/10.1038/s41570-024-00576-4)

### Eje 3: Workstations de Inteligencia Artificial
- **[12] AMD.** *Ryzen 5 5600.* [Enlace](https://www.amd.com/en/support/downloads/drivers.html/processors/ryzen/ryzen-5000-series/amd-ryzen-5-5600.html)
- **[13] AMD.** *Threadripper PRO 9995WX.* [Enlace](https://www.amd.com/en/products/processors/workstations/ryzen-threadripper/9000-wx-series/amd-ryzen-threadripper-pro-9995wx.html)
- **[14] ASUS.** *Pro WS WRX90E-SAGE SE.* [Enlace](https://www.asus.com/us/motherboards-components/motherboards/workstation/pro-ws-wrx90e-sage-se/techspec/)
- **[15] NVIDIA.** *RTX PRO 6000 Blackwell Workstation Edition.* [Enlace](https://www.nvidia.com/es-la/products/workstations/professional-desktop-gpus/rtx-pro-6000/)
- **[16] NVIDIA.** *GeForce RTX 3060 specifications.* [Enlace](https://www.nvidia.com/en-us/geforce/graphics-cards/30-series/rtx-3060-3060ti/)
- **[17] MSI.** *PRO B550M-P motherboard product page.* [Enlace](https://www.msi.com/Motherboard/PRO-B550M-P)
- **[22] PC Part Value.** *GeForce RTX 3060 12 GB usada, referencia de ventas recientes.* [Enlace](https://pcpartvalue.com/gpu/nvidia-geforce-rtx-3060-12-gb-ga106-12-gb-2021)
- **[23] Newegg.** *AMD Ryzen 5 5600, precio de oferta consultado.* [Enlace](https://www.newegg.com/amd-ryzen-5-5000-series-ryzen-5-5600-vermeer-socket-am4-desktop-cpu-processor/p/N82E16819113736)
- **[24] Newegg.** *MSI PRO B550M-P, precio consultado.* [Enlace](https://www.newegg.com/msi-pro-micro-atx-13-144-765-amd-b550-am4/p/N82E16813144765)
- **[25] OfferUp.** *Dos módulos usados SK hynix HMA82GU6DJR8N-XN, 16 GB cada uno, por USD 90.* [Enlace](https://offerup.com/item/detail/ce28c0c4-2c61-32ce-96bf-3c6f3f6c39eb)
- **[26] Newegg.** *Timetec MS10 35TTFP6PCIE-1TB, SSD NVMe de 1 TB; precio consultado USD 139,99.* [Enlace](https://www.newegg.com/timetec-1tb/p/0D9-00ES-00015?Item=9SIA56XBED8694)
- **[27] MaxMyBuild.** *Thermaltake Smart BM3 650 W, referencia de precio.* [Enlace](https://www.maxmybuild.com/power-supplies/thermaltake-smart-bm3-650w)
- **[28] eBay.** *Cooler Master MasterBox Q300L Micro-ATX usado; referencia USD 31,50.* [Enlace](https://www.ebay.com/p/17032785790)
- **[29] be quiet!.** *Dark Power Pro 13 1600 W, especificaciones.* [Enlace](https://www.bequiet.com/es/powersupply/4412)
- **[30] Noctua.** *NH-U14S TR5-SP6, compatibilidad con Threadripper PRO 9995WX.* [Enlace](https://www.noctua.at/en/compatibility/by-components/cpus/amd-ryzen-threadripper-pro-9995wx)
- **[31] Fractal Design.** *Define 7 XL, formatos de placa madre compatibles.* [Enlace](https://www.fractal-design.com/products/cases/define/define-7-xl/)
- **[32] Timetec.** *Ficha oficial e imágenes del SSD NVMe M.2 2280 PCIe 3.0 x4 (35TTFP6PCIE-1TB).* [Enlace](https://timetecinc.com/products/timetec-premium-m-2-nvme-pcie-3-0-ssd)
- **[33] Newegg.** *Especificaciones e imagen del módulo SK hynix HMA82GU6DJR8N-XN: 16 GB DDR4-3200 2Rx8 UDIMM.* [Enlace](https://www.newegg.com/sk-hynix-desktop-memory-16gb-ddr4-3200-cas-latency-cl22/p/0RN-00BX-000D3)
- **[34] Cooler Master.** *Ficha oficial e imágenes del MasterBox Q300L (MCB-Q300L-KANN-S00): Micro-ATX y refrigeración.* [Enlace](https://www.coolermaster.com/es-global/products/masterbox-q300l.html)

---

## 6. Lista de Imágenes Incorporadas y Estado de Materiales

### Imágenes Incorporadas (Oficiales y Autorizadas):
1. **GPU:** NVIDIA GeForce RTX 3060 12 GB (render oficial de socio NVIDIA [16]).
2. **CPU:** AMD Ryzen 5 5600 con disipador Wraith Stealth (fotografía oficial de producto AMD [12]).
3. **Placa madre:** MSI PRO B550M-P (asset oficial de placa MSI [17]).
4. **Memoria RAM:** SK hynix HMA82GU6DJR8N-XN (fotografía del producto en Newegg / SK hynix [33]).
5. **SSD:** Timetec MS10 35TTFP6PCIE-1TB (fotografía del catálogo oficial de Timetec Inc. [32]).
6. **Fuente:** Thermaltake Smart BM3 650 W Bronze (fotografía oficial de producto Thermaltake [27]).
7. **Gabinete:** Cooler Master MasterBox Q300L (fotografía oficial de la galería Cooler Master [34]).
8. **Punto 1:**
   - Referencia FLUX.1 / Stable Diffusion TensorRT FP4 en GPU Blackwell (NVIDIA Developer Blog [6]).
   - Panel de control de Windows Studio Effects en Copilot+ PC con NPU (Microsoft Support [21] y Microsoft Learn).
   - Motor DaVinci Neural Engine acelerado por GPU (Blackmagic Design DaVinci Resolve).

### Materiales opcionales que el grupo puede seguir aportando:
- Capturas de pantalla tomadas directamente en las computadoras personales de los estudiantes ejecutando las herramientas locales si el docente requiere capturas propias del grupo.
- Nombres de los integrantes para la portada final del PDF.
