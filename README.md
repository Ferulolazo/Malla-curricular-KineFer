# Malla-curricular-KineFer
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <title>Malla Kinesiología UChile</title>
    <script type="module">
      import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs';
      mermaid.initialize({ startOnLoad: true });
    </script>
  </head>
  <body>
    <h1 style="text-align:center;">Malla Curricular Interactiva – Kinesiología UChile</h1>
    <pre class="mermaid">
      graph TD
      %% Primer Año
      S1_BIOQ["Bases Integradas de Química, Biología Celular y Genética"]
      S1_FISIKA["Física para el Estudio de la Kinesiología"]
      S1_INTRO["Introducción a la Kinesiología"]
      S1_ANAT1["Anatomía Estructural y Funcional I"]
      S1_TISU["Estructura y Función Tisular"]
      S1_ESTRAT["Estrategias de Búsqueda Bibliográfica"]
      S1_ING1["Inglés I"]

      S2_PRINC["Principios de Evaluación"]
      S2_FISIOG["Fisiología General"]
      S2_NEURO["Neuroanatomía"]
      S2_ANAT2["Anatomía Estructural y Funcional II"]
      S2_HUM["Introducción al Estudio del Movimiento Humano"]
      S2_COMP["Lectura Comprensiva de Artículos Científicos"]
      S2_ING2["Inglés II"]

      %% Segundo Año
      S3_EXAM["Examen Kinésico Básico"]
      S3_FISIOSIS["Fisiología de Sistemas"]
      S3_BASESINF["Bases Integradas de Infecciosa, Inmunología y Farmacología"]
      S3_CTRL["Control y Aprendizaje Motor"]
      S3_EDUFIS["Educación Física I"]
      S3_FUNDINV["Fundamentos de la Investigación Científica"]
      S3_ING3["Inglés III"]

      S4_PROC["Procedimientos Terapéuticos Básicos y Generales"]
      S4_FISIOPATO["Fisiopatología y Disfunción en Sistemas"]
      S4_DESAR["Kinesiología del Desarrollo Psicomotor"]
      S4_ANALISIS["Análisis Biomecánico del Movimiento Humano"]
      S4_COND["Efectos de la Condición Física y la Conducta"]
      S4_LECT["Lectura Crítica de Artículos Científicos"]
      S4_MIM1["Módulo Integrado Interdisciplinario I"]

      %% Tercer Año
      S5_RESP1["Evaluación e Intervención en Cuidados Respiratorios I"]
      S5_NEURO1["Evaluación e Intervención en Neurokinesiología I"]
      S5_ESQUE1["Evaluación e Intervención en Neuro Músculo Esquelético I"]
      S5_AFYDEP["Actividad Física y Deportes I"]
      S5_EPI["Análisis Epidemiológico"]
      S5_MODELO["Análisis del Modelo de Salud"]
      S5_ETICA["Responsabilidad del Ejercicio Profesional"]

      S6_RESP2["Evaluación e Intervención en Cuidados Respiratorios II"]
      S6_NEURO2["Evaluación e Intervención en Neurokinesiología II"]
      S6_ESQUE2["Evaluación e Intervención en Neuro Músculo Esquelético II"]
      S6_RAZ["Razonamiento Clínico"]
      S6_EFISAL["Efectos de la Actividad Física en la Salud"]
      S6_DIS["Diseño y Formulación de Proyectos de Investigación"]
      S6_MIM2["Módulo Integrado Interdisciplinario II"]

      %% Cuarto Año
      S7_CONTEXT1["Intervención Profesional en Contexto I"]
      S7_ANALISISR["Análisis de la Relación Persona Entorno"]
      S7_DEP1["Estrategias Deportivas y Recreativas"]
      S7_SOCIAL["Determinantes Sociales de la Salud"]
      S7_ADMSAL["Procesos de Administración en Salud"]
      S7_EJEC1["Ejecución de Proyectos de Investigación I"]

      S8_CONTEXT2["Intervención Profesional en Contexto II"]
      S8_ERGO["Evaluación en Ergonomía"]
      S8_DEP2["Estrategias Deportivas y Recreativas Aplicadas"]
      S8_PROMO["Programas de Promoción y Prevención en Salud"]
      S8_EMP["Proyectos de Emprendimiento"]
      S8_EJEC2["Ejecución de Proyectos de Investigación II"]

      %% Quinto Año
      S9_CONTEXT3["Intervención Profesional III"]
      S9_PROYERGO["Proyectos de Intervención Ergonómica"]
      S9_COM["Comunicación Científica"]

      S10_CONTEXT4["Intervención Profesional IV"]
      S10_PROF["Cursos de Profundización Disciplinar y Profesional"]
      S10_COMSAL["Intervención en Salud Comunitaria"]
      S10_ADM["Administración en Salud"]

      %% Relaciones ejemplo:
      S1_ANAT1 --> S2_ANAT2
      S2_FISIOG --> S3_FISIOSIS
      S3_FISIOSIS --> S4_FISIOPATO
      S3_CTRL --> S5_ESQUE1
      S4_PROC --> S5_RESP1
      S5_RESP1 --> S6_RESP2
      S5_NEURO1 --> S6_NEURO2
      S5_ESQUE1 --> S6_ESQUE2
      S6_DIS --> S7_EJEC1 --> S8_EJEC2
      S8_EJEC2 --> S9_COM
      S9_CONTEXT3 --> S10_CONTEXT4

    </pre>
  </body>
</html>
