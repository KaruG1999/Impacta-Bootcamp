# Clase 2 (Día 2): Stellar y Smart Contracts

---

## Tema 6: Intro a Stellar

### ¿Qué es Stellar?

**Definición**: Red blockchain diseñada para mover valor de forma rápida, barata y confiable.

**Enfoque**: Pagos, stablecoins y sistemas financieros globales.

> No es una plataforma generalista para "hacer de todo", sino **infraestructura financiera**.

### El Origen de Stellar

**Fundadores** (2014):
- Jed McCaleb (cofundador de Ripple/XRP)
- Joyce Kim

**Objetivo original**:
> Crear un sistema financiero abierto que permita mover dinero como se mueve información en internet.

**Problemas que buscó resolver**:
- Transferencias internacionales lentas y caras
- Exclusión financiera
- Dependencia de intermediarios
- Fricción en pagos transfronterizos

### Relación con XRP (y la Ruptura)

**Similitudes**:
- Ambos buscan pagos rápidos
- Ambos usan consenso sin minería
- Ambos priorizan eficiencia y bajo costo

**Diferencia clave**:
- **XRP**: Evolucionó hacia modelo más corporativo
- **Stellar**: Camino open, neutral y **not-for-profit**

> Esa ruptura definió el ADN de Stellar.

---

## Stellar Consensus Protocol (SCP)

### Modelo de Consenso Distinto

**NO usa**:
- ❌ Proof of Work (minería)
- ❌ Proof of Stake tradicional

**SÍ usa**:
- ✅ **Consenso federado** basado en quorum slices

### ¿Cómo funciona?

**En términos simples**:
- Cada nodo elige a quién confiar
- El consenso emerge de la superposición de confianza
- No hay mineros
- No hay competencia por bloques

### Ventajas de SCP

- ⚡ **Rápido**: Segundos
- 💰 **Muy barato**: Costos extremadamente bajos
- 🌱 **Energéticamente eficiente**: Sin minería
- 📊 **Predecible**: Comportamiento consistente

---

## Stellar Development Foundation (SDF)

### Una Fundación Sin Fines de Lucro

**Características de SDF**:
- 🎯 **Not-for-profit**: No busca maximizar ingresos
- 🔓 **No es empresa tradicional**
- 🌍 **Enfoque**: Crecimiento del ecosistema

### Rol Principal

- 🛠 Mantener el protocolo
- 💰 Financiar proyectos
- 👥 Apoyar desarrolladores
- 📈 Impulsar adopción real

**Alineamiento único**:
```
Red ↔ Ecosistema ↔ Usuarios ↔ Builders
```

---

## Diferencia con Ethereum

Ethereum y Stellar **no compiten directamente** — resuelven problemas distintos.

| Característica | Ethereum | Stellar |
|----------------|----------|---------|
| **Tipo** | Plataforma generalista | Infraestructura financiera |
| **Enfoque** | Aplicaciones complejas | Pagos y stablecoins |
| **Flexibilidad** | Altamente flexible | Enfocada |
| **Costos** | Más costosa | Extremadamente bajos |
| **Velocidad** | Más fricción para pagos | Alta velocidad |
| **Ideal para** | DApps complejas | Productos financieros |

### Analogía Simple

> **Ethereum** = Computadora global  
> **Stellar** = Red financiera global

---

## Smart Contracts en Stellar

### Evolución del Enfoque

**Durante muchos años, Stellar se enfocó en**:
- Pagos
- Assets
- Trustlines
- Liquidez

**Recientemente**: Lanzó plataforma de smart contracts con enfoque distinto.

### Filosofía de Diseño

- **No busca copiar EVM** (Ethereum Virtual Machine)
- **Busca**: Seguridad, previsibilidad y eficiencia

### ¿Qué Permiten?

Los smart contracts en Stellar permiten:
- 💼 Lógica financiera
- 🤖 Automatización de flujos
- 🔐 Custodia programable
- 👥 Roles y permisos
- 🏗 Infraestructura para productos financieros

### Casos de Uso Habilitados

- Escrows
- Sistemas de puntos
- Programas de incentivos
- Productos B2B y B2B2C
- Infraestructura para stablecoins

---

## El Enfoque Histórico de Stellar

Stellar nunca ha sido una red "de moda".

**Su enfoque siempre ha sido**:
- 🏗 Infraestructura
- 💳 Pagos reales
- 🏦 Integraciones con mundo financiero
- 💵 Stablecoins
- ✅ Casos de uso en producción

### Ecosistema Típico

- On-ramps y off-ramps
- Wallets enfocadas en pagos
- Integraciones con empresas
- Casos de uso en países emergentes

---

## Beneficios Clave de Stellar

1. ⚡ **Transacciones casi instantáneas**
2. 💰 **Costos extremadamente bajos**
3. 🌱 **Modelo energético eficiente**
4. 💵 **Ideal para stablecoins**
5. 🏗 **Arquitectura clara y enfocada**
6. 🌍 **Ecosistema alineado a casos reales**

---

## ¿Por Qué Construir sobre Stellar?

Stellar es especialmente interesante si estás construyendo:

- 💼 Productos financieros
- 💳 Sistemas de pagos
- 💵 Infraestructura de stablecoins
- 🛒 Marketplaces
- 🔐 Escrows
- 🎯 Programas de incentivos
- 🏢 Productos B2B o B2B2C

> Es una red pensada para **productos**, no solo para experimentos.

---

## Idea Clave

> Stellar no es una blockchain "espectacular".  
> Es una blockchain **confiable**.  
>  
> Y en productos financieros,  
> **confiable siempre gana**.

---

# Tema 7: Smart Contracts - Estándares y Herramientas

**Instructor**: Matías Aguilar (@aguilar1x)
- Full Stack Web3
- Smart Contract Developer
- Co-founder nEKO protocol

---

## Introducción a Smart Contracts

### ¿Qué son los Smart Contracts?

**Definición**: Código que se ejecuta en una blockchain, viviendo en ella para cumplir diferentes funciones dependiendo de su contexto de creación.

### ¿Qué es Soroban?

**Definición**: Motor de contratos inteligentes de Stellar.

**Características**:
- Basado en **Rust**
- Usa **WebAssembly (WASM)**
- Permite ejecutar lógica avanzada en Stellar

### ¿Qué es WASM (WebAssembly)?

**Definición**: Formato binario diseñado para ejecutar código de manera muy rápida.

**Beneficio**: Contratos se ejecutan de forma **segura y rápida**.

---

## Buenas Prácticas

### 1. Seguridad

**Consideraciones**:
- ✅ Evitar overflow o underflows
- ✅ Controlar acceso (Admins, Users)
- ✅ Respetar estándares SEP
- ✅ No guardar información innecesaria en storage

### 2. Diseño

**Principios**:
- 📦 Contratos modulares por capas (mod)
- 📢 Eventos claros
- 💾 Storage explícito
- 🔄 Pensar en migraciones

### 3. Testing y Costos

**Prácticas**:
- 🧪 Unit tests
- 🎭 Simular escenarios adversos
- 💰 Minimizar uso de storage
- 🔁 Evitar loops innecesarios
- ⚡ Optimizar llamadas

---

## Estándares SEP (Stellar Ecosystem Proposals)

### SEP-0001: Stellar Info File

**Función**: Puente con contratos.

**Uso**: Discovery de servicios (anchors, wallets, dapps) que luego interactúan con contratos Soroban.

### SEP-0040: Soroban Token Interface

**Función**: Estándar para tokens en Soroban.

**Importancia**: Esencial para interoperabilidad entre tokens.

### SEP-0041: Oracle Consumer Interface

**Función**: Puente con contratos.

**Uso**: Define cómo consumir datos externos confiables (oracles).

### SEP-0046: Contract Meta

**Función**: Metadatos estandarizados de contratos.

**Uso**: Para tooling, UIs y auditoría.

### SEP-0048: Contract Interface Specification

**Función**: Especifica cómo describir interfaces.

**Uso**: Base para tooling y Developer Experience (DX).

---

## CAP (Core Advancement Proposals)

### CAP-0046: Soroban Smart Contract System

**Visión general del sistema de smart contracts**.

### CAP-0046-01: WebAssembly Runtime Environment

**Runtime WASM** para contratos inteligentes.

### CAP-0046-02: Fee Model in Smart Contracts

**Modelo de fees** en Soroban.

### CAP-0046-07: Smart Contract Lifecycle

**Ciclo de vida del contrato** (deploy, invoke, upgrade).

### CAP-0046-11: Soroban Authorization Framework

**Autorización y firmas** en contratos.

---

## ¿Qué Cambia para Developers?

> "Ok, existen los estándares… pero ¿qué cambia para nosotros como developers?"

**Respuesta**:
- 📚 **Interoperabilidad**: Tus contratos funcionan con otros del ecosistema
- 🛠 **Tooling mejorado**: Herramientas entienden tus contratos
- 🔒 **Seguridad**: Patrones probados reducen riesgos
- 📖 **Documentación consistente**: Más fácil de entender y usar
- 🤝 **Colaboración**: Equipos hablan el mismo lenguaje

---

## OpenZeppelin

### ¿Qué es OpenZeppelin?

> El punto de partida ideal para cualquier smart contract: código auditado, seguro y modular listo para extender.

### ¿Por Qué Usar OpenZeppelin?

#### 1. Implementaciones Auditadas 🔒

- Contratos revisados por expertos
- Probados y confiables
- Te evita reinventar lógica crítica
- Reduce riesgos

#### 2. Buenas Prácticas de Diseño 📐

- Código modular, legible y consistente
- Sigue estándares del ecosistema
- Contratos limpios y mantenibles

#### 3. Seguridad Reforzada 🛡️

- Incluye módulos como Pausable, ReentrancyGuard, roles
- Protegen contra vulnerabilidades comunes

#### 4. Contratos Estándares Listos 🚀

- Plantillas para tokens, gobernanza, permisos y más
- Bloques listos que aceleran desarrollo

---

## Módulos de OpenZeppelin

### 1. Access Control 🔐

**Gestión de roles y permisos**:
- Ownable
- AccessControl
- Roles

### 2. Tokens 🪙

**Implementaciones estándar**:
- Tokens fungibles
- Tokens no fungibles (NFTs)

### 3. Security 🛡️

**Módulos de protección**:
- Pausable
- ReentrancyGuard
- Timelocks

### 4. Compliance ⚖️

**Herramientas para regulaciones**:
- Freeze
- Approvals
- Whitelisting

### 5. Upgrades 🔄

**Patrones proxy**:
- Contratos actualizables
- Sin perder estado

### 6. Utilities 🧰

**Funciones auxiliares**:
- Math
- Strings
- Bitmaps
- Events

---

## Herramientas del Ecosistema

### Stellar Expert

**Definición**: El explorador más completo del ecosistema Stellar.

**Funciones**:
- 📊 **Métricas de la Red**: Validadores, actividad, bloques, volumen
- 📝 **Transacciones y Cuentas**: Inspeccionar cualquier transacción, cuenta o activo
- 🔍 **Contratos y Eventos**: Revisar contratos desplegados, logs, storage, métodos invocados
- 🐛 **Análisis de Contratos**: Ideal para debugging y auditoría

**Uso**: Validar lo que realmente sucedió en la red (deploys, llamadas, eventos, cambios de estado).

---

### Stellar Lab

**Definición**: Herramienta para construir, firmar y enviar transacciones sin escribir backend.

**Funcionalidades**:

#### 1. Construcción de Transacciones
- Crear operaciones complejas
- Ver estructura real de transacciones

#### 2. Herramientas de Debugging
- Simular operaciones
- Revisar errores
- Inspeccionar payload
- Entender comportamiento antes de enviar

#### 3. Testing e Interacción con Contratos
- Invocar métodos
- Enviar parámetros
- Simular ejecuciones
- Ver respuestas en tiempo real

---

## Workflow de Desarrollo

```
1. Diseñar contrato
   └─ Seguir buenas prácticas

2. Implementar usando OpenZeppelin
   └─ Módulos probados y seguros

3. Testear localmente
   └─ Unit tests

4. Desplegar en Testnet
   └─ Usar Stellar Lab

5. Validar en Stellar Expert
   └─ Revisar eventos y estado

6. Debugging
   └─ Stellar Lab + Expert

7. Desplegar en Mainnet
   └─ Cuando todo está validado
```

---

## Recursos del Instructor

**Matías Aguilar**:
- 🎥 YouTube: https://www.youtube.com/@aguilar1x
- 💻 GitHub: https://github.com/aguilar1x
- 🐦 X/Twitter: https://x.com/aguilar1x1

---

## Resumen Clave Día 2

### Stellar
- Red financiera global, no computadora global
- Consenso SCP: federado, rápido, eficiente
- Enfoque en pagos, stablecoins y productos financieros reales
- "Confiable siempre gana"

### Smart Contracts
- Soroban: Motor basado en Rust + WASM
- Estándares SEP/CAP para interoperabilidad
- OpenZeppelin: Código auditado y modular
- Herramientas: Stellar Lab (desarrollo) y Stellar Expert (explorador)

### Buenas Prácticas
- Seguridad: Evitar overflows, controlar acceso
- Diseño: Modular, eventos claros, storage explícito
- Testing: Unit tests, escenarios adversos
- Optimización: Minimizar storage, evitar loops innecesarios

---

> "El desarrollo de smart contracts no se trata solo de escribir código que funcione,  
> sino de escribir código que sea seguro, eficiente y mantenible."
