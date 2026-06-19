# QuantumVault Financial Evaluation

Evaluación financiera académica de **QuantumVault S.L.**, un proyecto de startup tecnológica orientado al almacenamiento cloud seguro mediante criptografía post-cuántica y arquitectura zero-knowledge.

## Descripción

QuantumVault S.L. se plantea como una empresa SaaS del sector cloud computing y ciberseguridad. Su propuesta de valor combina almacenamiento seguro, cifrado extremo a extremo, arquitectura zero-knowledge, cumplimiento normativo europeo y uso de criptografía post-cuántica.

El objetivo del proyecto es analizar si la inversión resulta viable desde un punto de vista económico-financiero.

## Metodología

El análisis se ha realizado mediante metodología clásica de evaluación de proyectos:

- Flujo de Fondos Puro
- Flujo de Fondos del Inversionista
- VAN
- TIR
- VAE
- Payback descontado
- Análisis de sensibilidad
- Punto VAN = 0
- Simulación Monte Carlo

El horizonte temporal del análisis es de 5 años y las magnitudes se expresan en euros constantes de 2026.

## Hipótesis principales

| Variable | Valor |
|---|---:|
| Horizonte temporal | 5 años |
| Clientes iniciales | 20 |
| Crecimiento anual de clientes | 40 % |
| Precio mensual por empresa | 150 € |
| Inversión inicial | 153.500 € |
| Capital propio | 40 % |
| Deuda bancaria | 60 % |
| Ke nominal | 12 % |
| Kd nominal | 5 % |
| Impuesto sobre sociedades | 25 % |

## Resultados principales

| Indicador | Resultado |
|---|---:|
| VAN del proyecto | -461.713,11 € |
| TIR del proyecto | No calculable |
| VAE | 117.896,69 € |
| VAN del inversionista | -490.611,23 € |
| TIR del inversionista | No calculable |
| Payback descontado | No se alcanza |
| Clientes iniciales necesarios para VAN = 0 | 52 |
| Probabilidad VAN > 0 en Monte Carlo | 0,00 % |

## Conclusión

Bajo las hipótesis actuales, el proyecto no resulta financieramente viable. El VAN es negativo, la TIR no es calculable y el periodo de recupero no se alcanza dentro del horizonte de cinco años.

La causa principal es la insuficiencia de ingresos iniciales frente a una estructura fija elevada de costes. Aunque la idea de negocio es innovadora y coherente con tendencias reales del mercado, el modelo financiero necesitaría mayor escala comercial, precios más ajustados al valor aportado o un horizonte de evaluación más amplio.

Por tanto, la decisión racional bajo el escenario base es no acometer la inversión en su configuración actual, aunque el proyecto podría ser reconsiderado con una reformulación de sus hipótesis financieras.

## Contenido del repositorio

```text
.
├── README.md
├── Informe_QuantumVault_SL.docx
├── Modelo_financiero_QuantumVault.xlsx
├── QuantumVault.md
└── graficos/