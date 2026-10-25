## Anthony Vera Baldeón

**Ingeniero Metalúrgico (UNI) · Desarrollo full stack, QA automatizado y datos**

Más de 7 años en planta industrial —supervisión de moldeo y acería, control metrológico y
auditoría de procesos bajo ISO 9001/14001/45001, de 2023 a 2026 en **ME Elecmetal Funvesa**—.
Hoy llevo ese criterio al software: APIs en Python y FastAPI, aplicaciones en Next.js y
TypeScript, pipelines de datos con SQL y PySpark, y pruebas automatizadas en todo lo que construyo.

**Databricks Certified Data Engineer Associate** · En curso: Power BI PL-300 (Microsoft Learn), Kaggle Learn (Advanced SQL, Data Cleaning)

📍 Lima, Perú · Disponible para trabajo remoto · Inglés intermedio (lectura técnica fluida) · [LinkedIn](https://linkedin.com/in/anthonyverabaldeon) · anthonyverab@gmail.com

---

### Proyectos destacados

**[whatsapp-ai-assistant](https://github.com/Laxionx/whatsapp-ai-assistant)** — *Python · FastAPI · WhatsApp Cloud API · OpenAI/Anthropic · SQLite · pytest*
Asistente de WhatsApp para negocios: webhook que valida la firma de Meta (HMAC), ignora
mensajes duplicados, responde con preguntas frecuentes configurables en YAML o con un LLM
—con vuelta automática a las reglas si falla— y deriva a una persona cuando se le pide.
**44 tests, 100 % de cobertura**, simulador para probarlo sin cuenta de Meta.

**[qa-automation-demo](https://github.com/Laxionx/qa-automation-demo)** — *pytest · Selenium · Postman/Newman · k6 · GitHub Actions · GitLab CI*
Automatización de pruebas de punta a punta sobre una tienda demo propia: pruebas unitarias
y de API, E2E con Selenium y Page Object, colecciones de Postman en el pipeline, carga con
k6 y un plan de pruebas documentado.

**[retencion-estudiantil-analytics](https://github.com/Laxionx/retencion-estudiantil-analytics)** — *SQL (DuckDB) · Python · PySpark · estadística*
Análisis de retención con modelo estrella, funciones de ventana, pruebas de calidad de datos
e intervalos de confianza. Muestra por qué comparar «en campaña vs fuera» engaña y cómo un
grupo de control aleatorio mide el efecto real de cada acción.

### Simuladores metalúrgicos

Implementados desde la literatura y contrastados con datos publicados. Cada modelo fija su
tolerancia antes de correr y documenta dónde no la cumple.

**[simulador-conminucion](https://github.com/Laxionx/simulador-conminucion)** — *Python · NumPy/SciPy · Streamlit* · **[▶ probar en el navegador](https://simulador-conminucion-mtxoolyzuvvcxrq8rce3el.streamlit.app/)**
Circuitos de molienda y clasificación (molino de bolas, hidrociclón, chancadora, energía de
Bond) con reciclos, reconciliación de balances y ajuste con intervalos de confianza.
Contrastado con los reportes de salida del curso de MODSIM. **168 pruebas.**

**[simulador-procesos](https://github.com/Laxionx/simulador-procesos)** — *Python · PHREEQC · YAML · Streamlit* · **[▶ probar en el navegador](https://simulador-procesos-ntfmuyhlnqc9d73kkqljzk.streamlit.app/)**
Balance de masa y de calor de plantas de cobre y estaño: lixiviación, SX-EW, flotación, fusión
flash, conversión, electrorrefinación y fundición de estaño, con datos publicados de Atlantic
Copper, Mount Isa y Funsur. La planta se describe en YAML y sale un reporte HTML con el costo
operativo, y una app con los equipos animados según su cálculo. **671 pruebas.**

**[tratamientos-termicos](https://github.com/Laxionx/tratamientos-termicos)** — *Python · pycalphad · programación lineal · Streamlit* · **[▶ probar en el navegador](https://tratamientos-termicos-6wqfzanyzyscgjwaexmopu.streamlit.app/)**
Hierro blanco alto cromo de bolas de molienda: desestabilización (CALPHAD), temple de la bola,
cálculo de carga del horno y revenido, cada uno contra estudios publicados, una app con el temple de la bola animado y una validación ampliada con datos nuevos. **242 pruebas.**

**[laboratorio-ensayos](https://github.com/Laxionx/laboratorio-ensayos)** — *Python · NumPy · Streamlit* · **[▶ probar en el navegador](https://laboratorio-ensayos-bromrnpno3wqjwkdmqcuov.streamlit.app/)**
Ensayo al fuego y ensayos metalúrgicos: error de muestreo de Gy y nomograma del protocolo, oro grueso
con Poisson, carga fundente con el crisol en fusión, cinética de cianuración y sedimentación para
dimensionar espesadores. Validado contra Minnitt, Chieregati, el USGS, Bugbee, Coe y Clevenger y datos
de Vale; documenta erratas de los artículos fuente. **613 pruebas.**

**[flotacion-silice](https://github.com/Laxionx/flotacion-silice)** — *Python · scikit-learn*
Sensor virtual de la sílice del concentrado con datos reales de planta, evaluado en un periodo
reservado contra la lectura anterior: gana, pero poco, y lo dice.

### Demos industriales

**[optimizador-carga-eaf](https://github.com/Laxionx/optimizador-carga-eaf)** — *Python · PuLP · Streamlit*
Programación lineal que calcula la mezcla de carga de un horno de arco eléctrico al
**mínimo costo**, cumpliendo la química objetivo de C, Mn y Si dentro de **±0,02 %**.

**[trazabilidad-forense](https://github.com/Laxionx/trazabilidad-forense)** — *SQL · SQLite · Python*
Trazabilidad **colada → pieza → defecto** con consultas de causa raíz que relacionan
variables de proceso (temperatura, %S) con defectos de calidad.

> Todos los proyectos usan datos sintéticos: demuestran el método, no contienen información
> de ninguna empresa.

---

### Stack

| | |
|---|---|
| **Backend** | Python · FastAPI · REST y webhooks · PostgreSQL / Supabase (RLS) · APIs de OpenAI y Anthropic |
| **Frontend** | React · Next.js (App Router) · TypeScript · Tailwind CSS |
| **Datos** | SQL · pandas · NumPy · PySpark · Databricks · DuckDB · programación lineal (PuLP) |
| **QA** | pytest · Playwright · Selenium · Postman/Newman · k6 · CI con GitHub Actions y GitLab |
| **Industria** | Fundición de acero · control de procesos · ISO 9001/14001/45001 · metodología A3 |

### Cómo trabajo

Mido antes de concluir. Diseño primero el control que puede refutar mi propia hipótesis y
solo después miro el resultado. En planta eso fue **−15 % de no conformidades** con A3 y
**−10 % en tiempos de ciclo**; en software es validación de entrada, pruebas automatizadas
e intervalos de confianza en vez de un número suelto. Trabajo con desarrollo asistido por IA
(Claude Code, Codex) y reviso y pruebo todo lo que se genera.
