<p align="center">
  <img src="../assets/logo-brown.png" alt="CDAD Logo" width="350"/>
</p>

# Context-Driven AI Development (CDAD)
Copyright © 2026 Moisés Griott
Licensed under CC BY 4.0

> **Cuando el contexto no gobierna a la IA, la IA termina gobernando la solución.**

> **El verdadero trabajo no es generar código con IA. El verdadero trabajo es diseñar y mantener el contexto que gobierna a la IA.**

Una metodología para el desarrollo de software asistido por IA basada en contexto gobernado, control arquitectónico, trazabilidad del conocimiento y aceleración sostenible.

---

## Autor

**Moisés Griott**  
**Digital Architect | Cloud & Agentic AI Architect | Distributed Systems | MCP, Multi-Agent Systems & Enterprise AI**

Más de 20 años de experiencia en desarrollo de software, diseño de soluciones, arquitectura tecnológica y modernización empresarial.

---

## Estado del Documento

**Versión:** 1.0  
**Estado:** En construcción y maduración continua.  
**Objetivo:** Consolidar una metodología práctica para el desarrollo de software asistido por IA, basada en arquitectura, contexto, conocimiento, gobernanza y aceleración controlada.

---

# 1. Introducción

**Context-Driven AI Development (CDAD)** nace como una metodología práctica para trabajar con Inteligencia Artificial en el desarrollo de soluciones tecnológicas sin perder control arquitectónico, coherencia técnica ni trazabilidad del conocimiento.

La IA es una herramienta extremadamente poderosa cuando se utiliza dentro de un marco de trabajo definido. La clave no está en generar código de forma indiscriminada, sino en proporcionar un contexto continuo que preserve el diseño, la arquitectura, los principios y las restricciones de la solución durante todo el ciclo de desarrollo.

CDAD surge desde la experiencia real en desarrollo de software, arquitectura de soluciones, sistemas distribuidos, plataformas cloud, modernización empresarial y arquitecturas basadas en IA Agéntica, MCP y sistemas multiagente.

La llegada de la IA Generativa no elimina la necesidad de arquitectura; por el contrario, la hace aún más importante.

La IA puede acelerar la implementación, automatizar tareas repetitivas y aumentar la productividad. Sin embargo, la arquitectura, las decisiones técnicas, el conocimiento del dominio, las restricciones de negocio y la visión de la solución continúan siendo responsabilidad del diseñador de la solución.

---

# 2. ¿Por Qué Nace CDAD?

Comenzamos con una idea clara de solución, una arquitectura definida y el apoyo de la IA para acelerar el desarrollo.

Al principio todo funcionaba bien. La IA generaba código rápidamente y permitía avanzar a gran velocidad.

Sin embargo, después de muchas iteraciones, comenzaron a aparecer señales preocupantes.

De un momento a otro, partes del código habían cambiado de enfoque. Algunos módulos ya no seguían el patrón original. El paradigma inicial comenzó a mezclarse con nuevas aproximaciones que nunca habíamos decidido adoptar formalmente.

Lo más complejo es que ningún cambio parecía incorrecto de forma individual. El problema aparecía al observar la solución completa.

Llegó un momento en que nos preguntamos:

- ¿Cuándo cambió la arquitectura?
- ¿Quién decidió este nuevo enfoque?
- ¿Por qué este módulo funciona distinto al resto?
- ¿En qué momento dejamos de seguir el diseño original?
- ¿Cómo llegó mi código a convertirse en algo que ya no controlo completamente?

La realidad era simple:

**La IA no estaba siguiendo una arquitectura gobernada; estaba respondiendo al contexto parcial disponible en cada interacción.**

El problema no era la generación de código.

El problema era la ausencia de una estrategia para gobernar el contexto que guía a la IA.

> **Cuando el contexto no gobierna a la IA, la IA termina gobernando la solución.**

---

# 3. Principio Fundacional

CDAD se basa en una premisa simple:

> La IA puede generar código.  
> La IA puede proponer soluciones.  
> La IA puede acelerar la implementación.  
> Pero solamente las personas responsables del diseño de la solución deben gobernar el contexto que guía a la IA.

Por esta razón, el contexto se transforma en el activo más importante del proyecto.

---

# 4. Visión

Transformar el desarrollo asistido por IA desde un enfoque centrado únicamente en la generación de código hacia un enfoque centrado en la gestión, protección y evolución del contexto.

El objetivo es construir soluciones más consistentes, mantenibles, escalables, trazables y alineadas con los objetivos del negocio.

---

# 5. Hipótesis Central de CDAD

El código ya no es la única fuente de conocimiento de un sistema.

En un entorno asistido por IA, el contexto gobernado se transforma en la verdadera fuente de verdad de la solución.

La arquitectura vive en el contexto.  
La IA ejecuta sobre ese contexto.  
Los equipos evolucionan el contexto.  
Y el software emerge como consecuencia de ello.

---

# 6. Pilares de CDAD

1. **Context Engineering**: construcción y mantenimiento del contexto que guía a la IA.
2. **Governance of Context**: control y evolución disciplinada del conocimiento del proyecto.
3. **Context Protection Pattern (CPP)**: protección de documentos fundacionales y decisiones arquitectónicas.
4. **Markdown-Driven Development**: uso de markdowns versionados como fuente viva de contexto.
5. **Agentic Development Environment (ADE)**: selección de entornos donde humanos y agentes colaboran con contexto compartido.
6. **AI-Assisted Delivery**: aceleración de implementación, pruebas, documentación y automatización.
7. **Controlled Vibe Coding**: uso del Vibe Coding como fase de aceleración, no como fundamento arquitectónico.

---

# 8. Governance of Context

## 5.1 Definición

**Governance of Context** es el conjunto de prácticas, reglas y mecanismos que permiten controlar, proteger y evolucionar el conocimiento que guía a la Inteligencia Artificial durante el ciclo de vida de una solución.

CDAD considera que el contexto es un activo estratégico y que debe administrarse con el mismo nivel de disciplina que tradicionalmente se ha aplicado al código fuente.

---

## 5.2 Single Source of Truth

Los documentos de contexto constituyen la **Fuente Única de la Verdad** (*Single Source of Truth*).

Estos artefactos representan el conocimiento oficial del proyecto y tienen prioridad sobre cualquier interpretación realizada por la IA.

Ejemplos:

- `vision.md`
- `architecture.md`
- `principles.md`
- `constraints.md`
- `adr/*.md`
- `domain-model.md`
- `business-rules.md`
- `use-cases.md`
- `api-contracts.md`

La IA puede trabajar con estos documentos, pero no debe modificarlos libremente.

---

# 8. Context Protection Pattern (CPP)

## 6.1 Definición

CDAD introduce el patrón:

## CPP — Context Protection Pattern

**Objetivo:**  
Proteger los artefactos fundacionales del proyecto y preservar la integridad del conocimiento que gobierna a la Inteligencia Artificial durante todo el ciclo de vida de la solución.

La IA puede:

- Analizar.
- Recomendar.
- Detectar inconsistencias.
- Proponer cambios.
- Justificar mejoras.

La IA no puede:

- Modificar arquitectura base.
- Alterar principios del sistema.
- Redefinir decisiones arquitectónicas.
- Cambiar restricciones de negocio.
- Reescribir la fuente de verdad sin aprobación explícita.

---

## 6.2 Estructura Recomendada

```text
/project

├── /context
│   ├── vision.md
│   ├── architecture.md
│   ├── principles.md
│   ├── constraints.md
│   └── glossary.md
│
├── /business
│   ├── business-rules.md
│   ├── use-cases.md
│   └── domain-model.md
│
├── /adr
│   ├── ADR-001.md
│   ├── ADR-002.md
│   └── ADR-003.md
│
├── /features
│   ├── feature-a.md
│   ├── feature-b.md
│   └── roadmap.md
│
├── /design
│   ├── diagrams/
│   ├── sequence-flows/
│   └── integrations/
│
└── /implementation
    ├── source-code/
    ├── tests/
    └── deployment/
```

---

## 6.3 Niveles de Protección

### L0 — Fundacional

Documentos que representan la fuente principal de verdad del sistema.

Ejemplos:

- `vision.md`
- `architecture.md`
- `principles.md`
- `constraints.md`

Reglas:

- Solo modificables por el Arquitecto o Diseñador de la Solución.
- La IA puede analizarlos.
- La IA puede referenciarlos.
- La IA puede proponer mejoras.
- La IA no puede modificarlos automáticamente.

---

### L1 — Arquitectura y Negocio

Ejemplos:

- ADRs.
- Reglas de negocio.
- Casos de uso.
- Modelos de dominio.
- Contratos de APIs.

Reglas:

- La IA puede proponer cambios.
- Requiere revisión humana.
- Todo cambio debe quedar registrado.

---

### L2 — Diseño y Documentación Técnica

Ejemplos:

- Diagramas.
- Especificaciones.
- Flujos.
- Markdowns técnicos.
- Documentación de integración.

Reglas:

- La IA puede generar contenido.
- La IA puede sugerir actualizaciones.
- Se recomienda revisión humana.

---

### L3 — Implementación

Ejemplos:

- Código fuente.
- Pruebas.
- Scripts.
- Pipelines.
- Automatizaciones.

Reglas:

- La IA puede crear.
- La IA puede modificar.
- La IA puede refactorizar.
- El equipo mantiene la responsabilidad final.

---

## 6.4 Comportamiento Esperado de la IA

Cuando la IA detecta una posible mejora sobre un documento protegido, no debe aplicar el cambio directamente.

Ejemplo:

```text
Documento afectado:
architecture.md
```

Respuesta esperada:

```text
Proposed Architecture Change

Current Decision:
Microservices Architecture

Suggested Improvement:
Event-Driven Architecture

Impact:
Positive impact on scalability and decoupling.

Risk:
Higher operational complexity.

Status:
Requires Architect Approval
```

---

## 6.5 Principio de Inmutabilidad Arquitectónica

La arquitectura vigente permanece inmutable hasta que el Diseñador de la Solución apruebe explícitamente una nueva versión del contexto.

La IA trabaja sobre la arquitectura.  
La IA no gobierna la arquitectura.

---

## 6.6 CPP Golden Rule

> La IA puede sugerir cambios al contexto.  
> La IA puede justificar cambios al contexto.  
> La IA puede analizar el contexto.  
> La IA nunca debe convertirse en propietaria del contexto.

La propiedad del contexto pertenece al Diseñador de la Solución.

---

# 9. Definición del Marco de Trabajo

Antes de generar una sola línea de código, se debe establecer:

- Objetivos de negocio.
- Alcance funcional.
- Paradigma de desarrollo.
- Arquitectura objetivo.
- Patrones de diseño.
- Restricciones técnicas.
- Convenciones de desarrollo.
- Estándares de calidad.
- Estrategia de despliegue.
- Consideraciones de seguridad.
- Estrategia de documentación.
- Modelo de versionamiento del contexto.

La IA debe comprender este contexto desde el inicio y mantenerlo durante toda la evolución de la solución.

---

# 10. Diseño Guiado por Contexto

El diseño de la solución se construye utilizando artefactos que sirven como contexto permanente para la IA:

- Markdowns versionados.
- Diagramas de arquitectura.
- Flujos funcionales.
- Casos de uso.
- ADRs.
- Definiciones de dominio.
- Contratos de APIs.
- Reglas de negocio.
- Estrategias de integración.
- Modelos de datos.
- Decisiones técnicas.
- Restricciones operacionales.

Estos elementos actúan como una memoria estructurada que permite mantener la coherencia técnica del proyecto.

---

# 11. Context Engineering

El verdadero acelerador no es la generación de código.

El verdadero acelerador es la construcción y mantenimiento del contexto.

La IA trabaja continuamente sobre:

- Arquitectura vigente.
- Decisiones técnicas tomadas.
- Evolución del diseño.
- Restricciones del proyecto.
- Documentación actualizada.
- Reglas de negocio.
- Aprendizajes acumulados.
- Patrones aplicables.
- Deuda técnica identificada.

El contexto se convierte en el activo principal del desarrollo.

---

# 12. Markdown-Driven Development

Los markdowns dejan de ser documentación secundaria.

Se convierten en:

- Fuente de contexto.
- Memoria del proyecto.
- Guía para la IA.
- Base de conocimiento.
- Mecanismo de alineación entre equipos.
- Registro de decisiones arquitectónicas.
- Insumo para generación asistida de código.
- Evidencia de evolución del diseño.

La documentación evoluciona junto con el código.

---

# 13. Scaffold Incremental

La solución se construye mediante ciclos iterativos:

1. Diseño.
2. Documentación.
3. Generación.
4. Validación.
5. Refinamiento.
6. Versionamiento.
7. Retroalimentación al contexto.

Cada iteración mejora tanto el software como el conocimiento documentado del proyecto.

---

# 14. Continuous Context Refinement

Cada nueva decisión arquitectónica, cambio funcional o aprendizaje debe incorporarse al contexto de forma controlada.

Esto evita:

- Deriva arquitectónica.
- Inconsistencias.
- Pérdida de conocimiento.
- Generación de código contradictorio.
- Repetición de errores.
- Desalineación entre equipos.
- Dependencia excesiva del conocimiento tácito.

---

# 15. Context Versioning

Todos los cambios relevantes del contexto deben ser versionados.

Ejemplo:

```text
/context
    architecture-v1.0.md
    architecture-v1.1.md
    architecture-v2.0.md
```

El contexto se trata como un activo de ingeniería, no como documentación secundaria.

Buenas prácticas:

- Versionar decisiones arquitectónicas.
- Registrar cambios relevantes.
- Mantener historial de evolución.
- Asociar cambios a decisiones, riesgos o necesidades de negocio.
- Evitar que la IA sobrescriba documentos fundacionales sin revisión.

---

# 16. Agentic Development Environment (ADE)

CDAD reconoce la aparición de una nueva categoría de herramientas:

## ADE — Agentic Development Environment

Un **Agentic Development Environment** es un entorno donde desarrolladores y agentes de IA colaboran utilizando contexto compartido, persistente y gobernado.

Esta categoría incluye herramientas conocidas como:

- Agentic IDEs.
- AI-Native IDEs.
- AI-First Code Editors.
- Agentic Coding Environments.

Ejemplos actuales:

- Kiro.
- Cursor.
- Windsurf.
- GitHub Copilot.
- Visual Studio Code con capacidades agentic.
- Otros entornos integrados con agentes, herramientas y contexto persistente.

---

## 14.1 Principios de un ADE compatible con CDAD

Un ADE compatible con CDAD debe permitir:

- Acceso controlado al contexto.
- Respeto por la gobernanza definida.
- Persistencia del conocimiento.
- Trabajo con múltiples agentes.
- Integración con repositorios documentales.
- Evolución continua del contexto.
- Trazabilidad de decisiones.
- Separación clara entre propuesta de cambio y aplicación de cambio.
- Capacidad de operar sobre código sin romper el marco arquitectónico.

---

## 14.2 Elección del IDE, IA y Stack de Trabajo

CDAD considera fundamental definir explícitamente el entorno de trabajo antes de iniciar la implementación.

Se debe decidir:

- IDE o ADE principal.
- Modelo de IA.
- Agentes disponibles.
- Herramientas de generación de código.
- Herramientas de documentación.
- Repositorio del contexto.
- Estrategia de versionamiento.
- Nivel de autonomía permitido a la IA.
- Límites de modificación sobre documentos y código.
- Flujo de revisión humana.

Ejemplo de definición:

```text
IDE/ADE:
Kiro / Cursor / Windsurf / VS Code

Modelo IA:
Claude / GPT / Gemini / modelo local / modelo corporativo

Repositorio de contexto:
Git

Documentos protegidos:
vision.md
architecture.md
principles.md
constraints.md

Nivel de autonomía:
L0 y L1 requieren aprobación humana.
L2 permite propuestas asistidas.
L3 permite generación y refactorización controlada.
```

---

# 17. AI-Assisted Delivery

Una vez definido y estabilizado el contexto, la generación de código se vuelve altamente eficiente.

La IA puede acelerar:

- Implementaciones.
- Refactorizaciones.
- Automatizaciones.
- Testing.
- Documentación.
- Diagramación.
- Generación de artefactos técnicos.
- Análisis de impacto.
- Revisiones técnicas.
- Generación de scripts.
- Creación de pruebas.
- Preparación de despliegues.

En esta etapa, gran parte de la implementación puede transformarse en lo que actualmente se conoce como **Vibe Coding**, pero respaldado por un marco de trabajo sólido, contexto gobernado y arquitectura controlada.

---

# 18. Vibe Coding Controlado

CDAD no rechaza el Vibe Coding.

Lo reubica correctamente.

El Vibe Coding puede ser útil cuando existe:

- Arquitectura clara.
- Contexto definido.
- Reglas de negocio documentadas.
- Restricciones técnicas conocidas.
- Gobernanza del contexto.
- Criterios de validación.
- Revisión humana.

Sin estos elementos, el Vibe Coding puede derivar en soluciones inconsistentes, difíciles de mantener o alejadas de la arquitectura objetivo.

Con CDAD, el Vibe Coding se convierte en una fase de aceleración, no en el fundamento del desarrollo.

---

# 19. Fórmula CDAD

```text
Architecture
+
Knowledge
+
Governed Context
+
Agentic Development Environment
+
AI
=
Sustainable Accelerated Development
```

Versión extendida:

```text
Arquitectura
+
Contexto Gobernado
+
Conocimiento del Dominio
+
Markdowns Versionados
+
Agentes de IA
+
Revisión Humana
=
Desarrollo Acelerado, Controlado y Sostenible
```

---

# 20. Regla de Oro CDAD

> La IA puede sugerir.  
> La IA puede analizar.  
> La IA puede proponer.  
> La IA puede acelerar.  
> Pero la IA no puede redefinir la arquitectura sin aprobación explícita del Diseñador de la Solución.

---

# 21. Diferenciación Frente a Otros Enfoques

CDAD no es solamente Prompt Engineering.

CDAD no es solamente Vibe Coding.

CDAD no es solamente usar un AI Coding Assistant.

CDAD propone un modelo más completo:

- Context Engineering para construir el contexto.
- Governance of Context para controlarlo.
- Context Protection Pattern para protegerlo.
- Markdown-Driven Development para mantenerlo vivo.
- Agentic Development Environment para ejecutarlo.
- AI-Assisted Delivery para acelerar la implementación.

---

# 22. Roadmap de Evolución

## Fase 1 — Fundamentos

- Context Engineering.
- Markdown-Driven Development.
- Governance of Context.
- Context Protection Pattern.
- Continuous Context Refinement.

## Fase 2 — Madurez Técnica

- Context Versioning.
- Architecture Memory.
- Context as Code (CaC).
- Architecture as Context (AaC).
- AI Coding Standards.
- AI Review Patterns.

## Fase 3 — Desarrollo Agéntico

- Agentic Development Lifecycle.
- Multi-Agent Collaboration.
- MCP Integration Patterns.
- Agentic Development Environment.
- Tooling Strategy.
- Human-in-the-Loop Governance.

## Fase 4 — Escala Empresarial

- Enterprise CDAD.
- Organizational Knowledge Memory.
- AI-Native Architecture.
- Autonomous Delivery Pipelines.
- AI Governance Framework.
- Continuous Architecture Validation.

---

# 23. Principio Final

La calidad del resultado generado por la IA depende directamente de la calidad, consistencia, protección y continuidad del contexto que la gobierna.

La IA no reemplaza la arquitectura.  
La IA no reemplaza el diseño.  
La IA no reemplaza la experiencia.  

La IA acelera la ejecución de una arquitectura correctamente definida.

---

# 24. Frase Central

> **Context is the new Source Code.**

En CDAD, el contexto no es documentación auxiliar.

El contexto es el fundamento que gobierna la solución.

---

# Licencia

Este documento se distribuye bajo la licencia:

Creative Commons Attribution 4.0 International (CC BY 4.0)

https://creativecommons.org/licenses/by/4.0/

Copyright © 2026 Moisés Griott

Se permite copiar, distribuir, adaptar y reutilizar este trabajo, incluyendo usos comerciales, siempre que se mantenga la atribución correspondiente al autor original.