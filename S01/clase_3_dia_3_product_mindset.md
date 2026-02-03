# Clase 3 (Día 3): Product Mindset y Discovery

**Instructores**: Equipo Tech Rebel - Producto

---

## Tema 8: Planeando Arquitecturas (Creative Architecture Design)

**Instructor**: Araya2001
**Repo**: https://github.com/Araya2001/creative-architecture-design

### Filosofía: El Proceso de Diseño Creativo

#### Definiciones Base

**Diseño** (RAE, Punto 3):
> Concepción original de un objeto u obra destinados a la producción en serie.

**Creativo** (RAE, Punto 2):
> Capaz de crear algo.

### ¿Qué Sucede con el Diseño de Arquitectura de Software?

#### Situación Actual
- Software = componente clave en monetización
- Grandes corporaciones dominan la monetización
- Parámetros de producción se vuelven rígidos

#### Comportamiento en Corporaciones
- Parámetros restrictivos para garantizar producción
- Estructuras y jerarquías organizacionales
- Controles estrictos basados en data histórica

#### Impacto en Developers
- Desarrolladores/agentes como componente de producción
- Parámetros se vuelven cíclicos y repetitivos
- **No se parametriza para lidiar con ambigüedad**
- Limitación a producir dentro de parámetros restrictivos

### ¿Dónde Entra la Creatividad?

**Como Builders**:
- Diseño = concepto **original**
- Nos apoyamos en **patrones** que brindan resultados específicos
- Similitud ≠ identidad (cada concepto es único)

### Apelando a la Creatividad

**Fuentes**:
- 🎨 Arte
- ❤️ Pasión
- 👥 Interacciones genuinas
- 🎯 Hobbies
- 🧘 Respeto a límites
- 🔄 Capacidad de adaptación

**Impacto**:
- Hábito de intentar cosas nuevas
- Experimentar y aprender de errores
- Tiempo, práctica y dedicación
- Alimentado por experiencia, curiosidad y perseverancia
- Generar ideas innovadoras en situaciones complejas

---

## Estrategia: Divide & Conquer

### ¿Qué es?

Técnica de resolución de problemas que **divide un problema complejo en subproblemas más pequeños y manejables**.

### Aplicación Real

**Problemas complejos no son solo de software**:
- Temas de comunicación
- "Analysis Paralysis" (parálisis por análisis)

### Evitar Analysis Paralysis

**Señales**:
- Sobre-análisis sin acción
- Indecisión por exceso de opciones
- Miedo a equivocarse
- Búsqueda de la solución perfecta

**Solución**: Dividir, ejecutar, iterar.

---

## Herramientas y Recomendaciones

### Herramientas para Facilitar el Proceso

#### Digitales
- **draw.io**: Diagramas y arquitectura
- **Kanban Boards**: Jira, Asana

#### Pruebas de Concepto
- Implementación a pequeña escala
- Validar ideas rápidamente

### Herramientas Analógicas (Fomentan Creatividad)

- ✏️ **Lápiz y papel**
- 🖍 **Pizarras**

**Por qué funcionan**:
> Escribir a mano = clave para un cerebro más inteligente  
> Fuente: https://udesa.edu.ar/noticias/escribir-mano-la-clave-para-un-cerebro-mas-inteligente

### Herramientas para Velocidad y Agilidad

#### Workflow con LLM

```
1. Requisitos y success criteria en prosa
   ↓
2. LLM estructura requisitos
   ↓
3. Requisitos estructurados
   ↓
4. LLM genera diagramas con Mermaid
   ↓
5. Diagramas Mermaid
   ↓
6. draw.io para refinar
```

---

## Recomendaciones de Lecturas

1. **Team Topologies, 2nd Edition**
2. **Designing Data-Intensive Applications**
3. **Learning Domain-Driven Design**
4. **Design Patterns: Elements of Reusable Object-Oriented Software**
5. **How LLMs Work**: https://joseparreogarcia.substack.com/p/how-llms-work-part-1-the-3-essential-layers

---

## Tema 9: Buscando Problemas (Problem Discovery)

### Principio Fundamental

> "Antes de construir la solución correcta, hay que estar seguro de que el problema existe."

### Conexión con Arquitectura

**Paralelismo**:

| Arquitectura | Producto |
|--------------|----------|
| Diagrama de sistema | Mapa del problema |
| Feedback técnico | Feedback de usuarios/expertos |
| Iterar antes de codear | Iterar antes de construir |
| Cambiar diagrama es barato | Pivotear en papel es gratis |

> 👉 Un problema también se puede dibujar, explicar y criticar.

---

## El Mejor Consejo para Encontrar Problemas

### "Fuck Around and Find Out"

**Por qué es honesto**:
- Nadie "piensa" el problema correcto desde cero
- Los problemas **emergen cuando empezás a construir**

**Qué pasa cuando empezás**:
- Aparecen fricciones
- Conocés gente con problemas similares
- Descubrís soluciones parciales
- Entendés qué cosas no importan

> No encontrás el problema antes de empezar.  
> **Empezar es lo que te revela el problema.**

**Aplica a**:
- Startups
- Side projects
- Open source
- Hackathons

---

## El Pivote: Barato en Papel, Caro en Producción

**Costos de pivotear**:
- Empresa con usuarios → 💰💰💰 Caro
- Producto en producción → 😰 Doloroso
- Idea en un cuaderno → ✅ Trivial

> 👉 Esta etapa existe para **equivocarse rápido y barato**.

---

## Qué es (y Qué NO es) un Problema Real

### Error Común en Equipos Técnicos

Empezar por la **solución** sin un **problema real**.

### Un Producto Debe Ser

```
┌─────────────┐
│   VALIOSO   │  ← ¿Alguien lo necesita?
└──────┬──────┘
       │
┌──────▼──────┐
│    VIABLE   │  ← ¿Alguien paga?
└──────┬──────┘
       │
┌──────▼──────┐
│  FACTIBLE   │  ← ¿Podemos construirlo?
└──────┬──────┘
       │
┌──────▼──────┐
│   USABLE    │  ← ¿El usuario puede usarlo?
└─────────────┘
```

### 1. Usable (UX)

- Usuario puede usarlo
- Idioma, contexto, hábitos
- Responsabilidad de diseño

### 2. Factible (Tecnología)

- ¿Podemos construirlo con este equipo?
- ¿Tenemos capacidades técnicas?
- ¿El stack lo permite?

### 3. Viable (Negocio)

- ¿Alguien paga?
- ¿Quién es el cliente?
- ¿Es sostenible?

### 4. Valioso (Foco de esta Clase)

**Pregunta clave**:
> ¿Hay alguien con un problema cuya solución sea lo suficientemente valiosa?

**Importante**: El usuario no siempre paga.

**Ejemplos de pagadores**:
- ONG
- Fundaciones
- Gobiernos
- Modelos B2B2C

> 👉 Pero **alguien tiene que pagar** porque el problema importa.

---

## Los Problemas También Se Pueden Diagramar

### Mapa Simple de Problema

```
┌─────────────────────────────────┐
│ PERSONA:                        │
│ [Quién tiene el problema]       │
├─────────────────────────────────┤
│ CONTEXTO:                       │
│ [Cuándo/dónde ocurre]          │
├─────────────────────────────────┤
│ PROBLEMA:                       │
│ [Qué pasa exactamente]         │
├─────────────────────────────────┤
│ SOLUCIÓN ACTUAL:                │
│ [Cómo lo resuelve hoy]         │
├─────────────────────────────────┤
│ FRUSTRACIÓN PRINCIPAL:          │
│ [Qué es lo que más duele]      │
├─────────────────────────────────┤
│ COSTO DEL PROBLEMA:             │
│ [Qué pierde si no se soluciona]│
└─────────────────────────────────┘
```

> 👉 Esto se puede enseñar a alguien que tenga ese problema y pedir feedback.

---

## Reference Customers / Reference Clients

### ¿Qué es un Reference Customer?

Alguien que:
- ✅ Tiene el problema
- ✅ Está dispuesto a:
  - Escuchar ideas incompletas
  - Probar algo en construcción
  - Dar feedback honesto
  - Tener paciencia

**No es un cliente tradicional. Es un partner de aprendizaje.**

### Por Qué Son Críticos

- Validan si el problema es real
- Ayudan a priorizar
- Reducen riesgo temprano

> 👉 En early stage no se escala sin reference customers.

---

## ¿Y Si No Tengo Clientes? Expertos de Industria

**Si no tenés acceso directo a usuarios**:
- Necesitás **expertos del dominio**

**Ejemplos**:
- Turismo → alguien de la industria turística
- Fintech → alguien que viva fintech
- Legal → alguien del sistema legal

### Regla Práctica

> Esa persona debería poder mostrar tu idea a **al menos 3 personas reales**.

**Si no puede**:
- No tiene acceso
- No entiende el mercado
- No es el perfil correcto

---

## El Mundo Está Lleno de Data (Incluso el Silencio)

**Todo es data**:
- Nadie usa tu producto → data
- Nadie responde → data
- Nadie paga → data
- Nadie deposita fondos → data

**Nuestro trabajo en etapas tempranas**:
- 📊 Interpretar señales
- 🚫 No enamorarnos de la solución
- 🔄 Ser flexibles y aprender rápido

---

## Pasión por el Problema (No por la Solución)

> Esto no es romanticismo, es realismo.

**Realidad**:
- Llevar un producto de 0 a 1 es largo y duro
- Requiere convicción, energía y enfoque
- Por eso se habla de "enamorarse del problema"

**Incluso si el problema es "aburrido"**:
- Escrow
- Pagos
- Contabilidad
- Compliance

> 👉 Justamente por ser "aburridos", suelen esconder **grandes oportunidades**.

---

## Tema 10: Problem Discovery Canvas

### Propósito del Canvas

> Entender un problema antes de construir una solución.  
> No busca validar ideas, busca validar que **el problema existe y duele**.

---

### 1. Persona / Actor

**¿Quién tiene el problema?**

- Rol:
- Industria:
- Contexto (empresa, país, tamaño, madurez):
- ¿Es usuario, cliente o influencer de decisión?

---

### 2. Contexto del Problema

**¿Cuándo y dónde ocurre?**

- Momento en el que aparece:
- Frecuencia:
- Qué estaba intentando hacer:
- Qué lo detona:

---

### 3. El Problema

**Descríbelo sin mencionar tu solución**

- Qué pasa exactamente:
- Por qué es frustrante:
- Qué consecuencias tiene:
- Qué tareas se ven afectadas:

> ❗ Regla: Si podés describir el problema sin tecnología, vas bien.

---

### 4. Solución Actual (si existe)

**¿Cómo lo resuelve hoy?**

- Herramientas actuales:
- Workarounds manuales:
- Procesos internos:
- Alternativas del mercado:

---

### 5. Frustración Principal

**¿Qué es lo que más duele?**

- Qué es lento:
- Qué es caro:
- Qué es confuso:
- Qué genera estrés o riesgo:

---

### 6. Costo del Problema

**¿Qué pierde la persona si no se soluciona?**

- Tiempo:
- Dinero:
- Oportunidades:
- Riesgo:
- Reputación:

---

### 7. Importancia del Problema

**¿Qué tan prioritario es?**

- 🔲 Crítico (lo tiene que resolver ya)
- 🔲 Importante (le molesta mucho)
- 🔲 Nice-to-have (no es urgente)

**¿Qué pasa si no lo resuelve este año?**

---

### 8. Stakeholders Involucrados

**¿Quién más está afectado?**

- Otros equipos:
- Clientes finales:
- Proveedores:
- Reguladores:
- Partners:

---

### 9. Early Signals (Data Temprana)

**¿Qué señales indican que el problema es real?**

- Quejas frecuentes
- Procesos manuales repetidos
- Uso de Excel / WhatsApp / Emails
- Silencio o falta de adopción
- Errores recurrentes

---

### 10. Reference Customer / Expert

**¿Con quién validarías este problema?**

- Nombre / Rol:
- Relación contigo:
- ¿Es cliente, experto o partner?
- ¿Puede mostrar esta idea a otras personas?

> **Regla práctica**: Si no puede llevar tu problema a 3 personas reales, no es buen validador.

---

### 11. Hipótesis de Valor (sin solución)

**Si este problema se resolviera…**

- ¿Qué cambiaría en su día a día?
- ¿Por qué sería valioso?
- ¿Quién estaría dispuesto a pagar (y por qué)?

---

### 12. Próximo Paso de Validación

**Acción concreta para esta semana**

- ¿A quién se lo voy a mostrar?
- ¿Qué quiero aprender?
- ¿Qué invalidaría este problema?

---

### Estado del Problema

- 🔲 Hipótesis
- 🔲 Validado con expertos
- 🔲 Validado con usuarios
- 🔲 No es un problema real
- 🔲 Problema confirmado, listo para explorar soluciones

---

## Tema 11: ¿Qué Problema Resuelve Blockchain?

### Concepto Fundamental

> Blockchain no es una tecnología para hacer cosas nuevas.  
> Es una tecnología para hacer posibles cosas que antes requerían **intermediarios de confianza**.

---

## Empezar por la Pregunta Correcta

### ❌ Pregunta Mal Planteada

"¿Cómo uso blockchain para este producto?"

### ✅ Pregunta Correcta

> ¿Qué problema existe aquí que solo puede resolverse con un **protocolo de confianza compartida**?

**Recordar**:
- Blockchain NO es una base de datos nueva
- Es una forma distinta de **coordinar actores que no confían entre sí**

---

## Blockchain Como Protocolo de Confianza

### Históricamente, la Confianza Requería Intermediarios

**Ejemplos**:
- Bancos
- Gobiernos
- Notarios
- Cámaras de compensación
- Plataformas centralizadas

**Estos intermediarios**:
- Custodian datos
- Definen reglas
- Ejecutan procesos
- Resuelven disputas

### Blockchain Introduce Alternativa

- Libro compartido entre múltiples actores
- Reglas verificables por código
- Ejecución automática sin entidad única

> 👉 En esencia, blockchain **reduce el costo de coordinar confianza**.

---

## El Núcleo del Problema: La Confianza

**Antes de pensar en blockchain, preguntate**:

1. ¿Quiénes son los actores involucrados?
2. ¿Confían entre sí?
3. ¿Qué pasa si uno hace trampa?
4. ¿Quién controla hoy los datos y las reglas?

**Si**:
- Hay un solo actor
- No hay conflicto de intereses
- Todos confían en una entidad central

> 👉 Entonces blockchain **probablemente no aporta valor**.

---

## Casos de Uso Donde Blockchain Aporta Valor

### 1. Acceso a Productos Financieros (DeFi)

**Problema real**:
- Productos financieros monopolizados
- Barreras geográficas y regulatorias
- Altos mínimos de capital
- Custodia y reglas opacas

**Qué habilita blockchain**:
- Acceso programático a productos financieros
- Custodia propia
- Reglas transparentes
- Menos intermediarios

> 👉 El valor está en **democratizar acceso y confianza**.

---

### 2. Pagos Cross-Border

**Problema**:
- Transferencias lentas
- Múltiples intermediarios
- Altas comisiones
- Falta de visibilidad

**Qué cambia**:
- Movimiento directo de valor
- Liquidación casi inmediata
- Menos fricción

> 👉 No elimina todos los problemas (regulación sigue existiendo), pero reduce fricción estructural.

---

### 3. Marketplaces Como Sistemas Financieros

**Tradicionalmente**:
- Custodian pagos
- Definen reglas
- Resuelven conflictos
- Dependen de Stripe, Visa, PayPal

**Qué habilita blockchain**:
- Custodia programática (escrow)
- Menos dependencia de intermediarios
- Plataformas operan como su propio sistema financiero

> 👉 Cada marketplace puede convertirse en su **propio banco**.

---

### 4. Supply Chain y Trazabilidad

**Problema**:
- Múltiples actores
- Sistemas desconectados
- Datos inconsistentes
- Auditorías costosas

**Qué aporta blockchain**:
- Fuente única de verdad
- Acceso compartido a datos
- Trazabilidad end-to-end

**Útil cuando**:
- Hay consorcios
- Existen certificaciones
- Se requiere auditoría

---

### 5. Aduanas y Comercio Internacional

**Problema**:
- Fricción entre países
- Duplicación de información
- Procesos manuales
- Falta de visibilidad

**Qué habilita**:
- Estados compartidos entre gobiernos
- Integración entre aduanas
- Trazabilidad desde materia prima hasta consumidor

> 👉 Blockchain coordina **actores soberanos que no confían plenamente entre sí**.

---

## Cuándo NO Usar Blockchain

**Ejemplos de sobreingeniería**:
- ❌ Inventarios internos
- ❌ Apps con un solo actor
- ❌ Bases de datos privadas
- ❌ Procesos sin conflicto de intereses

> 👉 Si una base de datos centralizada resuelve el problema, **úsala**.

---

## Blockchain No Crea Demanda

**Clave para entender**:

- ❌ Blockchain NO resuelve regulación
- ❌ Blockchain NO crea usuarios
- ❌ Blockchain NO valida productos

> 👉 Solo **reduce el costo de la confianza**.

**Si nadie quiere la solución**:
- Con blockchain → 💩
- Sin blockchain → 💩

> El producto sigue siendo malo.

---

## Cómo Identificar Problemas Solucionables con Blockchain

### Secuencia Sana de Pensamiento

```
1. Identificar problema real
   ↓
2. Entender la fricción
   ↓
3. Detectar problema de confianza
   ↓
4. Evaluar si blockchain reduce costos/riesgo
   ↓
5. Validar demanda con personas reales
```

> **Blockchain es un medio, no un fin.**

---

## Tema 12: Product Mindset

### ¿Qué es el Product Mindset?

**Definición**: Forma de pensar y operar que prioriza:

- 📚 **Aprender** antes de decidir
- 🏗 **Construir** para aprender, no para perfeccionar
- 🚀 **Lanzar** temprano para obtener señales reales
- 📊 **Medir** para reducir incertidumbre
- 🎯 **Liderar** con claridad, principios y narrativa

> Un producto no es algo que se construye una vez.  
> Es algo que se **aprende, se ajusta y se lidera continuamente**.

---

## Confiar en el Proceso, No en el Plan

### Cambio Mental Clave

- ❌ No confiamos en el plan
- ✅ Confiamos en el proceso

**Por qué**:
- Los planes asumen certeza
- El producto vive en incertidumbre
- La única forma de reducir incertidumbre es **interactuar con la realidad**

**El Product Mindset abraza**:
- Flexibilidad
- Adaptabilidad
- Resiliencia

> **Pivotear no es fallar. Pivotear es aprender.**

---

## Los Cinco Pilares del Product Mindset

```
   ┌─────────────┐
   │   LIDERAR   │
   └──────┬──────┘
          │
    ┌─────┴─────┐
    │           │
┌───▼───┐   ┌───▼───┐
│ MEDIR │◄──┤ LANZAR│
└───┬───┘   └───┬───┘
    │           │
    └─────┬─────┘
          │
    ┌─────▼─────┐
    │  CONSTRUIR│
    └─────┬─────┘
          │
    ┌─────▼─────┐
    │  APRENDER │
    └───────────┘
```

**No es un proceso lineal. Es un ciclo continuo.**

---

## 1. Aprender

**Por qué primero**: Todo producto empieza con desconocimiento.

**Prácticas**:
- Discovery de producto
- Investigación de usuarios
- Entrevistas
- Jobs to Be Done
- Empathy drills
- Formular hipótesis
- Definir problemas
- Propuesta de valor

**Preguntas clave**:
- ¿Qué no sabemos?
- ¿Qué estamos asumiendo?
- ¿Por qué este problema existe?
- ¿Por qué se resuelve así hoy?

> Aprender no es acumular información, es **reducir riesgo**.

---

## 2. Construir

**Concepto**: Construir no es ejecutar una idea perfecta. Es **materializar hipótesis**.

**Incluye**:
- MVP (Minimum Viable Product)
- Scope consciente
- Product Blueprint
- Prototipos
- Loops de experimentación

**Un buen MVP**:
- ✅ Es pequeño
- ✅ Es feo
- ✅ Es rápido
- ✅ Enseña algo

> 👉 Si el MVP no te incomoda, probablemente es demasiado grande.

---

## 3. Lanzar

**Importancia**: Tan importante como aprender y construir.

**Sin lanzamiento**:
- ❌ No hay data
- ❌ No hay señales
- ❌ No hay realidad

**Incluye**:
- Estrategias de go-to-market
- Identificación de señales
- Canales
- Messaging
- Founder-led growth
- Experimentos de growth

> **El mercado es el mejor crítico de producto.**

---

## 4. Medir

**Concepto**: Convertir el lanzamiento en aprendizaje.

**En etapas tempranas, medir es**:
- Feedback
- Uso
- Rechazo
- Silencio

**Todo es data.**

**Preguntas clave**:
- ¿Qué funcionó?
- ¿Qué no?
- ¿Qué aprendimos?
- ¿Qué cambiaríamos?

> 👉 Medir sirve para **decidir mejor**, no para justificar decisiones pasadas.

---

## 5. Liderar

**Por qué es necesario**: El Product Mindset necesita liderazgo.

**Responsabilidades**:
- Alguien sostiene el ciclo
- Alguien protege el proceso
- Alguien mantiene la narrativa

**Puede ser**:
- El founder
- El CTO
- El CPO
- El líder de producto

---

## Liderar es Narrativa

**Todo producto cuenta una historia**:
- Hay decisiones que fortalecen la narrativa
- Hay decisiones que la debilitan

**La narrativa**:
- Alinea al equipo
- Da contexto
- Da sentido a los pivotes

> Construir un producto es también **construir un documental en tiempo real**.

---

## Feedback Directo y Ciclos Cortos

**El Product Mindset valora**:
- Feedback honesto
- Feedback temprano
- Feedback directo

**No es ser agresivo, es respetar el tiempo y la verdad.**

**Los ciclos deben ser**:
- Cortos
- Baratos
- Repetibles

> 👉 Cada ciclo **reduce incertidumbre**.

---

## Alinear con Producto Real

**Objetivo claro**: Construir algo que sea:

```
┌─────────────┐
│   VALIOSO   │
├─────────────┤
│    VIABLE   │
├─────────────┤
│  FACTIBLE   │
├─────────────┤
│   USABLE    │
└─────────────┘
```

**Si uno de estos falla, el producto falla.**

---

## Ejercicio Práctico: Mapear un Problema

### Instrucciones

1. **Elegí una idea** (aunque no sea buena)

2. **Respondé**:
   - ¿Quién tiene el problema?
   - ¿Cuál es el problema?
   - ¿Cómo lo resuelve hoy?
   - ¿Por qué duele?

3. **Dibujá una posible solución**

4. **Pensá**:
   - ¿A quién se lo mostraría?
   - ¿Es cliente o experto?

5. **Definí el próximo paso**:
   - ¿A cuántas personas se lo mostrarías esta semana?

> **Objetivo**: No validar la solución, validar el problema.

---

## Resumen Clave Día 3

### Creative Architecture Design
- Divide & Conquer para evitar analysis paralysis
- Creatividad alimentada por arte, pasión, interacciones genuinas
- Herramientas: análogas (lápiz/papel) y digitales (draw.io, LLMs)
- Lecturas recomendadas: Team Topologies, DDD, Design Patterns

### Problem Discovery
- "Fuck around and find out" - empezar revela el problema
- Pivotear en papel es gratis, en producción es caro
- Producto debe ser: Valioso, Viable, Factible, Usable
- Reference customers son partners de aprendizaje
- Todo es data (incluso el silencio)

### Problem Discovery Canvas
- Herramienta para validar problemas antes de construir
- Describe problema sin mencionar solución
- Identifica reference customers y expertos
- Define próximos pasos de validación

### ¿Qué Resuelve Blockchain?
- No crea demanda, reduce costo de confianza
- Casos válidos: DeFi, pagos cross-border, marketplaces, supply chain, aduanas
- No usar cuando hay un solo actor o entidad central confiable
- Blockchain es medio, no fin

### Product Mindset
- 5 pilares: Aprender, Construir, Lanzar, Medir, Liderar
- Confiar en el proceso, no en el plan
- Pivotear es aprender, no fallar
- MVP debe incomodar (si no, es demasiado grande)
- Liderar es construir y mantener narrativa

---

## Cierre de la Clase 3

> "Así como no construimos sistemas sin feedback técnico,  
> no deberíamos construir productos sin feedback del problema.  
>  
> **El producto empieza antes del código.**"

---

> "El Product Mindset no es una metodología.  
> Es una forma de pensar, decidir y liderar bajo incertidumbre.  
>  
> No se trata de tener razón desde el inicio.  
> Se trata de **aprender más rápido que los demás**."
