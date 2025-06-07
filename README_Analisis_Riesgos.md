# 📊 Laboratorio: Análisis de Riesgos – Cisco CyberOps (Módulo 26.2)

Este repositorio documenta el laboratorio correspondiente al **módulo 26.2 del curso Cisco CyberOps Associate**, orientado al uso de metodologías cuantitativas y cualitativas para la gestión de riesgos en activos tecnológicos. Se aplican métricas como SLE, ARO y ALE para fundamentar decisiones estratégicas en ciberseguridad.

---

## 🎯 Objetivos del laboratorio

- Aplicar métodos de **análisis cuantitativo y cualitativo** de riesgos.
- Calcular métricas clave: **SLE** (Single Loss Expectancy), **ARO** (Annual Rate of Occurrence), **ALE** (Annual Loss Expectancy).
- Utilizar **matrices de impacto** para valorar el riesgo cualitativamente.
- Evaluar riesgos en distintos escenarios: servidores, redes, punto de venta y entornos en la nube.

---

## 🧪 Estructura del laboratorio

### 🔹 Parte 1: Análisis cuantitativo y cualitativo

- **Valor del servidor**: $135,000 USD
- **Justificación del costo intangible**: reputación, pérdida de confianza, legales, recuperación.
- **Cálculo de SLE**:
  - Falla de disco: $67,500
  - Ransomware: $135,000
- **Cálculo de ARO**:
  - Ransomware: 0.5
  - Falla de hardware: 0.4
- **Cálculo de ALE**:
  - Falla de hardware: $12,500
  - Hacking: $5,000

- **Evaluación cualitativa**:
  - Falla servidor web: Severo
  - Ataque DoS: Severo
  - Incendio: Moderado
  - Violación de datos: Crítico
  - Tornado: Menor

---

### 🔹 Parte 2: Escenarios y ALE calculado

| Escenario                  | ALE Total |
|---------------------------|-----------|
| Equipos portátiles        | $1,824    |
| Red SAN                   | $68,750   |
| Servidor base de datos    | $11,816   |
| Punto de venta (POS)      | $4,080    |
| Nube privada              | $345,000  |

---

## 🛠️ Herramientas y conceptos aplicados

- SLE, ARO, ALE
- Análisis cualitativo de impacto
- Evaluación de activos críticos
- Toma de decisiones basada en riesgo
- Gestión de continuidad operativa

---

## 📁 Archivos del repositorio

```
lab-analisis-riesgos/
├── README.md
├── LICENSE
└── documentos/
    └── calculos_riesgos_laboratorio_26.2.pdf
```

---

## 🧠 Conclusión profesional

El análisis de riesgos cuantificable permite tomar decisiones informadas y priorizar inversiones en seguridad. Este laboratorio fortalece habilidades clave para roles técnicos, analíticos y estratégicos en el campo de la ciberseguridad.

---

## 👨‍💻 Autor

- **Nombre:** Lester Alfonso Dávila Escobedo, CPA  
- **Curso:** Cisco CyberOps – Módulo 26.2  
- **Fecha:** Junio 2025  
- **Licencia:** Creative Commons BY 4.0  
- **LinkedIn:** [linkedin.com/in/lester-alfonso-davila-escobedo-cpa](https://www.linkedin.com/in/lester-alfonso-davila-escobedo-cpa)
