# 🧠💻 Tarea-2: Explorando el Futuro de la Computación

Repositorio de la tarea 2 sobre arquitecturas emergentes de computación: cuántica, neuromórfica, biológica, heterogénea y de borde. Incluye investigación, historia, ventajas, desventajas, diagramas y referencias organizadas en un README con formatos e imágenes.

------------

## 📚 Contenido

1. [Computación Cuántica](#computación-cuántica)
   - [Arquitectura de un computador cuántico](#arquitectura-de-un-computador-cuántico)
   - [Historia, ventajas y desventajas](#historia-ventajas-y-desventajas)
   - [Principios y conceptos clave](#principios-y-conceptos-clave)
     - Superposición
     - Entrelazamiento
     - Interferencia cuántica
     - Medición probabilística
     - Desafío de decoherencia
     - Tipos de comunicación cuántica
     - Puertas cuánticas

2. [Computación Neuromórfica](#computación-neuromórfica)
   - [Arquitectura y funcionamiento](#arquitectura-y-funcionamiento)
   - [Ventajas y desventajas](#ventajas-y-desventajas)
   - [Hardware utilizado](#hardware-utilizado)
   - [Tipos de computación neuromórfica](#tipos-de-computación-neuromórfica)

3. [Ordenadores Biológicos](#ordenadores-biológicos)
   - [Arquitectura y tipos existentes](#arquitectura-y-tipos-existentes)
   - [Principales hitos](#principales-hitos)

4. [Computación Heterogénea](#computación-heterogénea)
   - [Historia](#historia)
   - [Ventajas y desventajas](#ventajas-y-desventajas-1)

5. [Computación de Borde](#computación-de-borde)
   - [Historia](#historia-1)
   - [Ventajas y desventajas](#ventajas-y-desventajas-2) 

------------

# 1) 🧑‍🔬⚛️💻 Computacion Cuantica
### 1.1) **¿Que es la Computacion Cuantica?
La computación cuántica es un nuevo tipo de informática que aprovecha las leyes de la mecánica cuántica para resolver problemas que serían demasiado difíciles o lentos para una computadora normal.

🔹 En lugar de usar bits (que solo pueden valer 0 o 1), utiliza cúbits.
🔹 Los cúbits tienen dos propiedades especiales:
- Superposición → pueden estar en 0 y 1 al mismo tiempo.
- Entrelazamiento → varios cúbits pueden estar conectados entre sí, de modo que el cambio en uno afecta al otro instantáneamente.

Gracias a esto, una computadora cuántica puede hacer muchos cálculos en paralelo, logrando una enorme potencia en ciertos problemas.

📌 Aplicaciones actuales y futuras:

* Medicina → simulación de moléculas para descubrir nuevos fármacos.
* Economía → optimización de carteras y predicciones financieras.
* Inteligencia artificial → entrenamiento más rápido de modelos complejos.
* Medio ambiente → modelación climática para prever y combatir el cambio climático.

En resumen: la computación cuántica no reemplaza a la clásica, sino que la complementa para resolver los problemas más complejos y pesados.

<img width="500" height="600" alt="Image" src="https://github.com/user-attachments/assets/5d37c5fd-5fc4-4eb5-ad5b-b6b8e71cfb13" />

> - BIT y QUBIT

🌟 Principios clave de la Computación Cuántica

🔹 Cúbits
* Son como los “bits” de una computadora clásica, pero mucho más poderosos.
* Mientras un bit solo puede ser 0 o 1, un cúbit puede ser 0, 1 o ambos al mismo tiempo gracias a la superposición.

🔹 Superposición
* Imagina lanzar una moneda: mientras gira en el aire, está en una mezcla de cara y sello al mismo tiempo.
* Eso mismo hacen los cúbits: pueden representar varios estados simultáneamente, lo que permite explorar muchas soluciones a la vez.

🔹 Entrelazamiento
* Es como si dos cúbits estuvieran “conectados mágicamente”.
* Si cambias uno, el otro también cambia, aunque estén separados por miles de kilómetros.
* Esto permite que la información esté fuertemente correlacionada, abriendo la puerta a cálculos más veloces y coordinados.

🔹 Interferencia cuántica
* En el mundo cuántico, los resultados son probabilísticos (basados en posibilidades).
* La interferencia permite “jugar” con esas probabilidades:
   * Refuerza las respuestas correctas.
   * Elimina las incorrectas.
* Es como afinar una radio para escuchar solo la estación clara y silenciar el ruido.

👉 En conjunto, estos principios hacen que los computadores cuánticos puedan realizar cálculos masivos en paralelo y resolver problemas que serían imposibles para las computadoras tradicionales.

-----

# ⚛️ Arquitectura de un Computador Cuántico  

La **arquitectura de la computación cuántica** es el diseño estructural y operativo de los sistemas cuánticos, basados en principios de la **mecánica cuántica** para realizar cálculos complejos mediante **cúbits, puertas cuánticas** y **mecanismos de corrección de errores**.  

Esta arquitectura se organiza en **capas** que integran hardware especializado y software cuántico para hacer posible la computación cuántica.

---

## 🧩 Componentes Clave de la Arquitectura  

| 🔹 Componente | 📖 Descripción |
|--------------|----------------|
| **Cúbits** 🌀 | Unidad básica de información cuántica. Pueden estar en **superposición** (0, 1 o ambos a la vez) y **entrelazarse** con otros cúbits. |
| **Puertas Cuánticas** 🔑 | Operaciones que modifican el estado de los cúbits, equivalentes a las puertas lógicas clásicas. |
| **Corrección de Errores** 🛡️ | Mecanismos que protegen la información frente a la **decoherencia cuántica** (ejemplo: códigos de superficie). |

---

## 🏗️ Estructura en Capas  

Un computador cuántico se puede entender como un **modelo de capas**:

│ Procesador de Control y Host 🖥️ │
│ (algoritmos y software) │
│ Plano de Control y Medida 🎛️ │
│ (microondas, láseres, lecturas) │
│ Plano de Datos Cuánticos ⚛️ │
│ (cúbits y hardware físico) │

### 📌 Descripción de cada capa:  
- **Plano de datos cuánticos:** Contiene los cúbits físicos y los sistemas que mantienen su estado cuántico.  
- **Plano de control y medida:** Manipula cúbits mediante señales (microondas, láseres) y mide su estado.  
- **Procesador de control y host:** Ejecuta el algoritmo cuántico y conecta con software clásico.  

---

## ⚙️ Consideraciones Adicionales  

- 🌡️ **Entorno de operación:** Los cúbits requieren temperaturas **ultrabajas** para preservar la coherencia.  
- 💻 **Software cuántico:** Define algoritmos, circuitos lógicos y bibliotecas de desarrollo.  
- 📈 **Evolución y escalabilidad:** El gran reto está en manejar la **decoherencia** y la **corrección de errores** para aumentar el número de cúbits utilizables.

<img width="1200" height="763" alt="Image" src="https://github.com/user-attachments/assets/6a2897c2-3a6f-411d-a2c6-a2103c602c77" />

-----

### 📜 Historia, ventajas y desventajas

| ✅ Ventajas | ⚠️ Desventajas |
|------------|----------------|
| Resolución de problemas exponencialmente más rápida en criptografía y optimización | Estados frágiles: decoherencia y ruido |
| Criptografía cuántica segura 🔐 | Altos costos y complejidad técnica |
| Simulación de moléculas y materiales | Necesidad de enfriamiento extremo |
| Impulso en IA y machine learning 🤖 | Escalabilidad limitada de cúbits |

### 🔑 Principios y conceptos clave

- **Superposición** 🌀: un cúbit puede representar 0 y 1 a la vez.  
- **Entrelazamiento** 🔗: los cúbits comparten estados aunque estén separados.  
- **Interferencia** ✨: usada para amplificar soluciones correctas.  

---

## 2- 🧠🤖 Computación Neuromórfica

### 🧩 ¿Qué es?

Imita el **funcionamiento del cerebro humano** con neuronas artificiales que procesan información de forma distribuida, eficiente y adaptable.  

### 🏗️ Arquitectura y funcionamiento

| 🧱 Elemento | 📌 Descripción |
|-------------|----------------|
| Neuronas artificiales (SNNs) | Procesan picos eléctricos en lugar de valores continuos |
| Sinapsis (memristores) | Ajustan conexiones dinámicamente |
| Procesamiento event-driven ⚡ | Solo se activa con estímulos → ahorro energético |

### ⚖️ Ventajas y desventajas

| ✅ Ventajas | ⚠️ Desventajas |
|------------|----------------|
| Consumo hasta 1000x menor 🔋 | Falta de estándares universales |
| Adaptación en tiempo real (ideal IA en edge) 🤖 | Ecosistema de software en desarrollo |
| Privacidad mejorada (procesamiento local) 🔒 | Programación compleja |
| Uso eficiente en IoT | Escalabilidad aún limitada |

### 🖥️ Hardware utilizado

- **Intel Loihi** 🖤  
- **IBM TrueNorth** 🧩  
- **BrainChip Akida** 🔋  
- **SpiNNaker (UK)** 🧠  

### 🌐 Tipos

1. Simulación por software  
2. Hardware neuromórfico dedicado  
3. Modelos híbridos  
4. Neuromorphic-Quantum 🚀  

---

## 3- 🧬💻 Ordenadores Biológicos

### 🧬 ¿Qué son?

Usan **moléculas biológicas** (ADN, proteínas o células) como elementos de cálculo.  

### 🏗️ Arquitectura y tipos

| 🔖 Tipo | 📌 Descripción |
|---------|----------------|
| Computación con ADN 🧬 | Usa reacciones químicas para resolver problemas |
| Computación proteica | Interacciones moleculares como lógica |
| Computación celular 🧫 | Células vivas programadas para cálculos |

### 📜 Hitos

- **1994**: Leonard Adleman → 1ª demostración con ADN.  
- Década de 2000 → biología sintética avanza.  
- Actualidad → aplicaciones en **medicina personalizada** y diagnósticos inteligentes.  

---

## 4- 🖥️⚡ Computación Heterogénea

### 🖥️ ¿Qué es?

Uso conjunto de **CPU, GPU, FPGA y ASICs** para maximizar rendimiento y eficiencia.  

### 📜 Historia

- **2000s**: auge de GPUs para cálculos científicos.  
- Hoy: se usa en **IA, supercomputación y móviles**.  

### ⚖️ Ventajas y desventajas

| ✅ Ventajas | ⚠️ Desventajas |
|------------|----------------|
| Gran rendimiento en IA y Big Data 📊 | Programación compleja |
| Eficiencia energética 💡 | Fragmentación de software |
| Flexibilidad en cargas de trabajo | Costo de integración alto |

---

## 5- 🌐📡 Computación de Borde

### 🌍 ¿Qué es?

Procesamiento de datos **cerca de donde se generan** (sensores, IoT) → menor latencia y dependencia de la nube.  

### 📜 Historia

- Surge con el **IoT**.  
- Crece con el despliegue de **5G y dispositivos inteligentes**.  

### ⚖️ Ventajas y desventajas

| ✅ Ventajas | ⚠️ Desventajas |
|------------|----------------|
| Baja latencia ⚡ | Menor capacidad que la nube |
| Ahorro de ancho de banda 📶 | Requiere infraestructura distribuida |
| Privacidad local 🔒 | Escalabilidad difícil |
| Ideal para IA en tiempo real 🤖 | Costo de mantenimiento |

---

## 📚 Referencias

- Quantum Computing: [Quantum Zeitgeist](https://quantumzeitgeist.com/quantum-computing-and-neuromorphic-computing-comparing-future-technologies/?utm_source=chatgpt.com), [Arxiv](https://arxiv.org/abs/2010.15559?utm_source=chatgpt.com), [Wikipedia](https://en.wikipedia.org/wiki/Quantum_computing?utm_source=chatgpt.com)  
- Neuromorphic: [BuiltIn](https://builtin.com/artificial-intelligence/neuromorphic-computing?utm_source=chatgpt.com), [Elprocus](https://www.elprocus.com/neuromorphic-computing/?utm_source=chatgpt.com), [Tom’s Guide](https://www.tomsguide.com/computing/were-building-chips-that-think-like-the-brain-i-got-a-front-row-seat-to-see-how-neuromorphic-computing-will-transform-your-next-smart-device?utm_source=chatgpt.com)  
- Biological Computing: [Wikipedia](https://en.wikipedia.org/wiki/Biological_computing?utm_source=chatgpt.com)  
- Heterogeneous: [Supermicro](https://www.supermicro.com/en/glossary/heterogeneous-computing?utm_source=chatgpt.com), [ACM](https://cacm.acm.org/practice/heterogeneous-computing/?utm_source=chatgpt.com), [Intel](https://www.intel.com/content/www/us/en/docs/sycl/introduction/latest/01-homogeneous-vs-heterogeneous.html?utm_source=chatgpt.com)  
- Edge Computing: [Wikipedia](https://en.wikipedia.org/wiki/Edge_computing?utm_source=chatgpt.com)  
