# Finanzas Cuantitativas – Cálculo Estocástico

## Autores
- Alvaro García
- Tomás Natividad

Universidad Panamericana  
Licenciatura en Finanzas Cuantitativas  
Profesor: Dr. Julio César Galindo

---

# Descripción del Repositorio

Este repositorio contiene el proyecto final y los laboratorios desarrollados para la materia de Cálculo Estocástico y Finanzas Cuantitativas.

El objetivo general es aplicar herramientas de procesos estocásticos, simulación Monte Carlo, movimiento browniano y teoría de valuación neutral al riesgo para modelar activos financieros y analizar derivados.

---

# Estructura del Repositorio

```text
.
├── Proyecto Estocástico Alvaro García y Tomás Natividad.pdf
├── Proyecto_Martingalas.tex
├── Proyecto_calculo_estocastico.ipynb
├── Laboratorios.ipynb
└── README.md
```

---

# Proyecto Final

## Cambio de Medida y Martingalas en Derivados

### Objetivo

Verificar numéricamente la propiedad de martingala de los precios descontados bajo la medida neutral al riesgo mediante simulación Monte Carlo.

### Temas principales

- Movimiento Browniano Geométrico (GBM)
- Cambio de medida
- Teorema de Girsanov
- Densidad de Radon-Nikodym
- Martingalas
- Medida histórica P
- Medida neutral al riesgo Q
- Valuación de opciones europeas
- Simulación Monte Carlo

### Metodología

Se calibró un modelo GBM utilizando datos históricos del ETF SPY entre 2021 y 2023.

Posteriormente se generaron 10,000 trayectorias simuladas bajo las medidas P y Q para comparar el comportamiento del precio descontado del activo.

### Resultados

- Bajo la medida Q, el precio descontado converge a su valor inicial.
- Bajo la medida P, el precio descontado incorpora una prima de riesgo y no es martingala.
- Los precios Monte Carlo bajo Q son consistentes con Black-Scholes.

---

# Laboratorios

El archivo `Laboratorios.ipynb` contiene ejercicios y aplicaciones prácticas desarrolladas durante el curso.

Temas abordados:

- Simulación de variables aleatorias
- Procesos estocásticos
- Movimiento Browniano
- Movimiento Browniano Geométrico
- Integración estocástica
- Simulación Monte Carlo
- Aplicaciones financieras
- Valuación de derivados

---

# Tecnologías Utilizadas

- Python
- NumPy
- Pandas
- Matplotlib
- SciPy
- yFinance
- Jupyter Notebook
- LaTeX

---

# Referencias

- Black, F. & Scholes, M. (1973). The Pricing of Options and Corporate Liabilities.
- Shreve, S. (2004). Stochastic Calculus for Finance II.
- Bjork, T. (2009). Arbitrage Theory in Continuous Time.
- Øksendal, B. (2003). Stochastic Differential Equations.
- Galindo, J. C. (2025). Material del curso.
