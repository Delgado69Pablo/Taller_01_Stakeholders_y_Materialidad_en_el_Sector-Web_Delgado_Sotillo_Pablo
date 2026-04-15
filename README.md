# Taller 1 — Stakeholders y Materialidad en el Sector Web

Este repositorio contiene el desarrollo completo del Taller 1 del módulo **Sostenibilidad Aplicada al Sistema Productivo (UD05)**.  
El objetivo es identificar los **grupos de interés (stakeholders)** y los **aspectos ASG materiales** para una consultora web, estructurándolos en un archivo XML y documentando el proceso.

---

## 1. Stakeholders Identificados

Según la teoría de Freeman y el análisis del documento UD05, los principales grupos de interés son:

- **Clientes corporativos** — Alta influencia en los objetivos empresariales.  
- **Usuarios finales** — Relevancia social por accesibilidad y privacidad.  
- **Proveedores cloud** — Impacto ambiental por consumo energético.

---

## 2. Temas Materiales (ASG)

### **A — Ambiental**
- *Eficiencia energética del código* (Green Code).  
  Minimización del uso de CPU y memoria para reducir la huella digital.

### **S — Social**
- *Accesibilidad universal*.  
  Garantizar que las aplicaciones web sean inclusivas.

### **G — Gobernanza**
- *Transparencia algorítmica*.  
  Explicar y auditar decisiones automatizadas.

---

## 3. Archivo XML

El archivo `materialidad.xml` contiene:

- Raíz `<empresa_sostenible>`  
- Tres nodos `<stakeholder>` con atributo `importancia`  
- Tres nodos `<tema_material>` con atributo `impacto` (A, S o G)

---

## 4. Fuentes (Formato IEEE)

[1] R. E. Freeman, *Strategic Management: A Stakeholder Approach*. Cambridge University Press, 2010.  
[2] K. Berntsen et al., “Sustainability in Software Engineering – A Systematic Mapping,” 2017.  
[3] United Nations Global Compact, *Pymes y sostenibilidad. Guía para aumentar su impacto ASG*, 2024.  
[4] IBM, “¿Qué es la codificación verde y por qué es importante?”, 2026.

---

## 5. Gestión de Versiones (Commits recomendados)

1. **docs:** añadido README inicial y referencias IEEE  
2. **feat:** creada estructura base de `materialidad.xml`  
3. **refactor:** completados nodos ASG y comentarios explicativos

---
