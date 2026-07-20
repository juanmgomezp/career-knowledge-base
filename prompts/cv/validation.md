# CV Validation Specification

## Objetivo

Definir las validaciones finales que deberán ejecutarse antes de entregar un currículum.

Este documento no genera contenido.

No modifica el contenido.

No decide qué información incluir.

Únicamente verifica que el CV cumple todas las especificaciones definidas por los demás documentos.

---

# Principio

El currículum sólo podrá entregarse cuando todas las validaciones sean satisfactorias.

Si alguna validación falla, deberá corregirse antes de generar la versión final.

Nunca entregar un CV con validaciones pendientes.

---

# Alcance

Validar:

- integridad
- consistencia
- precisión
- cumplimiento de especificaciones
- adaptación a la vacante

No realizar nuevas optimizaciones durante esta etapa.

---

# Validación de la fuente

Verificar que toda la información proviene exclusivamente de la Career Knowledge Base.

Confirmar que no existen:

- experiencias inventadas;
- proyectos inventados;
- tecnologías inventadas;
- habilidades inventadas;
- certificaciones inventadas;
- fechas inventadas;
- cargos inventados;
- métricas inventadas.

Si existe información sin respaldo en la KB, deberá eliminarse.

---

# Validación de la Job Description

Confirmar que el CV fue adaptado para la vacante.

Verificar que:

- el Summary refleja el perfil solicitado;
- las experiencias relevantes fueron priorizadas;
- los proyectos seleccionados son pertinentes;
- las habilidades técnicas apoyan la candidatura;
- las palabras clave importantes fueron consideradas.

---

# Validación del Summary

Verificar que:

- resume correctamente el perfil;
- está adaptado a la vacante;
- no contiene frases genéricas;
- no repite información de Experience;
- no contiene afirmaciones sin evidencia.

---

# Validación de Experience

Verificar que:

- todas las experiencias siguen la misma estructura;
- el orden cronológico es correcto;
- los bullets reflejan contribuciones relevantes;
- no existen responsabilidades repetidas;
- no existen logros duplicados;
- las tecnologías mostradas tienen evidencia.

---

# Validación de Projects

Cuando la sección exista, verificar que:

- todos los proyectos provienen de la KB;
- cada proyecto aporta valor para la vacante;
- no duplican Experience;
- las tecnologías son correctas.

Si la sección no aporta valor, confirmar que fue omitida.

---

# Validación de Technical Skills

Verificar que:

- todas las tecnologías tienen evidencia;
- no existen duplicados;
- las categorías son consistentes;
- las tecnologías son relevantes para la vacante.

---

# Validación de Education

Verificar que:

- todas las instituciones son correctas;
- todos los títulos existen en la KB;
- las fechas son consistentes;
- no existen datos académicos innecesarios.

---

# Validación de Languages

Verificar que:

- todos los idiomas tienen evidencia;
- todos los niveles están documentados;
- el formato es consistente.

---

# Validación de redacción

Confirmar que el documento cumple las reglas definidas en `writing.md`.

Verificar especialmente que:

- no existen frases genéricas;
- no existen exageraciones;
- no existen afirmaciones sin evidencia;
- la redacción es clara;
- el tono es profesional;
- no existen párrafos innecesarios.

---

# Validación ATS

Confirmar el cumplimiento de todas las reglas definidas en `ats.md`.

Verificar especialmente que:

- no existen tablas;
- no existen columnas;
- no existen iconos;
- no existen imágenes;
- no existen cuadros de texto;
- los encabezados son estándar;
- el contenido puede leerse linealmente.

---

# Validación de Layout

Confirmar el cumplimiento de todas las reglas definidas en `layout.md`.

Verificar que:

- el orden de las secciones es correcto;
- el formato es consistente;
- las tecnologías utilizan el formato definido;
- el documento mantiene una presentación uniforme.

---

# Validación de consistencia

Verificar que:

- no existen contradicciones entre secciones;
- las fechas coinciden;
- los cargos coinciden;
- las tecnologías coinciden;
- los proyectos coinciden;
- los idiomas coinciden.

---

# Validación de duplicados

Eliminar información repetida entre:

- Summary;
- Experience;
- Projects;
- Technical Skills.

Cada sección deberá aportar información diferente.

---

# Validación de longitud

Verificar que:

- el documento cumple el límite definido;
- ninguna sección ocupa un espacio desproporcionado;
- existe un equilibrio adecuado entre las secciones.

---

# Validación de idioma

Confirmar que:

- todo el documento utiliza el idioma solicitado;
- no existen mezclas innecesarias;
- la terminología es consistente;
- las traducciones mantienen el significado original.

---

# Validación final

Antes de entregar el CV confirmar que:

- toda la información proviene de la Career Knowledge Base;
- el documento está adaptado a la vacante;
- todas las especificaciones fueron respetadas;
- no existen inconsistencias;
- no existen duplicados;
- no existen afirmaciones sin evidencia;
- el formato es uniforme;
- el CV está listo para enviarse sin modificaciones adicionales.

---

# Resultado esperado

El resultado de esta validación deberá ser uno de los siguientes:

**PASS**

Todas las validaciones fueron satisfactorias.

El CV puede entregarse.

**FAIL**

Existe al menos una validación incumplida.

El CV deberá corregirse antes de entregarse.

---

# Responsabilidad

Este documento únicamente define el proceso de validación final del currículum.

No define:

- la estructura del documento;
- las reglas de redacción;
- las reglas ATS;
- el contenido de las secciones;
- la estrategia de adaptación.

Estas responsabilidades pertenecen a los documentos especializados correspondientes.