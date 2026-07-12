# Arbol φ — Test del Árbol con Proporción Áurea

App web para el Test del Dibujo del Árbol (Tree Drawing Test) con análisis de desviación de la proporción áurea (φ ≈ 1.618) para detección de deterioro cognitivo.

Basado en el estudio de **Stanzani Maserati & Zama (2026)** publicado en *Scientific Reports*, IRCCS Bolonia, Italia.

## Resumen del Artículo Científico

**Título:** *Quantifying golden-ratio deviations in the Tree Drawing Test to identify patients with Alzheimer's disease*
**Revista:** Scientific Reports (2026)
**Autores:** Maserati & Zama (IRCCS Bolonia, Italia)
**Muestra:** 1,379 participantes (613 EA, 328 DCL, 438 controles sanos)

### ¿De qué trata?

Analizaron el Test del Dibujo del Árbol (TDT) —pedirle al paciente que dibuje un árbol— y calcularon qué tanto se desvía la proporción tronco/copa de la proporción áurea (φ ≈ 1.618). El mejor índice fue **H/φ − T** (altura total entre φ menos altura del tronco).

Los pacientes con Alzheimer son los que más se acercan a la proporción áurea (menor desviación), los controles sanos los que más se alejan, y los DCL quedan en medio. Sin embargo, los enfermos dibujan árboles mucho más pequeños y simplificados, por lo que esa "cercanía a φ" es por pobreza del dibujo, no por armonía preservada.

### ¿A qué pacientes aplicarlo?

**Candidatos ideales:**
- Pacientes con queja cognitiva o sospecha de deterioro (target principal del estudio)
- Pacientes con MMSE limítrofe o no concluyente (funciona como complemento)
- Evaluación inicial en atención primaria o neurología (prueba barata, rápida, solo papel y lápiz)
- Pacientes ≥ 60–65 años
- Descartar deterioro en pacientes con sospecha baja (AUC = 0.911 para controles sanos, VPN = 0.92)

**Contraindicaciones (criterios de exclusión):**
- Enfermedad neurológica o psiquiátrica activa (depresión mayor, esquizofrenia, etc.)
- Alcoholismo o abuso de sustancias
- Uso de neurolépticos, antipsicóticos, antidepresivos tricíclicos o benzodiacepinas
- Problemas visuales severos (glaucoma avanzado, cataratas, degeneración macular)
- Apraxia severa o problemas motores de miembros superiores

### Limitaciones importantes
- DCL sigue siendo difícil de clasificar: AUC = 0.736 (el peor rendimiento)
- Punto de corte práctico: H/φ − T ≤ 14.37 para detectar deterioro (sens 80%, espec 75%)
- No reemplaza la evaluación neuropsicológica — es un complemento
- Requiere validación externa antes de uso clínico rutinario (estudio unicéntrico italiano)

### En una frase
> Este test del árbol con análisis de proporción áurea sirve como screening complementario en pacientes con sospecha de deterioro cognitivo, es muy bueno para identificar controles sanos (los descarta con alta confianza), pero se le dificulta diferenciar DCL de Alzheimer temprano.

## Cómo usar la app

1. Toma una foto o sube un dibujo de árbol hecho a lápiz en una hoja de papel
2. Marca 3 puntos en la pantalla: 🟡 copa (punta), 🔴 base del tronco, 🟢 unión tronco-copa
3. Presiona 🌀 Calcular y obtén los índices φ con correlación diagnóstica

## Tecnología

HTML + CSS + JS puro — sin frameworks, sin servidor, sin dependencias. Funciona en cualquier navegador moderno con HTTPS.

## Referencia

Stanzani Maserati M., Zama F. (2026). *Quantifying golden-ratio deviations in the Tree Drawing Test to identify patients with Alzheimer's disease*. Scientific Reports.
DOI: [10.1038/s41598-026-61257-4](https://doi.org/10.1038/s41598-026-61257-4)

**⚠️ Importante:** Herramienta de investigación. No reemplaza una evaluación clínica neuropsicológica completa. Los resultados son orientativos y deben ser interpretados por un profesional de la salud.
